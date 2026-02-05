# How to Run Al Zahraa Application

Because this project uses modern JavaScript (ES6 Modules), you cannot simply double-click `index.html` to open it. Browsers block module loading for local files for security reasons.

## Option 1: VS Code Live Server (Recommended)
If you are using Visual Studio Code:
1.  Go to the **Extensions** view (click the square icon on the left sidebar or press `Ctrl+Shift+X`).
2.  Search for **"Live Server"** (by Ritwick Dey).
3.  Click **Install**.
4.  Once installed, open `index.html` in the editor.
5.  Right-click anywhere in the code and select **"Open with Live Server"**.
6.  The app will open automatically in your browser.

## Option 2: Web Server for Chrome
If you use Google Chrome:
1.  Install the [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb) extension.
2.  Launch the app.
3.  Click **"Choose Folder"** and select the `al zahraa` folder.
4.  Click the Web Server URL (usually `http://127.0.0.1:8887`).

## Why is this necessary?
The application is built with modular JavaScript files (`import`/`export`) to keep the code clean and organized. This requires a web server to function correctly.
