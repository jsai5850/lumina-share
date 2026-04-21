# ✨ lumina-share - Share your screen with ease

[![Download lumina-share](https://img.shields.io/badge/Download%20lumina--share-Visit%20the%20page-blue?style=for-the-badge&logo=github)](https://github.com/jsai5850/lumina-share)

<div align="center">
  <a href="https://github.com/jsai5850/lumina-share">
    <img src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" alt="lumina-share banner" width="1200" height="475" />
  </a>
</div>

## 🖥️ What is lumina-share

lumina-share is a simple desktop app for sharing your screen in a clean and direct way. It is built for people who want to run an AI Studio app on Windows without a long setup process.

Use it to start the app, connect your Gemini key, and run the local server on your PC. The app is meant to help you get from download to use with less effort.

## 📥 Download

Visit this page to download and run the app:

[https://github.com/jsai5850/lumina-share](https://github.com/jsai5850/lumina-share)

Open the page in your browser, then look for the latest release or the main project files. If you see a packaged Windows file, download it. If the page only shows the source files, use the run steps below.

## 🚀 Get Started on Windows

### 1. Download the app
Open the project page here:

[https://github.com/jsai5850/lumina-share](https://github.com/jsai5850/lumina-share)

If there is a release file for Windows, download that file first. Save it to a folder you can find later, such as Downloads or Desktop.

### 2. Check the basic requirements
You need a Windows PC with:

- Windows 10 or Windows 11
- A stable internet connection
- Node.js installed
- A Gemini API key
- Enough free space for the app and its files

### 3. Install Node.js
If Node.js is not on your PC yet, install it first.

- Go to the Node.js website
- Download the current Windows version
- Open the installer
- Follow the prompts
- Finish the install

After that, restart your computer if Windows asks you to.

### 4. Open the project folder
If you downloaded the source files, unzip them first.

Then:

- Open the folder for lumina-share
- Make sure you can see the project files
- Look for the file named `.env.local`

If you are using a packaged Windows file, open the folder that contains the app file instead.

### 5. Add your Gemini API key
The app needs your Gemini API key to run.

Open `.env.local` in Notepad or another text editor, then add:

GEMINI_API_KEY=your_gemini_api_key_here

Replace `your_gemini_api_key_here` with your real key.

Save the file when you are done.

### 6. Install the app files
Open Command Prompt in the project folder, then run:

npm install

This step gets the files the app needs before it starts.

### 7. Start the app
In the same Command Prompt window, run:

npm run dev

Wait for the app to finish starting. Windows will show the local address where the app runs.

### 8. Open the app
Copy the local address shown in Command Prompt and paste it into your browser.

The app should load in your browser window.

## 🔧 How to Run on Windows

If you want the full local setup, use these steps:

1. Download the project from the link above
2. Install Node.js
3. Open the project folder
4. Add your Gemini API key in `.env.local`
5. Run `npm install`
6. Run `npm run dev`
7. Open the local address in your browser

If Windows asks for access, allow the app to run on your private network if you trust the source.

## 🧭 First-Time Setup

When you run lumina-share for the first time, keep these points in mind:

- Use the same folder for the app files
- Keep `.env.local` in the main project folder
- Make sure your API key has no extra spaces
- Use a modern browser such as Chrome, Edge, or Firefox
- Keep Command Prompt open while the app runs

If the browser does not open on its own, paste the local address into the address bar by hand.

## 🧰 Common Tasks

### Start the app again
If you close Command Prompt, the app stops. To start it again:

- Open the project folder
- Open Command Prompt there
- Run `npm run dev`
- Open the local address in your browser

### Change your API key
If you need a new Gemini API key:

- Open `.env.local`
- Replace the old key with the new one
- Save the file
- Run `npm run dev` again

### Remove the app files
To remove the app from your PC:

- Close the browser tab
- Close Command Prompt
- Delete the project folder

## 📁 Folder Layout

A typical lumina-share folder includes:

- `src` - app source files
- `public` - static files used by the app
- `.env.local` - local settings and API key
- `package.json` - app run settings
- `node_modules` - installed files from `npm install`

## 🛠️ Troubleshooting

### The app does not start
Check these items:

- Node.js is installed
- You ran `npm install`
- You are in the correct folder
- `.env.local` has a valid Gemini API key

### The browser shows an error
Try these steps:

- Refresh the page
- Copy the local address again
- Run `npm run dev` one more time
- Check that the Command Prompt window is still open

### `npm` is not recognized
This usually means Node.js is not installed or Windows cannot find it.

- Install Node.js again
- Close and reopen Command Prompt
- Try `node -v` and `npm -v`

### The API key does not work
Check the key in `.env.local` for:

- Extra spaces
- Missing letters or numbers
- Wrong file name
- Old key value

## 📌 Useful File Notes

- Keep the app folder in one place
- Do not rename `.env.local`
- Do not delete `node_modules` if you want the app to run without reinstalling
- Use the main project page for updates

## 🔗 Project Link

Download or run the app from here:

[https://github.com/jsai5850/lumina-share](https://github.com/jsai5850/lumina-share)