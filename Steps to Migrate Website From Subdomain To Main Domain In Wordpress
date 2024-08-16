# Steps to Migrate Website from Subdomain to Main Domain in WordPress

1. **Access cPanel:**
   - Open cPanel by entering your username and password.

2. **Backup and Move Subdomain Files:**
   - Navigate to `File Manager > public_html > subdomain_name`.
   - Make a copy of the subdomain folder and move it to the main domain directory within `public_html`.

3. **Duplicate the Database:**
   - Go to `phpMyAdmin` in cPanel.
   - Select the database of the subdomain you want to migrate.
   - Navigate to the **Operations** tab.
   - Under **Copy database to:**
     - Enter a unique name for the new duplicate database.
     - Ensure the duplicate database name is unique.
   - Click **Go** to create the duplicate.

4. **Create a New Database User for the Duplicated Database:**
   - Navigate to **MySQL Databases** in cPanel.
   - Under **MySQL Users**, create a new user:
     - Enter a username and password.
     - Note the username and password for future use.
     - Click **Create User**.
   - Ensure that all privileges are granted to the new user by selecting **All Privileges** and then click **Make Changes**.

5. **Assign the User to the Duplicated Database:**
   - In the **MySQL Databases** section, go to **Add User to Database**.
   - From the dropdown menus:
     - Select the new user you just created under **User**.
     - Select the duplicated database under **Database**.
   - Click **Add** to assign the user to the database with all privileges.

6. **Update Site URLs in the Duplicated Database:**
   - In the duplicated database, locate the `wp_options` table (or similar, depending on your CMS).
   - Search for the `siteurl` and `home` fields.
   - Change the URL from the subdomain to the main domain.

7. **Update Configuration Files:**
   - Update the `wp-config.php` file (or equivalent) with the new database name and the new user credentials.

8. **Update Permalinks:**
   - Go to your main domain URL and navigate to the WordPress admin dashboard.
   - Under **Settings > Permalinks**, click **Save Changes** to update the permalink structure.

9. **Replace URLs Using the Better Search Replace Plugin:**
   - In the WordPress admin dashboard, go to **Plugins > Add New**.
   - Search for the **Better Search Replace** plugin, install, and activate it.
   - After activation, navigate to **Settings > Better Search Replace**.
   - In the **Search for** field, paste the subdomain URL.
   - In the **Replace with** field, paste the main domain URL.
   - Select all tables by pressing **Ctrl + A**.
   - Perform a **Dry Run** to identify in which tables the subdomain URL is found.
   - Uncheck the **Dry Run** option and replace the URLs in all tables.
   - Repeat the process, performing dry runs and replacements until all instances of the subdomain URL are replaced and none are found.

10. **Test the Live Site:**
    - Visit your main domain to ensure everything has been migrated correctly.
    - Test all functionalities to make sure the site is working properly.

11. **Final Cleanup:**
    - Once the main domain is working perfectly, remove any unnecessary subdomain files and databases.
