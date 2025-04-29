# WordPress Penetration Testing Checklist

This checklist helps you test all possible security vulnerabilities in your WordPress site.

---

## 1. **Reconnaissance (Public Information Gathering)**

- **Check WordPress Version**
    - Search for the version in the page source:
      ```html
      <meta name="generator" content="WordPress X.X.X" />
      ```
    - Check for the presence of:
      ```
      https://example.com/readme.html
      https://example.com/license.txt
      ```

- **Identify Active Themes and Plugins**
    - Search in the source code for:
      ```
      /wp-content/themes/
      /wp-content/plugins/
      ```
    - Identify known vulnerabilities in plugins and themes.

- **Enumerate Users**
    - Check for user enumeration via URL:
      ```
      https://example.com/?author=1
      https://example.com/?author=2
      ```

- **REST API User Discovery**
    - Check for exposed user info:
      ```
      https://example.com/wp-json/wp/v2/users
      ```

---

## 2. **Common Entry Points**

- **Brute Force Login Attempts**
    - Try default login credentials at `/wp-login.php`:
      - `admin`
      - `administrator`
      - `test`
      - `user`

- **Test XML-RPC**
    - Check if `xmlrpc.php` is enabled:
      ```
      https://example.com/xmlrpc.php
      ```
    - If active, it can be used for brute force and DDoS attacks.

---

## 3. **Sensitive File Access**

- **Check Access to Critical Files**
    - Try opening these files in the browser:
      ```
      https://example.com/wp-config.php
      https://example.com/.htaccess
      https://example.com/.env
      https://example.com/.git/
      https://example.com/composer.json
      https://example.com/package.json
      ```

- **Check for Backup Files**
    - Try accessing backup files:
      ```
      https://example.com/wp-config.php.bak
      https://example.com/backup.zip
      https://example.com/db.sql
      ```

---

## 4. **Test Directory Browsing**

- **Check if Directory Listing is Enabled**
    - Try browsing the following directories:
      ```
      https://example.com/wp-content/uploads/
      https://example.com/wp-content/themes/
      https://example.com/wp-content/plugins/
      ```
    - If directory listing is enabled, files can be easily accessed.

---

## 5. **Vulnerability Check (Automated Tools)**

- **WPScan** — Official WordPress vulnerability scanner.
    - [WPScan](https://wpscan.com/)

- **SecurityHeaders.com** — Check HTTP security headers.
    - [SecurityHeaders.com](https://securityheaders.com/)

- **Detectify** — Scan for vulnerabilities.
    - [Detectify](https://detectify.com/)

- **Pentest-Tools.com** — WordPress vulnerability scanning.
    - [Pentest-Tools](https://pentest-tools.com/website-vulnerability-scanning/wordpress-scanner)

---

## 6. **SQL Injection Testing**

- **Test for SQL Injection Vulnerabilities**
    - Add a `'` (single quote) to URL parameters:
      ```
      https://example.com/?id=1'
      ```
    - If the site throws a SQL error like:
      ```
      SQL syntax error near...
      ```
    - The site may be vulnerable to SQL Injection.

---

## 7. **Cross-Site Scripting (XSS) Testing**

- **Test for XSS Vulnerabilities**
    - Try injecting JavaScript into form fields:
      ```html
      <script>alert('XSS')</script>
      ```
    - Submit it to:
      - Contact forms
      - Search bars
      - Comment sections
    - If it triggers an alert or shows strange behavior, XSS is likely present.

---

## 8. **Summary of Common Weaknesses**

| Weakness                | What Hacker Can Access |
|-------------------------|------------------------|
| **Usernames**            | Brute-force login attempts |
| **Open Directory**       | Browse and download files |
| **Backup Files**         | Full site takeover (DB credentials, files) |
| **wp-config.php Leak**   | Database connection details |
| **XSS**                  | Site defacement, cookie stealing |
| **SQL Injection**        | Database extraction |
| **XML-RPC**              | Brute-force and DDoS attacks |
| **REST API Open**        | User enumeration and sensitive data leak |

---

## 9. **Next Steps: Hardening WordPress**

1. **Disable Directory Listing**
    - Add to `.htaccess`:
      ```apache
      Options -Indexes
      ```

2. **Protect Critical Files**
    - Add protection to `.htaccess` for wp-config.php and other sensitive files.

3. **Limit Login Attempts**
    - Use plugins to limit login attempts or set up two-factor authentication (2FA).

4. **Use Security Plugins**
    - Install plugins like **Wordfence**, **iThemes Security**, or **All In One WP Security** to automate protection.

5. **Regular Backups**
    - Ensure you have regular backups of the database and files to recover from potential attacks.
