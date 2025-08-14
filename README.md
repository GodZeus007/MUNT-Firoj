> This extension is no longer maintained by its original creator, XengShi
> You can create a backup from the old extension’s settings and restore it into this new version.

<!-- Initialized : Sun 20 Aug 2023 03:41:08 PM IST -->
<h1 align="center">

<a href="https://godzeus007.github.io/MUNT-Firoj/"><img src="https://github.com/user-attachments/assets/48c3a9cb-06fa-4c45-92ec-194cdb7c5661" width="58"></a>
<br>
MUNT: Material UI New Tab

</h1>
<div align="center">

MUNT: Material UI New Tab is a versatile browser extension that personalizes your New Tab page with customizable themes, a welcoming message, and various handy tools, all while integrating seamlessly with your preferred search engine.

</div>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-installation-guide">Installation Guide</a> •
  <a href="#download">Download</a> •
  <a href="#-currently-supported-languages-29">Currently Supported Languages</a>
<br>
  <a href="#-contributing">Contributing</a> •
  <a href="#-star-history">Star History</a> •
  <a href="#-issues-and-support">Issues and Support</a> •
  <a href="#-privacy-policy">Privacy Policy</a> •
  <a href="#-license">License</a>
</p>

<img src="https://i.postimg.cc/CF43Yzj1/material-you-new-Tab-poster.webp" alt="Screenshot 1" width="100%">

#### 🔴 🟡 🟢 Test live: [https://godzeus007.github.io/MUNT-Firoj/](https://godzeus007.github.io/MUNT-Firoj/)

## ✨ Features

