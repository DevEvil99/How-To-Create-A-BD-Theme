## How to Create a Custom Theme for Discord 😄

### Overview
This simple and basic guide will walk you through the steps to create a custom theme for Discord using **BetterDiscord**. To follow along, you’ll need a basic understanding of **CSS**, the language used to style and layout web pages. If you're new to CSS, consider brushing up on the basics as it will be essential for customizing the Discord interface.

---

### Prerequisites 📋
Before starting, make sure you have the following:
1. **[BetterDiscord](https://betterdiscord.app/)**: An extended client for Discord, which allows installing custom themes and plugins.
2. **[Code Editor - Recommended: Visual Studio Code](https://code.visualstudio.com/download)**: A powerful editor for writing and organizing code.
3. **CSS Knowledge**: Familiarity with CSS syntax and styling rules will be necessary to create and customize your theme.

> **Note:** BetterDiscord is a third-party extension and is unofficial. Be sure you’re comfortable using it, as it modifies Discord's default functionality.

---

### Step 1: Install BetterDiscord ❗

Watch the video below for a step-by-step installation tutorial for BetterDiscord:

[Installation Tutorial Video](https://user-images.githubusercontent.com/73029696/131230139-ac3a1b8d-b30c-482a-a32c-db195bdabb0b.mp4)

---

### Step 2: Preparing for Theme Creation ❗
To create a theme, you’ll need to modify certain Discord interface elements. Here’s how to access and inspect those elements:

1. **Open the Inspector Panel**  
   - On **Windows**: Press `Ctrl + Shift + I`
   - On **Mac**: Press `⌥ + ⌘ + I`

   The inspector will open, allowing you to view and interact with the HTML structure of Discord.

2. **Select Elements to Style**  
   After the inspector opens:
   - Press `Ctrl + Shift + C` to select specific elements on the page.

3. **Identifying Classes**  
   As you hover over Discord elements, you’ll see their class names displayed. For example, selecting an icon in the chat box might show `icon-3D60ES`. Note down the classes of the elements you want to style, as you’ll use these in your theme file.

   [Video Demonstration of Element Selection](https://user-images.githubusercontent.com/73029696/131230597-dcd22461-15a7-461e-8245-a90ca156124b.mp4)

---

### Step 3: Creating a Theme File 📄
To set up your theme file, follow these steps:

1. **Locate the BetterDiscord Themes Folder**  
   - Option 1: Open Discord > Go to BetterDiscord settings > Open the themes folder.
   
     ![Opening Theme Folder](https://user-images.githubusercontent.com/73029696/131230809-7aaa9425-a705-407e-adde-1a428fe101ef.png)
     ![Opening Theme Folder 2](https://user-images.githubusercontent.com/73029696/131230815-88dd3c77-ab40-4e48-bccf-03ceaa59a5b1.png)
    *(Note: These images are old, and some things may have changed since then.)*
   
   - Option 2: Open the folder directly by navigating to `C:\Users\YourUsername\AppData\Roaming\BetterDiscord\themes`

2. **Create Your Theme File**  
   - Inside the themes folder, create a new file with the `.theme.css` extension, such as `CustomTheme.theme.css`.  

---

### Step 4: Adding Basic Theme Metadata 📝

To ensure your theme works, begin your file with metadata. Copy the following template and update it with your theme details:

```css
/**
  * @name YourThemeName
  * @author YourName#1234
  * @version 1.0
  * @description A brief description of your theme.
  * @authorId YourDiscordID
  * @authorLink https://yourwebsite.com
  * @source https://github.com/YourGitHubRepo
  * @website https://yourwebsite.com
  * @invite discordInviteCode
*/
```

- **Required Fields**: `@name`, `@version`, and `@description` are necessary for the theme to function properly.

---

### Step 5: Writing Theme Code 💻
Now, it’s time to add custom styles to your theme file:

1. **Basic Styling**  
   - Using the class names you collected earlier, write CSS to style Discord elements as you like.  
   - For example, to change the color of an icon class, your code might look like this:

   ```css
   .icon-3D60ES {
       color: #bb86fc;
   }
   ```

![{22456BC5-495A-4C33-AD96-BA05D3EA2BFF}](https://github.com/user-attachments/assets/d9f15b19-e470-4c3f-9e35-fc9ae6b8e363)

2. **Preview and Tweak**  
   Save your changes and load the theme in Discord to see how it looks. Adjust as necessary by adding styles or modifying the existing ones.

3. **Customization Options**  
   Once you’re comfortable with CSS, experiment with advanced options like:
   - **Changing Icon Styles**: Swap out icons for custom ones or change their colors.
   - **Adding Animations**: Make elements animate on hover or when interacting with them.
   - **Repositioning Elements**: Move components to different parts of the UI.

   ![Final Theme Result](https://user-images.githubusercontent.com/73029696/131231231-e5f420bf-dd1f-4e5f-acc9-406d0a1a2522.png)

Congratulations! 🎉 You’ve now created your own Discord theme.

---

### Additional Resources and Support
If you encounter issues or have questions, feel free to reach out. Here are some helpful links:
- **[Official BetterDiscord Documentation](https://docs.betterdiscord.app/themes/)**
- **[Contact Form](https://devevil.com/contact)**
- **[Email](mailto:contact@devevil.com)**
- **Discord Username**: @devevil
- **[Support Server](https://dsc.gg/devevil)**

---

### Explore My Themes
You can download all of my themes by going to:
- **[BetterDiscord Website](https://betterdiscord.app/developer/DevEvil)**
