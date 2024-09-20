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
   - **Screenshot (Backend Setting):** 

      ![Back To Top Theme Options Settings](https://github.com/user-attachments/assets/107baa77-62e9-4923-b463-10b50deaf49d)

   - **Screenshot (Frontend Preview):**

      ![Before](https://github.com/user-attachments/assets/69afcd1c-8549-4b7a-b603-47c0fe9a25b1)

   - **Usage:** Toggle to display or hide the button.

### General Tab > Site Identity

Under the _General_ tab, in _Site Identity_, you can adjust the following:

1. **Text Logo**
   - **Description:** This theme option allows you to create a custom text-based logo that will be displayed in the header of your website. The text logo will only appear       if no default header logo is set.
   - **Screenshot (Backend Setting):** 
      
      ![Text Logo Settings Theme Options](https://github.com/user-attachments/assets/eee3faf2-d3b8-401f-a360-1b033ba7840c)

   - **Screenshot (Frontend Preview):** 

      ![Screenshot 2024-08-12 145556](https://github.com/user-attachments/assets/78863b74-39b6-4636-813e-472a3a068ea0)
   
   - **Usage:** Enter the text for your logo.

1. **Text Logo Typography**
   - **Font Size:** This theme option allows you to customize the font size of the text-based logo.
     - **Screenshot (Backend Setting):**
    
       ![Font Size Text Typography Theme Options Settings](https://github.com/user-attachments/assets/a0d39616-b5b6-4baf-8070-f1ce631f6308)
      
     - **Screenshot (Frontend Preview):**
    
       ![Screenshot 2024-08-12 145703](https://github.com/user-attachments/assets/23faba0a-62df-444e-88ee-7c5e4f53ca8a)  

   - **Font Color:** This theme option allows you to pick a custom color for your text-based logo.
     - **Screenshot (Backend Setting):**
   
       ![Font Color Text Typography Theme Options Settings (1)](https://github.com/user-attachments/assets/109eed25-7ee3-4ebd-badc-b9c062238dcb)
        
     - **Screenshot (Frontend Preview):** 

       ![Screenshot 2024-08-12 150153](https://github.com/user-attachments/assets/c07be733-a538-476f-b24c-32fe6cf3ebac)
     
   - **Font Weight:** This theme option modify the font weight of the text-based logo.
     - **Screenshot (Backend Setting):** 

       ![Font Weight Text Typography Theme Options Settings](https://github.com/user-attachments/assets/6b1bd6a5-99f8-4340-a5cd-9b0ac820d2b5)
     
     - **Screenshot (Frontend Preview):**
    
       ![Screenshot 2024-08-12 150733](https://github.com/user-attachments/assets/0127e4d0-5441-4f9e-9d81-bf8fa1ca4910)

   - **Usage:** Style your text logo by adjusting these settings.

1. **Dark Header Logo**
   - **Description:** This option allows you to set a logo specifically for dark headers. The logo will only be visible if the selected header type is "Dark Header." To         set a dark header, navigate to _Theme Options > Header > General > Header Type_ and select "Dark Header."
   - **Screenshot (Backend Setting):** 

      ![Dark Logo Theme Options Settings](https://github.com/user-attachments/assets/78688ed2-a8ad-4147-95e4-f27cec4a162d)

   - **Screenshot (Frontend Preview):** 

      ![Screenshot 2024-08-12 181023](https://github.com/user-attachments/assets/de2f8d01-81c8-430e-89d0-86d98fe3473c)

   - **Usage:** Upload a logo for use with dark headers.

2. **Retina Header Logo**
   - **Description:** Upload a high-resolution logo for Apple devices.
   - **Screenshot (Backend Setting):** 

      ![Retina Logo Theme Options Settings](https://github.com/user-attachments/assets/1b76785e-8642-48ca-9bbe-3bbe826beeb9)

   - **Screenshot (Frontend Preview):** 

      ![Screenshot 2024-08-12 182042](https://github.com/user-attachments/assets/999a228f-c513-4018-a39b-a381c4e2cb69)

   - **Usage:** Upload a retina logo for better display on high-resolution screens.

2. **Light Header Logo**
   - **Description:** Set a logo for light headers.
   - **Screenshot (Backend Setting):**

     ![Light Logo Theme Options Settings](https://github.com/user-attachments/assets/570b05ba-704f-4a08-8abb-366bde4e8378)

   - **Screenshot (Frontend Preview):** 

      ![Screenshot 2024-08-12 182042](https://github.com/user-attachments/assets/c984680c-0406-432e-8001-63586efb5444)

   - **Usage:** Upload a logo for use with light headers.

3. **Default Header Logo**
   - **Description:** Set the default logo for the standard header.
   - **Screenshot (Backend Setting):**

     ![Default Logo Theme Options Settings](https://github.com/user-attachments/assets/92461216-fee9-4423-b420-d6a6c796cf8f)

   - **Screenshot (Frontend Preview):**

      ![Screenshot 2024-08-12 182042](https://github.com/user-attachments/assets/c984680c-0406-432e-8001-63586efb5444)

   - **Usage:** Upload the default logo for the header.

4. **Site Logo Width**
   - **Description:** Adjust the logo width for desktop, tablet, and mobile devices.
   - **Screenshot (Backend Setting):** 

     ![Width Logo Theme Options Settings](https://github.com/user-attachments/assets/c5f85dc3-47c7-447e-92cd-5ebc7347c938)
  
   - **Screenshot (Frontend Preview):** 

      ![Screenshot 2024-08-12 190901](https://github.com/user-attachments/assets/780df14f-49ff-41b5-99b9-2ec922096167)

   - **Usage:** Set width values for different devices.

5. **Site Logo Height**
   - **Description:** Adjust the logo height for desktop, tablet, and mobile devices.
   - **Screenshot (Backend Setting):** 

      ![Height Logo Theme Options Settings](https://github.com/user-attachments/assets/cb29120e-3dbe-4608-ab4d-09a5fe312567)

   - **Screenshot (Frontend Preview):** 

      ![Screenshot 2024-08-12 182759](https://github.com/user-attachments/assets/bc3bcea8-e342-4f94-ac8e-061f9b49cf9a)

   - **Usage:** Set height values for different devices.

## Menu > General

### 1. Menu Font Style
- **Description:** Transform the menu text to uppercase, lowercase, or capitalize.
- **Options:**
  - **Uppercase:** Converts all menu text to uppercase letters.
  - **Lowercase:** Converts all menu text to lowercase letters.
  - **Capitalize:** Capitalizes the first letter of each menu item.
- **Screenshot (Backend Setting):** 
   
   ![Menu Font Style Theme Settings](https://github.com/user-attachments/assets/127bb6e6-74fd-4fce-b129-b38e192af223)

- **Screenshot (Frontend Preview):** 

   ![Screenshot 2024-08-12 183312](https://github.com/user-attachments/assets/0da16f24-7e1c-427f-bb60-89aed021eb87)

- **Usage:** Choose the desired text transformation for your menu items.

### 2. Menu Typography
- **Description:** Customize the typography settings for the navigation menu.
  - **Font Size:** Adjust the font size of the menu text.
  - **Font Weight:** Set the font weight for the menu text.
  - **Font Color:** Change the color of the menu text.
- **Screenshot (Backend Setting):**

   ![Menu Font TypographyTheme Settings](https://github.com/user-attachments/assets/f4f7a1de-5f15-49d6-914b-1ce23d285dcf)

- **Screenshot (Frontend Preview):** 

   ![Screenshot 2024-08-13 113603](https://github.com/user-attachments/assets/d86497dc-4721-483e-8843-0d03d6a3af2c)

- **Usage:** Configure these settings to match your site's design preferences.

> [!IMPORTANT]
> If the above settings don't apply, try using [Ostnica Page Options](https://github.com/codeholicritin/GitCommands/blob/main/tutorial-documention.md#ostnica-page-settings--). Click on _Edit Page > Ostnica Page Options_, select the desired settings for that page, and then update it to see the changes.

## Header > General

### 1. Header Type
- **Description:** The Ostnica theme allows you to choose from various header styles to suit your site’s design.
  - **Light Header:** Features a light background, ideal for dark text, enhancing readability.
  - **Dark Header:** Offers a dark background, which works well with light text for a modern look.
  - **Default Header:** Uses the theme’s standard header style, providing a balanced design without customization.
- **Screenshot (Backend Setting):** 

   ![Header Type Theme Settings](https://github.com/user-attachments/assets/fceb34cb-ad12-457f-9b95-a9999becdca9)

- **Screenshot (Frontend Preview):** 
   
   ![Screenshot 2024-08-13 121735](https://github.com/user-attachments/assets/796c8db0-e073-441b-86c1-cae5d6ba0c9b)

- **Usage:** Select the header type that best fits your site’s design.

### 2. Sticky Header
- **Description:** Enable or disable the sticky header feature, which keeps the header fixed at the top of the page as you scroll.
- **Screenshot (Backend Setting):** 

   ![Sticky Header Theme Settings (1)](https://github.com/user-attachments/assets/7c30aade-1267-46a3-ad74-ae93e3bb2759)

- **Screenshot (Frontend Preview):**
  
   https://github.com/user-attachments/assets/dd596acb-973c-4a14-bfcb-53e84ab1ace3

- **Usage:** Toggle the switch to enable or disable the sticky header.

### 3. Transparent Header
- **Description:** Enable or disable the transparency of the header.
- **Screenshot (Backend Setting):** 

   ![_Theme Settings](https://github.com/user-attachments/assets/4f9c0543-9cf3-4f1f-90f5-10bfc81ae217)

- **Screenshot (Frontend Preview):** 

     https://github.com/user-attachments/assets/ff180d37-f4fa-49f7-bdf6-a39c4f623237

- **Usage:** Toggle the switch to enable or disable header transparency.

### 4. Header Layout
- **Description:** Ostnica Theme Options offer a range of header layouts to enhance your website’s design.
  - **Hamburger Menu Right:** The hamburger menu icon is positioned on the right.
  - **Hamburger Menu Full Width:** The hamburger menu icon spans the full width of the header.
  - **Hamburger Menu Left:** The hamburger menu icon is positioned on the left.
  - **Simple Menu:** A basic menu layout without additional features.
  - **Center Menu Center Logo:** The menu and logo are centered within the header.
  - **Center Logo Left Menu Right Menu:** The logo is centered, with the menu items on the left and right.
  - **Center Menu Blur Background:** The menu is centered with a blurred background effect.
- **Screenshot (Backend Setting):** 

   ![Header Layout Theme Settings](https://github.com/user-attachments/assets/33a729f9-06a5-44b0-aa45-adb5f1b9bbc1)

- **Screenshot (Frontend Preview):** 

   ![Screenshot 2024-08-14 171506](https://github.com/user-attachments/assets/1aadb8aa-e13c-47fe-9f82-4a62e59c4deb)

- **Usage:** Choose the layout that best fits your website's design.

### 5. Header Background
- **Description:** Change the background color of the header.
- **Screenshot (Backend Setting):** 

   ![Header Backhground Theme Settings](https://github.com/user-attachments/assets/30f5e1a5-a3f8-4e73-a4c3-4ee8a8eb8c93)

- **Screenshot (Frontend Preview):** 

   ![Screenshot 2024-08-14 172101](https://github.com/user-attachments/assets/2d514275-db97-4b7b-8ae3-c3b99d500537)

- **Usage:** Select a color to set as the header background.

### 6. Header Height
- **Description:** Set the height of the header for different devices.
  - **Desktop:** Height of the header on desktop screens.
  - **Tablet:** Height of the header on tablet screens.
  - **Mobile:** Height of the header on mobile screens.
- **Screenshot (Backend Setting):**

   ![Header Backhground Theme Settings (1)](https://github.com/user-attachments/assets/c926fcb1-2540-4d07-950d-186de16e01cc)

- **Screenshot (Frontend Preview):** 

   ![Screenshot 2024-08-14 170544](https://github.com/user-attachments/assets/2ea634a2-5d8d-4715-ba68-416f1357c534)

- **Usage:** Enter height values for desktop, tablet, and mobile devices to adjust the header’s size.

## Page > General

### 1. Sidebar
- **Description:** Enable or disable the sidebar on the post page, allowing you to display widgets or posts. Posts are displayed only when you select them from the "Select Page" options.
- **Sidebar Widgets:** To display widgets in the left sidebar, navigate to _Appearance > Widgets > Left Sidebar_ and add content. For the right sidebar, navigate to _Appearance > Widgets > Right Sidebar_ and add your content.
- **Screenshot (Backend Setting):**

   ![Left Side Bar Enable In Page](https://github.com/user-attachments/assets/b808402e-abf7-40ad-9029-cf25647b7f00)
  
- **Screenshot (Frontend Preview):**
  
   ![Front End Preview Left Sidebar](https://github.com/user-attachments/assets/bafcab4f-c4b1-42a2-9268-8cd93888405e)

- **Usage:** Toggle the switch to enable or disable the sidebar on the post page.

### 2. Select Sidebar Position
- **Description:** Choose the position where the sidebar will appear on the page. The available options include:
  - **Left Sidebar:** Displays the sidebar on the left side of the page.
  - **Right Sidebar:** Displays the sidebar on the right side of the page.
  - **Both Sidebars:** Displays sidebars on both the left and right sides of the page.
- **Screenshot (Backend Setting):**

   ![Right Sidebar Backend Setting](https://github.com/user-attachments/assets/f7787999-b6c2-4909-a34f-bb43c0a1cf40)
  
- **Screenshot (Frontend Preview):** 

   ![Front End Preview Right Sidebar](https://github.com/user-attachments/assets/5495e728-3b57-4880-98d0-aec5bae672a2)

- **Usage:** Select the desired sidebar position to apply it to your pages.

### 3. Select Page
- **Description:** Provides a list of posts that you can choose to display in the sidebar. This feature allows you to curate specific content that appears alongside your main content.
- **Screenshot (Backend Setting):**

   ![Page List](https://github.com/user-attachments/assets/1854792c-9604-4f06-8938-50fa96d1b25d)

- **Screenshot (Frontend Preview):**

  ![Front End Preview Left Sidebar](https://github.com/user-attachments/assets/5892f1f9-84cf-4417-b11d-4745f1cf50fa)

- **Usage:** Select the posts from the provided list to display them in the sidebar.
  
### 4. Portfolio Page Layout
- **Description:** Choose the design layout for your portfolio page.
- **Options:**
  - **Layout 1:**

    ![post_and_portfolio_l1](https://github.com/user-attachments/assets/8a7f05fd-0395-49f3-8f20-b5afc1d6e620)

  - **Layout 2:**

    ![post_and_portfolio_l2](https://github.com/user-attachments/assets/8e24a439-1eba-496b-b6cc-2933baab8a67)
      
- **Usage:** Choose the layout that aligns with your portfolio’s aesthetic. 
- **Screenshot (Backend Setting):**

   ![Portfolio Layout Selection Backend](https://github.com/user-attachments/assets/fdbfcaee-300c-4c68-a236-61b95bef1bd1)

- **Screenshot (Frontend Preview):**

  ![Portfolio Layout Preview Frontend](https://github.com/user-attachments/assets/eb74bacb-00cd-4804-9a5c-1edfd13a47a0)

> [!Note]  
> To preview changes, navigate to your website's portfolio URL, e.g., _http://localhost/Ostnica_demo/portfolios/_.
> 
> If you encounter a "Page Not Found" error, go to `Settings > Permalinks`, click the **Save Changes** button, and try accessing the URL again. Ensure you entered the correct URL format: _base-url/portfolios_.

### 5. Portfolio List Page Settings
- **Description:** Configure settings for the portfolio list page to customize its appearance and functionality.

- **Select Settings for Portfolio List Page:**
  - **Post Order:**  
    - **Description:** Determine the order in which posts appear on the portfolio list page, either in ascending or descending order.
    - **Usage:** Select your preferred post order to control the sequence of portfolio items displayed.
  
  - **Post Per Page:**  
    - **Description:** Set the number of posts displayed per page on the portfolio list page.
    - **Usage:** Choose the desired number of posts to show on each page of the portfolio list.

  - **Layout Options:**
     - **Layout 1:**
         - **Description:** This layout displays portfolio items in a grid format, offering a clean and structured appearance. When hovering over any portfolio image, an overlay text with the project title appears from                the bottom of the image, creating an interactive visual effect. This layout is perfect for showcasing projects with minimalistic yet engaging hover effects.
           
              ![portfolio_l3](https://github.com/user-attachments/assets/191f04b9-65eb-4858-bc12-e0fc00daaa69)
    
     - **Layout 2:**  
         - **Description:** This layout presents portfolio items in a list format, where each portfolio entry is displayed with the image on the left side and the corresponding portfolio description on the right. It                    provides a clear and detailed view of each project, making it ideal for portfolios that require more descriptive content alongside visual representation.
        
             ![portfolio_l1](https://github.com/user-attachments/assets/88b520fc-cfbc-44bb-87c9-5bce8d1bc297)

     - **Layout 3:**  
         - **Description:** This layout displays portfolio items in a grid format, similar to a card layout. Each portfolio entry showcases the image, with the portfolio description positioned directly below it. It                    offers a clean, modern, and visually balanced presentation, ideal for portfolios with a strong emphasis on visual content and concise descriptions.
        
             ![portfolio_l2](https://github.com/user-attachments/assets/07824e0c-dab0-472e-923d-5762a79be2ae)

### 6. Post Page Layout
- **Description:** Choose the design layout for individual post pages.
- **Options:** 
  - **Layout 1**

    ![post_and_portfolio_l1](https://github.com/user-attachments/assets/8a9f52bb-0710-4a66-b563-cda9bc9af70a)

  - **Layout 2**

    ![post_and_portfolio_l2 (1)](https://github.com/user-attachments/assets/34b827d7-f409-4d00-a777-677936d07b1f)

- **Usage:** Select the layout that best fits your design preferences for individual posts.
- **Screenshot (Backend Setting):**
  
     ![Portfolio Post Description Layout](https://github.com/user-attachments/assets/8c0b0287-5878-45e4-96d5-16516ccf2896)

- **Screenshot (Frontend Preview):**

     ![Screenshot 2024-09-19 192426](https://github.com/user-attachments/assets/8e176b0c-64b1-441e-bc52-82f069d28605)

### 7. Portfolio List Page Settings
- **Description:** Configure settings for the portfolio list page to control post display.
- **Screenshot (Backend Setting):**
  
     ![Post List Page Settings](https://github.com/user-attachments/assets/ae7a68ce-525e-4a40-b420-67670a3f07c9)

- **Screenshot (Frontend Preview):**
  
     ![Screenshot 2024-09-20 162022](https://github.com/user-attachments/assets/f2724215-f489-41c4-822f-1b6cd827c647)

- **Layout Options:**
   - **Layout 1:**
     
        ![post_l1](https://github.com/user-attachments/assets/675af835-3d02-4c7b-b331-ed215a685cce)

   - **Layout 2:**
  
       ![post_l2](https://github.com/user-attachments/assets/a91024a6-3250-4c6d-bbe3-0406cc81481c)

  - **Layout 3:**

       ![post_l3](https://github.com/user-attachments/assets/f1ac1d86-ab3c-4a32-9515-b2114b1d6fec)


- **Post Order:** 
  - **Description:** Arrange posts in ascending or descending order.
  - **Options:**
    - **Ascending:** Posts will be displayed from oldest to newest.
    - **Descending:** Posts will be displayed from newest to oldest.
  - **Screenshot (Backend Setting):**
    
     ![Post List Page Post Order Backend](https://github.com/user-attachments/assets/07499e4b-4690-4a05-a46a-f78927184d5c)

- **Posts Per Page:** 
  - **Description:** Set the number of posts to display per page in the portfolio list.
  - **Usage:** Enter the desired number to limit the posts shown on each page.
  - **Screenshot (Backend Setting):**
  
      ![Screenshot 2024-09-20 163305](https://github.com/user-attachments/assets/6d325307-37f3-4d43-884b-c07749780b80)

- **Screenshot (Frontend Preview):**
  
     ![Screenshot 2024-09-20 164405](https://github.com/user-attachments/assets/1c6b96d7-6f4a-4ef3-9b69-fb6f13f7b1ac)


## Footer > Footer Settings

### Footer Layout
- **Description:** Customize your footer's design with various layout options.
- **Customization:** Create your footer layout from _Appearance > Widgets > Footer [Area Name]_.
- **Usage:** Save changes to apply the updated footer design to your site.
- **Screenshot (Backend Setting):**

  ![Footer Layout Theme Settings](https://github.com/user-attachments/assets/347715a5-86b2-46f7-8d58-8873a273a688)

- **Screenshot (Frontend Preview):**
  
   ![image](https://github.com/user-attachments/assets/aa2c03c7-d092-4734-9446-5dfb811472d1)

### Box Layout
- **Description:** Enable or disable a boxed layout for the footer.
- **Usage:** Toggle this setting to apply a boxed or full-width footer layout.
- **Screenshot (Backend Setting):** 
   ![Footer Box Layout Theme Settings](https://github.com/user-attachments/assets/852d559e-c100-4be6-9293-f0f1efa4f09a)

- **Screenshot (Frontend Preview):** 
   
   ![image](https://github.com/user-attachments/assets/2b4028af-0e5b-4b60-9c64-5f2ae7a2632c)

### Sticky Footer
- **Description:** Make the footer sticky, so it stays fixed at the bottom of the page while scrolling.
- **Usage:** Toggle this setting to enable or disable the sticky footer.
- **Screenshot (Backend Setting):**
  
   ![Footer Box Layout Theme Settings (1)](https://github.com/user-attachments/assets/8afa5958-2ac9-41aa-b881-34c8c2c74501)

- **Screenshot (Frontend Preview):** 

   https://github.com/user-attachments/assets/d6b4df2c-98f5-4b84-a14a-a836acd83386

### Footer Background Color
- **Description:** Set the background color for the footer.
- **Usage:** Choose a color that complements your site's design.
- **Screenshot (Backend Setting):**

   ![Footer Background Color](https://github.com/user-attachments/assets/889214b5-0391-4571-a118-351c545c7791)
  
- **Screenshot (Frontend Preview):**

   ![Screenshot 2024-09-19 160357](https://github.com/user-attachments/assets/dd826e8e-01fe-4a66-aebe-dea01e1c457f)

### Footer Font Color
- **Description:** Set the font color for the footer text.
- **Usage:** Select a color for optimal readability.
- **Screenshot (Backend Setting):**

   ![Footer Font Color](https://github.com/user-attachments/assets/7c8c2227-6c35-4752-9beb-0ddf9b895bc0)
  
- **Screenshot (Frontend Preview):**

  ![Footer Font Color Frontend](https://github.com/user-attachments/assets/2aa18db6-f7c7-48ce-9721-21c48475c701)

### Copyright Bar Content
- **Description:** Add content to the copyright bar, such as company details or legal information.
- **Usage:** Enter your content to display it at the bottom of the footer.
- **Screenshot (Backend Setting):**
  
  ![Screenshot 2024-09-19 154159](https://github.com/user-attachments/assets/9747e206-3663-4f76-8494-f02599a17a7e)
  
- **Screenshot (Frontend Preview):**

  ![Screenshot 2024-09-19 161050](https://github.com/user-attachments/assets/fb6eb94e-28c1-4872-8486-b7e9e9b5349b)

### Copyright Bar Typography
- **Description:** Customize the typography for the copyright content in the footer.
- **Options:**
  - **Font Size:** Set the font size for copyright text.
  - **Font Weight:** Adjust the font weight of copyright text.
  - **Font Color:** Change the font color for copyright text.
  - **Font Family:** Select the font family for copyright text.
- **Usage:** Adjust these settings to style the copyright content to match your site's design.
- **Screenshot (Backend Setting):**

  ![Footer Copyright typography](https://github.com/user-attachments/assets/538d93d9-59eb-41db-a423-5516ade94650)

- **Screenshot (Frontend Preview):**

   ![Screenshot 2024-09-19 161050](https://github.com/user-attachments/assets/e953dd1c-dc2b-41d0-b158-07537f840586)

## Reset > Reset All Settings

### Reset All Settings
- **Description:** As the name suggests, this option resets the theme settings to their default state. When selected, all applied theme settings will be removed, and the theme will revert to its original configuration.
- **Screenshot (Backend Setting):** 

   ![Header Backhground Theme Settings](https://github.com/user-attachments/assets/6c0846ad-2411-4f9c-9b93-02198c2d8327)

- **Usage:** Use this option if you want to restore the theme to its default settings, removing any customizations you've made.

*Note: Attach screenshots from both the admin dashboard showing the theme options and the front end displaying the changes for clarity.*

## Ostnica Page Settings -
Ostnica theme also provides you with **Ostnica Page Setting** options to fully customize your page design and layout. It includes a variety of options that allow you to control the appearance and functionality of your pages, offering flexibility and ease of use for creating unique page layouts that fit your style.

## Backend Settings Screenshot:

   ![Edit Single Page Ostnica Settings](https://github.com/user-attachments/assets/640bec3b-79d3-4dfb-ae8a-f202ec44fd7b)
   
   ![Ostnica Page Settings Backend Customization](https://github.com/user-attachments/assets/66ee6c4a-457e-456a-8bcd-14df806d902d)

## Frontend Preview Screenshot:
   - **Before Applying Ostnica Page Setting :**
     
        ![Screenshot 2024-09-20 164746](https://github.com/user-attachments/assets/7db96eb1-e047-46df-a3f5-206ff65b1a3d)
     
   - **After Applying Ostnica Page Setting :** 

        ![Screenshot 2024-09-20 171258](https://github.com/user-attachments/assets/d8e511b4-d47b-468e-9c1a-5333e80b134b)
