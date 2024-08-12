# Ostnica Theme Documentation

## 1. Getting Started
- **Theme Name**: Ostnica
- **Description**: The theme is designed to take full advantage of advanced features. It includes theme options, multiple layout demos, an easy one-click demo import option, customization support, and many more features, making it a perfect choice for your website. Use it to create something cool and attractive, and share what you’ve learned with others.
- **Version**: 1.0.0
- **Author**: Codeholic IT Services PVT LTD.
- **License**: GPLv2 or later

## 2. General Requirements of Ostnica Theme
Before getting started with the Ostnica theme, you need to first ensure your server or WordPress installation meets the specific requirements:

1. **WordPress Version**: 5.8+
2. **PHP Version**: 7.4+
3. **PHP Configuration**:
   - `max_execution_time`: 600
   - `max_input_vars`: 3000
   - `memory_limit`: 1024M
   - `post_max_size`: 1024M
   - `max_file_upload` : 40
   - `upload_max_filesize`: 1024M

## 3. Installation 
You can install the theme in two ways:

**Method 1 - Via the WordPress Admin Dashboard**
1. Navigate to _Appearance > Themes > Add New_.

   ![Method 1 Step 1 Ostnica](https://github.com/user-attachments/assets/6571a360-0038-4526-9554-f721958be72a)

2. Click on the "Upload Theme" button and choose the Ostnica-theme.zip file you previously downloaded.
   
   ![Method 1 Step 2 Ostnica](https://github.com/user-attachments/assets/2031225b-f896-4f41-a44b-77c02ce28c3f)

3. Click the "Install Now" button to upload and install the theme.

**Method 2 - FTP Upload** 
1. Connect to your server via FTP software, using your FTP sever URL, FTP Username, FTP Password and a port number.
2. Once Logged In, Navigate to your _wp-content > themes_ folder.
3. Upload the Unzipped Ostnica Theme inside the _wp-content > themes_ folder.

      ![Method 2 Step 1 Ostnica](https://github.com/user-attachments/assets/8d893cc5-c7e9-4ffa-a025-6b5be886c449)

   Once the theme is uploaded , you will then need to activate it . To do so , navigate to the _Appearance > theme_ section and activate your theme.
   
      ![Method 1 Step 3 Ostnica](https://github.com/user-attachments/assets/e1f69a88-042d-49fc-a462-0097de77d43b)

## 4. Required Plugins

These are the required plugins we need to activate before using the theme's functionality:

- **Ostnica Elementor Addons**
  - Version: 1.0.0
  - Description: Plugin for Elementor addons

- **Ostnica Demo Import (for Elementor)**
  - Version: 1.0.0
  - Description: Plugin for importing pre-built pages (theme demos)

- **Ostnica Core**
  - Version: 1.0.0
  - Description: Plugin to manage custom post types

- **Contact Form 7**
  - Version: 5.4+

- **Elementor**
  - Version: 3.1+

- **MC4WP: Mailchimp for WordPress**
  - Version: [latest]

- **Ostnica Gutenberg Addon**
  - Version: 1.0.0

- **Ostnica Widget Importer Exporter Addon**
  - Version: 1.0.0

To install these required plugins, navigate to _Plugins_ and click `Begin installing plugins`.

   ![Required Plugin Install Step 1](https://github.com/user-attachments/assets/c5b7841c-d767-458e-8ba9-6995e3fc345c)

Now check the plugin checkbox to select all plugins, and under the _Bulk Actions_ dropdown, select _Install_ and click on the _Apply_ button to install all plugins at once.

   ![Install Required Plugin Bulk Action](https://github.com/user-attachments/assets/4bdf55b5-313e-4c16-b637-dbe7eedf418a)

If you encounter an error while using the bulk action, please try to install the plugins one by one.

## 5. Importing Demo Themes

1. Navigate to _Theme Options > Demo Import_.

   ![Demo Import Step 1](https://github.com/user-attachments/assets/d2dad04a-80ee-4c24-a0a9-1de4bc452cb1)

2. You will see the available theme demo. Select the theme demo you want to import.
3. Select the Option _INSTALL COMPLETE PRE-BUILT WEBSITE_ and click on _IMPORT_ button.
   
   ![Demo Import Step 2](https://github.com/user-attachments/assets/2076f278-d5a9-4e56-84ce-ec44b65f3bbe)

4. After the theme demo is imported successfully, you will see a success message as shown below. Click the _Close_ button and go to your homepage.

   ![Demo Import Step 3](https://github.com/user-attachments/assets/818ff6a0-1fde-46ca-9fbc-5970de15cb1e)

> [!Note]
> If you encounter issues with importing the theme demo, ensure you have followed the [General Requirements for the Ostnica Theme](tutorial-documention.md#2-general-requirements-of-ostnica-theme).

## 6. Setting the Demo Theme as the Homepage

1. By default, you will see the posts page on the homepage, as shown below.
   
   ![Screenshot 2024-08-07 152430](https://github.com/user-attachments/assets/9cf8a6a5-3a08-4bb7-b7d3-d8c88a57ec7b)

2. To set the demo import to be visible on the homepage, navigate to _Settings > Reading_.

   ![Set Demo Homepage step 1](https://github.com/user-attachments/assets/0262d03c-6e64-4a9b-8a99-839c40d5565d)

3. In the Reading Settings, under **Your homepage displays**, select the option _A static page_. Then, choose your desired _HomePage_ and _Posts page_ and click on _Save Changes_.

   ![Set Demo Homepage step 2](https://github.com/user-attachments/assets/76835f1b-f3e8-49a9-82f5-406a8236d10d)

4. Now navigate to the homepage, and your selected page will be visible.
   
   ![Screenshot 2024-08-07 170901](https://github.com/user-attachments/assets/97f359ab-603f-4a2e-8e32-9bed1747bcbd)

## 7. Setting Up Your Site Menu

1. Navigate to _Appearance > Menus_.

   ![Select Menu Step 1](https://github.com/user-attachments/assets/254b563d-d113-4e0d-a5e6-7373229623f4)
   
2. Select the _Manage Locations_ tab.

   ![Select Menu Step 2](https://github.com/user-attachments/assets/27511b92-6609-4a54-a94f-51e7b472ad21)
   
3. In _Manage Locations_, under the **Primary Menu** dropdown, select the menu you want to display. This will be shown on all pages of your website.
4. In _Manage Locations_, under the **Left Menu** dropdown, select the left menu, and under the **Right Menu** dropdown, select the right menu. These will be displayed when you choose the header option _Center Menu Center Logo_ or _Center Logo Left Menu Right Menu_ in _Theme Settings > Header_ under header layout options.

   ![Select Menu Step 3](https://github.com/user-attachments/assets/1a3b0784-674c-4e26-b264-e4e07a15498d)

5. Click on _Save Changes_ to apply the settings.

## 8. Ostnica Theme Options 

In the Admin dashboard menu, navigate to _Theme Options_ to find various options for customizing your website.

### General Tab > Theme Styling

Under the _General_ tab, in _Theme Styling_, you can customize the following:

1. **Font Family**
   - **Description:** Theme Options offers you a list of font families to customize the appearance of text across your entire website.
   - **Usage:** Select a font family from the list to apply it to all text elements site-wide.
   - **Screenshot (Backend Setting):**

        ![1](https://github.com/user-attachments/assets/bdc64b24-20df-413b-8002-f3eeb1714b2c)
  
   - **Screenshot (Frontend Preview):**

        ![Screenshot 2024-08-10 182803](https://github.com/user-attachments/assets/61351ac7-a423-4d3f-983e-c8fe906988b7)

2. **Link Color**
   - **Description:** This Theme Option allows you to change the color of all links across your entire website. By customizing the link color, you can ensure that                hyperlinks stand out or blend in with your site's design, improving both aesthetics and user experience.
   - **Screenshot (Backend Setting):**

      ![Link Color Theme Settings](https://github.com/user-attachments/assets/2ff0626d-5545-4169-8414-9753f4ecb6ac)

   - **Screenshot (Frontend Preview):**

      ![Link Color Theme Settings Frontend](https://github.com/user-attachments/assets/dcaa1552-9210-4554-9d3e-1ae108019007)

   - **Usage:** Select a color from the palette to apply to all hyperlinks. This change will reflect site-wide, making it easier for visitors to recognize and interact          with links on your pages.

2. **Theme Background Color**
   - **Description:** This Theme Option allows you to change the background color of your entire website. By selecting a color that complements your brand or design, you         can create a cohesive and visually appealing look for your site.
   - **Screenshot (Backend Setting):**
      
      ![Background color settings theme Options](https://github.com/user-attachments/assets/ed597a79-065f-4c3f-8823-9a6fb5afd0d8)

   - **Screenshot (Frontend Preview):**

      ![Background Color Settings Preview](https://github.com/user-attachments/assets/2b54f971-c244-4bc0-9d70-6dbb10307eb1)

   - **Usage:** Choose a color from the palette to set as the background for your website. This change will be applied to all pages, giving your site a consistent and            customized appearance.

2. **Smooth Scroll**
   - **Description:** This theme option allows you to enable or disable smooth scrolling behavior on your website, enhancing the user experience by providing a smoother          scroll effect.
   - **Screenshot (Backend Setting):**

      ![Smooth Scroll Theme Options Settings](https://github.com/user-attachments/assets/fea4cedd-cff4-4692-b1a7-6eb1607efdd8)

   - **Screenshot (Frontend Preview):**

      [Click here to watch the video](https://github.com/user-attachments/assets/571049c1-3bf8-457f-8356-303b3fcfd036)

   - **Usage:** Toggle to enable or disable smooth scrolling.
> [!IMPORTANT]
> To ensure smooth scrolling works, you need to enable it in your browser:
>
> **Chrome:**
>
> 1. Copy and paste the following URL into your Chrome address bar:
> 
> ```
> chrome://flags/
> ```
> 
> 2. Find "Smooth Scrolling" in the list, select "Enabled" from the dropdown, and relaunch Chrome.
>
> 3. See the screenshot below for guidance:
> 
> ![Screenshot 2024-08-12 122157](https://github.com/user-attachments/assets/dced811b-6872-4587-8d5e-fd6ead220168)
>
> **Firefox:**
>
> 1. Go to Firefox `Settings > General > Browsing`. </br>
>
> 2. Check the "Use smooth scrolling" box as shown below: </br>
>
> ![Screenshot 2024-08-12 122825](https://github.com/user-attachments/assets/cb8dacb5-02ca-467f-b402-646500d312fc)
>
> ![Screenshot 2024-08-12 122855](https://github.com/user-attachments/assets/0ba8372b-1ca3-434e-85d2-ecd14b0ec390)


2. **Back to Top**
   - **Description:** Show or hide the "Back to Top" button on the right side of the site.
   - **Screenshot (Backend Setting):** ![Back to Top Setting](https://github.com/user-attachments/assets/back-to-top-screenshot)
   - **Screenshot (Frontend Preview):** ![Back to Top Frontend Preview](https://github.com/user-attachments/assets/back-to-top-frontend-preview)
   - **Usage:** Toggle to display or hide the button.

### General Tab > Site Identity

Under the _General_ tab, in _Site Identity_, you can adjust the following:

1. **Text Logo**
   - **Description:** Set a text logo if no default header logo is provided.
   - **Screenshot (Backend Setting):** ![Text Logo Setting](https://github.com/user-attachments/assets/text-logo-screenshot)
   - **Screenshot (Frontend Preview):** ![Text Logo Frontend Preview](https://github.com/user-attachments/assets/text-logo-frontend-preview)
   - **Usage:** Enter the text for your logo.

2. **Text Logo Typography**
   - **Font Size:** Adjust the font size of the text logo.
     - **Screenshot (Backend Setting):** ![Font Size Setting](https://github.com/user-attachments/assets/font-size-screenshot)
     - **Screenshot (Frontend Preview):** ![Font Size Frontend Preview](https://github.com/user-attachments/assets/font-size-frontend-preview)
   - **Font Color:** Change the color of the text logo.
     - **Screenshot (Backend Setting):** ![Font Color Setting](https://github.com/user-attachments/assets/font-color-screenshot)
     - **Screenshot (Frontend Preview):** ![Font Color Frontend Preview](https://github.com/user-attachments/assets/font-color-frontend-preview)
   - **Font Weight:** Modify the font weight of the text logo.
     - **Screenshot (Backend Setting):** ![Font Weight Setting](https://github.com/user-attachments/assets/font-weight-screenshot)
     - **Screenshot (Frontend Preview):** ![Font Weight Frontend Preview](https://github.com/user-attachments/assets/font-weight-frontend-preview)
   - **Usage:** Style your text logo by adjusting these settings.

3. **Dark Header Logo**
   - **Description:** Set a logo for dark headers.
   - **Screenshot (Backend Setting):** ![Dark Header Logo Setting](https://github.com/user-attachments/assets/dark-header-logo-screenshot)
   - **Screenshot (Frontend Preview):** ![Dark Header Logo Frontend Preview](https://github.com/user-attachments/assets/dark-header-logo-frontend-preview)
   - **Usage:** Upload a logo for use with dark headers.

4. **Retina Header Logo**
   - **Description:** Upload a high-resolution logo for Apple devices.
   - **Screenshot (Backend Setting):** ![Retina Header Logo Setting](https://github.com/user-attachments/assets/retina-header-logo-screenshot)
   - **Screenshot (Frontend Preview):** ![Retina Header Logo Frontend Preview](https://github.com/user-attachments/assets/retina-header-logo-frontend-preview)
   - **Usage:** Upload a retina logo for better display on high-resolution screens.

5. **Light Header Logo**
   - **Description:** Set a logo for light headers.
   - **Screenshot (Backend Setting):** ![Light Header Logo Setting](https://github.com/user-attachments/assets/light-header-logo-screenshot)
   - **Screenshot (Frontend Preview):** ![Light Header Logo Frontend Preview](https://github.com/user-attachments/assets/light-header-logo-frontend-preview)
   - **Usage:** Upload a logo for use with light headers.

6. **Default Header Logo**
   - **Description:** Set the default logo for the standard header.
   - **Screenshot (Backend Setting):** ![Default Header Logo Setting](https://github.com/user-attachments/assets/default-header-logo-screenshot)
   - **Screenshot (Frontend Preview):** ![Default Header Logo Frontend Preview](https://github.com/user-attachments/assets/default-header-logo-frontend-preview)
   - **Usage:** Upload the default logo for the header.

7. **Site Logo Width**
   - **Description:** Adjust the logo width for desktop, tablet, and mobile devices.
   - **Screenshot (Backend Setting):** ![Site Logo Width Setting](https://github.com/user-attachments/assets/site-logo-width-screenshot)
   - **Screenshot (Frontend Preview):** ![Site Logo Width Frontend Preview](https://github.com/user-attachments/assets/site-logo-width-frontend-preview)
   - **Usage:** Set width values for different devices.

8. **Site Logo Height**
   - **Description:** Adjust the logo height for desktop, tablet, and mobile devices.
   - **Screenshot (Backend Setting):** ![Site Logo Height Setting](https://github.com/user-attachments/assets/site-logo-height-screenshot)
   - **Screenshot (Frontend Preview):** ![Site Logo Height Frontend Preview](https://github.com/user-attachments/assets/site-logo-height-frontend-preview)
   - **Usage:** Set height values for different devices.

## Menu > General

### 1. Menu Font Style
- **Description:** Transform the menu text to uppercase, lowercase, or capitalize.
- **Options:**
  - **Uppercase:** Converts all menu text to uppercase letters.
  - **Lowercase:** Converts all menu text to lowercase letters.
  - **Capitalize:** Capitalizes the first letter of each menu item.
- **Screenshot (Backend Setting):** ![Menu Font Style Setting](https://github.com/user-attachments/assets/menu-font-style-screenshot)
- **Screenshot (Frontend Preview):** ![Menu Font Style Frontend Preview](https://github.com/user-attachments/assets/menu-font-style-frontend-preview)
- **Usage:** Choose the desired text transformation for your menu items.

### 2. Menu Typography
- **Description:** Customize the typography settings for the navigation menu.
  - **Font Size:** Adjust the font size of the menu text.
  - **Font Weight:** Set the font weight for the menu text.
  - **Font Color:** Change the color of the menu text.
- **Screenshot (Backend Setting):** ![Menu Typography Setting](https://github.com/user-attachments/assets/menu-typography-screenshot)
- **Screenshot (Frontend Preview):** ![Menu Typography Frontend Preview](https://github.com/user-attachments/assets/menu-typography-frontend-preview)
- **Usage:** Configure these settings to match your site's design preferences.

## Header > General

### 1. Header Type
- **Description:** Choose the type of header to display.
  - **Light Header:** A header with a light background suitable for dark text.
  - **Dark Header:** A header with a dark background suitable for light text.
  - **Default Header:** The default header style provided by the theme.
- **Screenshot (Backend Setting):** ![Header Type Setting](https://github.com/user-attachments/assets/header-type-screenshot)
- **Screenshot (Frontend Preview):** ![Header Type Frontend Preview](https://github.com/user-attachments/assets/header-type-frontend-preview)
- **Usage:** Select the header type that best fits your site’s design.

### 2. Sticky Header
- **Description:** Enable or disable the sticky header feature, which keeps the header fixed at the top of the page as you scroll.
- **Screenshot (Backend Setting):** ![Sticky Header Setting](https://github.com/user-attachments/assets/sticky-header-screenshot)
- **Screenshot (Frontend Preview):** ![Sticky Header Frontend Preview](https://github.com/user-attachments/assets/sticky-header-frontend-preview)
- **Usage:** Toggle the switch to enable or disable the sticky header.

### 3. Transparent Header
- **Description:** Enable or disable the transparency of the header.
- **Screenshot (Backend Setting):** ![Transparent Header Setting](https://github.com/user-attachments/assets/transparent-header-screenshot)
- **Screenshot (Frontend Preview):** ![Transparent Header Frontend Preview](https://github.com/user-attachments/assets/transparent-header-frontend-preview)
- **Usage:** Toggle the switch to enable or disable header transparency.

### 4. Header Layout
- **Description:** Select from different header layout styles.
  - **Hamburger Menu Right:** The hamburger menu icon is positioned on the right.
  - **Hamburger Menu Full Width:** The hamburger menu icon spans the full width of the header.
  - **Hamburger Menu Left:** The hamburger menu icon is positioned on the left.
  - **Simple Menu:** A basic menu layout without additional features.
  - **Center Menu Center Logo:** The menu and logo are centered within the header.
  - **Center Logo Left Menu Right Menu:** The logo is centered, with the menu items on the left and right.
  - **Center Menu Blur Background:** The menu is centered with a blurred background effect.
- **Screenshot (Backend Setting):** ![Header Layout Setting](https://github.com/user-attachments/assets/header-layout-screenshot)
- **Screenshot (Frontend Preview):** ![Header Layout Frontend Preview](https://github.com/user-attachments/assets/header-layout-frontend-preview)
- **Usage:** Choose the layout that best fits your website's design.

### 5. Header Background
- **Description:** Change the background color of the header.
- **Screenshot (Backend Setting):** ![Header Background Setting](https://github.com/user-attachments/assets/header-background-screenshot)
- **Screenshot (Frontend Preview):** ![Header Background Frontend Preview](https://github.com/user-attachments/assets/header-background-frontend-preview)
- **Usage:** Select a color to set as the header background.

### 6. Header Height
- **Description:** Set the height of the header for different devices.
  - **Desktop:** Height of the header on desktop screens.
  - **Tablet:** Height of the header on tablet screens.
  - **Mobile:** Height of the header on mobile screens.
- **Screenshot (Backend Setting):** ![Header Height Setting](https://github.com/user-attachments/assets/header-height-screenshot)
- **Screenshot (Frontend Preview):** ![Header Height Frontend Preview](https://github.com/user-attachments/assets/header-height-frontend-preview)
- **Usage:** Enter height values for desktop, tablet, and mobile devices to adjust the header’s size.

## Page > General

### 1. Sidebar
- **Description:** Enable or disable the sidebar on the post page, allowing you to display widgets or posts. Posts are displayed only when you select them from the "Select Page" options.
- **Sidebar Widgets:** To display widgets in the left sidebar, navigate to _Appearance > Widgets > Left Sidebar_ and add content. For the right sidebar, navigate to _Appearance > Widgets > Right Sidebar_ and add your content.
- **Screenshot (Backend Setting):** ![Sidebar Setting](https://github.com/user-attachments/assets/sidebar-setting-screenshot)
- **Screenshot (Frontend Preview):** ![Sidebar Frontend Preview](https://github.com/user-attachments/assets/sidebar-frontend-preview)
- **Usage:** Toggle the switch to enable or disable the sidebar on the post page.

### 2. Select Sidebar Position
- **Description:** Choose the position where the sidebar will appear on the page. The available options include:
  - **Left Sidebar:** Displays the sidebar on the left side of the page.
  - **Right Sidebar:** Displays the sidebar on the right side of the page.
  - **Both Sidebars:** Displays sidebars on both the left and right sides of the page.
- **Screenshot (Backend Setting):** ![Sidebar Position Setting](https://github.com/user-attachments/assets/sidebar-position-setting-screenshot)
- **Screenshot (Frontend Preview):** ![Sidebar Position Frontend Preview](https://github.com/user-attachments/assets/sidebar-position-frontend-preview)
- **Usage:** Select the desired sidebar position to apply it to your pages.

### 3. Select Page
- **Description:** Provides a list of posts that you can choose to display in the sidebar. This feature allows you to curate specific content that appears alongside your main content.
- **Screenshot (Backend Setting):** ![Select Page Setting](https://github.com/user-attachments/assets/select-page-setting-screenshot)
- **Screenshot (Frontend Preview):** ![Select Page Frontend Preview](https://github.com/user-attachments/assets/select-page-frontend-preview)
- **Usage:** Select the posts from the provided list to display them in the sidebar.
  
### 4. Portfolio Page Layout
- **Description:** Choose the design layout for your portfolio page.
- **Options:** 
  - **Layout 1:** [Description or screenshot of Layout 1]
  - **Layout 2:** [Description or screenshot of Layout 2]
- **Usage:** Select the layout that best fits your portfolio design preferences.
- **Screenshot (Backend Setting):** ![Portfolio Page Layout Backend](https://github.com/user-attachments/assets/portfolio-page-layout-screenshot)
- **Screenshot (Frontend Preview):** ![Portfolio Page Layout Frontend](https://github.com/user-attachments/assets/portfolio-page-layout-frontend-screenshot)

### 5. Portfolio List Page Settings
- **Description:** Configure settings for the portfolio list page to customize its appearance and functionality.
- **Select Settings for Portfolio List Page:**
  - **Post Order:** 
    - **Description:** Determine the order in which posts appear on the portfolio list page (ascending or descending).
    - **Usage:** Choose the preferred order for displaying portfolio items.
    - **Screenshot (Backend Setting):** ![Post Order Backend](https://github.com/user-attachments/assets/post-order-screenshot)
    - **Screenshot (Frontend Preview):** ![Post Order Frontend](https://github.com/user-attachments/assets/post-order-frontend-screenshot)

  - **Posts Per Page:** 
    - **Description:** Set the number of posts to display per page on the portfolio list page.
    - **Usage:** Enter the desired number of posts to show on each page of the portfolio list.
    - **Screenshot (Backend Setting):** ![Posts Per Page Backend](https://github.com/user-attachments/assets/posts-per-page-screenshot)
    - **Screenshot (Frontend Preview):** ![Posts Per Page Frontend](https://github.com/user-attachments/assets/posts-per-page-frontend-screenshot)

### 6. Post Page Layout
- **Description:** Choose the design layout for individual post pages.
- **Options:** 
  - **Layout 1**
  - **Layout 2**
- **Usage:** Select the layout that best fits your design preferences for individual posts.
- **Screenshot (Backend Setting):** ![Post Page Layout Backend](https://github.com/user-attachments/assets/post-page-layout-screenshot)
- **Screenshot (Frontend Preview):** ![Post Page Layout Frontend](https://github.com/user-attachments/assets/post-page-layout-frontend-screenshot)

### 7. Portfolio List Page Settings
- **Description:** Configure settings for the portfolio list page to control post display.
- **Post Order:** 
  - **Description:** Arrange posts in ascending or descending order.
  - **Options:**
    - **Ascending:** Posts will be displayed from oldest to newest.
    - **Descending:** Posts will be displayed from newest to oldest.
  - **Screenshot (Backend Setting):** ![Post Order Backend](https://github.com/user-attachments/assets/post-order-screenshot)
  
- **Posts Per Page:** 
  - **Description:** Set the number of posts to display per page in the portfolio list.
  - **Usage:** Enter the desired number to limit the posts shown on each page.
  - **Screenshot (Backend Setting):** ![Posts Per Page Backend](https://github.com/user-attachments/assets/posts-per-page-screenshot)

- **Screenshot (Frontend Preview):** ![Portfolio List Page Settings Frontend](https://github.com/user-attachments/assets/portfolio-list-page-settings-frontend-screenshot)

## Footer > Footer Settings

### Footer Layout
- **Description:** Customize your footer's design with various layout options.
- **Customization:** Create your footer layout from _Appearance > Widgets > Footer [Area Name]_.
- **Usage:** Save changes to apply the updated footer design to your site.
- **Screenshot (Backend Setting):** ![Footer Layout Backend](https://github.com/user-attachments/assets/footer-layout-screenshot)
- **Screenshot (Frontend Preview):** ![Footer Layout Frontend](https://github.com/user-attachments/assets/footer-layout-frontend-screenshot)

### Box Layout
- **Description:** Enable or disable a boxed layout for the footer.
- **Usage:** Toggle this setting to apply a boxed or full-width footer layout.
- **Screenshot (Backend Setting):** ![Box Layout Backend](https://github.com/user-attachments/assets/box-layout-screenshot)
- **Screenshot (Frontend Preview):** ![Box Layout Frontend](https://github.com/user-attachments/assets/box-layout-frontend-screenshot)

### Sticky Footer
- **Description:** Make the footer sticky, so it stays fixed at the bottom of the page while scrolling.
- **Usage:** Toggle this setting to enable or disable the sticky footer.
- **Screenshot (Backend Setting):** ![Sticky Footer Backend](https://github.com/user-attachments/assets/sticky-footer-screenshot)
- **Screenshot (Frontend Preview):** ![Sticky Footer Frontend](https://github.com/user-attachments/assets/sticky-footer-frontend-screenshot)

### Footer Background Color
- **Description:** Set the background color for the footer.
- **Usage:** Choose a color that complements your site's design.
- **Screenshot (Backend Setting):** ![Footer Background Color Backend](https://github.com/user-attachments/assets/footer-bg-color-screenshot)
- **Screenshot (Frontend Preview):** ![Footer Background Color Frontend](https://github.com/user-attachments/assets/footer-bg-color-frontend-screenshot)

### Footer Font Color
- **Description:** Set the font color for the footer text.
- **Usage:** Select a color for optimal readability.
- **Screenshot (Backend Setting):** ![Footer Font Color Backend](https://github.com/user-attachments/assets/footer-font-color-screenshot)
- **Screenshot (Frontend Preview):** ![Footer Font Color Frontend](https://github.com/user-attachments/assets/footer-font-color-frontend-screenshot)

### Copyright Bar Content
- **Description:** Add content to the copyright bar, such as company details or legal information.
- **Usage:** Enter your content to display it at the bottom of the footer.
- **Screenshot (Backend Setting):** ![Copyright Bar Content Backend](https://github.com/user-attachments/assets/copyright-bar-content-screenshot)
- **Screenshot (Frontend Preview):** ![Copyright Bar Content Frontend](https://github.com/user-attachments/assets/copyright-bar-content-frontend-screenshot)

### Copyright Bar Typography
- **Description:** Customize the typography for the copyright content in the footer.
- **Options:**
  - **Font Size:** Set the font size for copyright text.
  - **Font Weight:** Adjust the font weight of copyright text.
  - **Font Color:** Change the font color for copyright text.
  - **Font Family:** Select the font family for copyright text.
- **Usage:** Adjust these settings to style the copyright content to match your site's design.
- **Screenshot (Backend Setting):** ![Copyright Bar Typography Backend](https://github.com/user-attachments/assets/copyright-bar-typography-screenshot)
- **Screenshot (Frontend Preview):** ![Copyright Bar Typography Frontend](https://github.com/user-attachments/assets/copyright-bar-typography-frontend-screenshot)

  
## Reset > Reset All Settings

### Reset All Settings
- **Description:** As the name suggests, this option resets the theme settings to their default state. When selected, all applied theme settings will be removed, and the theme will revert to its original configuration.
- **Screenshot (Backend Setting):** ![Reset All Settings](https://github.com/user-attachments/assets/reset-all-settings-screenshot)
- **Usage:** Use this option if you want to restore the theme to its default settings, removing any customizations you've made.

*Note: Attach screenshots from both the admin dashboard showing the theme options and the front end displaying the changes for clarity.*
