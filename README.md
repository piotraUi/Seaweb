Seaweb is a modern, secure, and fast web browser built on the Electron platform, designed with user privacy and convenience in mind.

This project combines standard browser functionalities with advanced features like profile management and comprehensive parental controls, offering a complete and safe environment for browsing the web.

Key Features
🚀 Fast Browsing: Built on the Chromium engine, Seaweb ensures high performance and compatibility with modern web standards.
🛡️ Built-in Ad-Blocker: Automatically blocks ads and tracking scripts to protect your privacy and speed up page loading.
👨‍👩‍👧 Advanced Parental Controls:
Create dedicated profiles for children.
Secure access to key features (Incognito mode, developer tools, extension installation) with a security question.
👥 Profile System: Create separate profiles for different users, each with its own history, bookmarks, and settings.
🌐 Extension Support: Easily manage extensions through a dedicated manager window.
🔖 Standard Features: Full support for tabs, bookmarks, browsing history, and incognito mode.
✨ Clean Interface: A minimalist and intuitive user interface that is easy to navigate.
Tech Stack
Framework: Electron
Languages: JavaScript, HTML5, CSS3
Key Libraries:
@cliqz/adblocker-electron - for ad blocking
@electron/remote - for inter-process communication
electron-builder - for creating installation packages
Installation and Setup
To run the project locally, follow these steps:

Clone the repository:
bash
git clone https://github.com/your-username/Seaweb.git
cd Seaweb
Install dependencies:
bash
npm install
Run the application in development mode:
bash
npm start
Building the Application
To create an executable file (.exe for Windows), use the following command:

bash
npm run dist
The built application will be located in the newly created dist folder.

License
This project is licensed under the MIT License