- **Integrated Search**: Search directly from the New Tab using your preferred search engine — Google, DuckDuckGo, Bing, Brave Search, YouTube, Wikipedia, and more, with integrated voice typing.
- **Customizable Themes**: Choose from a selection of themes or use the built-in color picker to match your style.
- **Wallpaper**: Upload your own wallpapers or enable daily random images sourced from [Lorem Picsum](https://picsum.photos).
- **Personalized Greeting**: Add a custom message or your name, so you're greeted each time you open a new tab.
- **Clock & Time Display**: Choose between a modern analog or digital clock.
- **Live Weather Updates**: View real-time temperature, conditions, humidity, feels like, and max-min temperature values. Supports °C and °F with location customization.
- **Quick Shortcuts**: Access common platforms (YouTube, Email, WhatsApp, etc.) or add your own shortcuts for instant navigation.
- **AI Tools**: Open ChatGPT, Gemini, Copilot, Perplexity, Claude, DeepSeek, and more with one click.
- **To-Do List**: Manage daily tasks, pin important ones, and enjoy automatic cleanup at the start of each day (pinned tasks reset to pending).
- **Sidebar Bookmarks**: View, delete, and organize bookmarks in either list or grid layout.
- **Google Apps**: Quickly launch Gmail, Drive, Docs, and other Google services.
- **Backup & Reset**: Save or restore your setup anytime, or reset everything to default with one click.
- **Language Support**: Use the extension in your preferred language for better accessibility.
- **Browser Compatibility**: Supports all Chromium-based browsers, including **Chrome**, **Edge**, **Brave**, and **Opera**, as well as Firefox-based browsers like **Firefox** and **Zen**.

## 📥 Installation Guide

### Download



    -Download the latest version as a ZIP file by clicking below:


    - You can also download the ZIP file by clicking on the Code button. On the repository page, look for a green button labeled **Code**. Click on the **Code** button, and in the dropdown menu, select **Download ZIP**.
---

### Installation

#### ![Chromium](https://img.icons8.com/?size=20&id=104996&format=png&color=000000) Chromium-Based Browsers


1. **Manual Installation**:

   - **Prepare the Extension Folder**:

     - Ensure you’ve cloned the repository or downloaded the ZIP file and extracted it.

   - **Open Extensions Page**:
     Open your preferred browser and enter the following text in the address bar:

     - ![Chrome](https://img.icons8.com/color/20/000000/chrome--v1.png) Chrome: `chrome://extensions`

     - ![Edge](https://img.icons8.com/?size=20&id=dGm9KIZPpukc&format=png&color=000000) Edge: `edge://extensions`

     - ![Brave](https://img.icons8.com/color/20/000000/brave-web-browser.png) Brave: `brave://extensions`

     - ![Opera](https://img.icons8.com/color/20/000000/opera--v1.png) Opera: `opera://extensions`

   - **Enable Developer Mode**:

     - Turn on **Developer Mode** in the extensions page.

   - **Load Unpacked Extension**:
     - Click on **Load unpacked** and select your extracted extension folder.

3. **Additional Steps ONLY for <img height="16" src="https://cdn.simpleicons.org/opera"/> Opera (or <img height="16" src="https://cdn.simpleicons.org/operagx"/> Opera GX)**:

> [!NOTE]
> Opera does **not support replacing the default New Tab**.  
> This method only sets the extension as a **startup page**.

<details><summary>Click here for the workaround</summary>

- Go to the **Settings**.
- Scroll to the **On startup** section (use the search option if needed).
- Click on **Open a specific page or set of pages** and then click on **Add a new page**.
- Add the following (replace 32-character extension ID if installed manually) to the **Site URL**:

```text
chrome-extension://jjpokbgpiljgndebfoljdeihhkpcpfgl/index.html
```

- To find the extension ID:

  - Go to `opera://extensions`, find the extension, and copy the 32-character ID from its details.

- To simulate new tabs:

  - Bookmark the extension page to access new tab pages manually.

  - Or, right-click the tab and select **Duplicate tab**.

</details>

Below are screenshots of the process to guide you through each step visually.

<img src="https://i.postimg.cc/w6JYypvc/chrome.png" alt="Screenshot 1" width="569">
<img src="https://i.postimg.cc/0ksR7BKg/edge.png" alt="Screenshot 2" width="569">
<img src="https://i.postimg.cc/MqPSg5NR/brave.png" alt="Screenshot 3" width="569">

---

#### ![Firefox](https://img.icons8.com/color/20/000000/firefox--v1.png) Firefox

1. **Install from Mozilla Extensions Store**:

   - [Mozilla Add-ons link](https://addons.mozilla.org/en-US/firefox/addon/mynt/)

<img src="https://i.postimg.cc/bPW2fHX7/FireFox.png" alt="Screenshot" width="569">

2. **Update the Homepage**:

   - Open Firefox and **obtain the UUID**:
      - Hover over the New Tab button (next to the tab close button). A tooltip will display the extension's unique ID, which looks like this: `0f31e1c1-d63c-4660-b950-8bfbda3bb20a`. Copy or note this ID.
      - Alternatively, type `about:debugging#/runtime/this-firefox` in the address bar and find the extension's UUID there.
   - Open **Settings** and navigate to **Home**, or type `about:preferences#home` in the address bar.
   - Under the **Homepage and new windows** section, select **Custom URLs...**.
   - Paste the following URL, replacing the ID with your actual UUID:

     ```text
     moz-extension://e31d6701-f699-414f-bb4c-8fde495c432e/index.html
     ```

   - This will update both your homepage and new tab to the extension.
  
3. **Additional Steps ONLY for Zen Browser** <img height="16" src="https://cdn.simpleicons.org/zenbrowser"/> :

   - Open a new tab and go to `about:config`.
   - Accept the risk and continue if prompted.
   - In the search bar, type:

     ```text
     zen.urlbar.replace-newtab
     ```

   - Set its value to **false** by clicking the toggle icon.

   This ensures the browser does not override the custom New Tab page set by the extension.

4. **Manual Installation (Temporary)**:

   - Clone the repository or download and extract the ZIP file.
   - **Prepare the Manifest**:

     - Delete the existing `manifest.json` file.
     - Rename `manifest(firefox).json` to `manifest.json`.

   - **Load Temporary Add-on**:
     - Go to `about:debugging#/runtime/this-firefox`, select **"This Firefox"**, then click **Load Temporary Add-on**.
     - Browse and select the updated `manifest.json`.

---

### Installation Video

For a step-by-step walkthrough, watch this [installation guide video](https://youtu.be/P4ryQPixfw8).

[![Watch the video](https://img.youtube.com/vi/P4ryQPixfw8/0.jpg)](https://youtu.be/P4ryQPixfw8)

## 🤝 Contributing

Contributions are welcome! If you’d like to contribute:

1. Follow the guidelines in the [CONTRIBUTING.md](./CONTRIBUTING.md) file.
2. Fork the repository.
3. Create a new branch: `git checkout -b feature/YourFeature`.
4. Commit your changes: `git commit -m 'Add Your Feature'`.
5. Push to the branch: `git push origin feature/YourFeature`.
6. Open a pull request.

## ⭐ Star History

Here is the star history chart for the **MUNT: Material UI New Tab** repository. It shows the growth of stars over time, reflecting the increasing interest and support for the project.


## ❓ Issues and Support

- If you encounter any issues or bugs, feel free to open an issue on [GitHub](https://godzeus007.github.io/MUNT-Firoj/issues).
- For general questions or support, you can contact the repository maintainers through the **Telegram group**: [Join here](https://t.me/Material_You_NewTab).

## 🛡 Privacy Policy

MUNT: Material UI New Tab prioritizes your privacy and is focused solely on providing a better browsing experience. For more details, read our [Privacy Policy](https://godzeus007.github.io/MUNT-Firoj/privacy-policy.html).

## 📜 License

Copyright (C) 2023-2025 XengShi

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). This means you must **not** distribute this software, whether original or modified, to any platform **without** its source code or the reference to its original source code. See the [LICENSE](https://godzeus007.github.io/MUNT-Firoj/blob/main/LICENSE) file for details.
