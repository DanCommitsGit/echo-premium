# Echo Premium - Enhanced Online Echo Classroom Experience

> This project is archived and no longer maintained.

https://github.com/user-attachments/assets/36454eda-e28a-4f8a-9df5-fa777ae0285c

Below is a comparison of how the site looks before and after installing the mod:

### Before & After Comparison

<table>
  <tr>
    <td align="center"><b>Before</b></td>
    <td align="center"><b>After</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/a25bc1fd-8fd0-4408-a03d-d70786215522" width="1000"></td>
    <td><img src="https://github.com/user-attachments/assets/a5056cc2-f7d6-4498-9e09-8c3b9515d235" width="1000"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/52c2edc1-2d36-4db2-9b4e-14aa4f83302e" width="1000"></td>
    <td><img src="https://github.com/user-attachments/assets/a24a7e20-56fc-4621-9a7d-4223b43fbaa3" width="1000"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/22472d1b-2fa2-4f28-907a-0b874871c2c6" width="1000"></td>
    <td><img src="https://github.com/user-attachments/assets/4a7241b6-c389-4723-bd5c-f3d9fa2c0ecb" width="1000"></td>
  </tr>
</table>

---

## 🎨 Premium Settings Page

Explore the new dedicated settings page to toggle the mod and customize your experience:

![premium settings page](https://github.com/user-attachments/assets/d1a37756-f8dc-40c2-89a3-43d66aff4be4)

---

## 🌟 Features

- **Reworked and Improved UI**
- **Modern UI Styling**
- **Custom Logo**
- **Custom Loading Screen**
- **Automatic Updates**
- **New modern and smooth animations**
- **Set a preset background or choose your own custom background**
- **Dedicated Settings Page with easy on/off toggle for the mod**
- **Visual presentation of grades with emoticons for a quick emotional cue (e.g., 😊 for B, 😟 for D)**

---

## 🛠️ How It Works

Echo Premium is a Tampermonkey userscript that runs on Echo pages and changes how they look.

- It injects a stylesheet that restyles Echo's Angular Material interface: rounded cards, a gradient side menu, a custom background and animated glows.
- A Premium Settings link is added to the side menu by cloning an existing link. Opening it replaces the main content area with the settings page.
- The settings page has an "Enable Echo Premium" toggle and a background image URL field, and both are saved in the browser's `localStorage`.
- The Dark Mode toggle in the side menu changes the theme file Echo stores for your account, using the Agilix Buzz API and the session you're already signed in with.
- The first time it runs, the script switches your account to Echo's dark purple theme.
- Every 300 ms it scans the course cards and adds grade emoticons and colored outlines.

The script contacts only the Agilix Buzz API that Echo uses and this repository, which serves the images and updates. The one exception is a custom background URL, which loads from whatever address you enter.

---

## ⚠️ Status

Echo Premium was written in 2023 as a student project and last updated in 2025. It depends on Echo's page structure, so an Echo update can break parts of it.

It is set to run on one school's Echo site. Other Echo sites may only need a different `@match` line at the top of `echo-premium.user.js`, but I haven't tested any.

---

## 🚀 Installation Guide

### 1️⃣ Install Tampermonkey (Required)
1. [Click here](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) to open the Chrome Web Store.
2. Click **"Add to Chrome"**.

   ![image](https://user-images.githubusercontent.com/61391827/222789735-b863c221-cdbd-48e5-b629-090c20f03964.png)

3. Click **"Add Extension"**.

   ![image](https://user-images.githubusercontent.com/61391827/222790193-23953a11-458c-4f01-868d-0c41596123ea.png)

---

### 2️⃣ Install Echo Premium
1. [Click here](https://github.com/DanCommitsGit/echo-premium/raw/main/echo-premium.user.js) to download Echo Premium.
2. Click the **"Install"** button.

   ![image](https://user-images.githubusercontent.com/61391827/222788870-870ae580-6246-443b-8845-890e5e1e67d8.png)

✅ **That's it!**

---

Echo Premium is an unofficial project. It is not affiliated with or endorsed by the makers of Echo or Agilix, and their names and logos belong to their owners.
