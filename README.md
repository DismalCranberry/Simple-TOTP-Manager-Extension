# Simple OTP Manager (Browser Extension)
A lightweight browser extension for generating one-time passwords locally.

## What is this?
Welcome to your very own OTP sidekick! 🕵️‍♂️🔐  
This extension generates 6-digit time-based one-time passwords (OTP) and stores your codes locally, so you can grab a fresh code whenever you need it.

## How It Works
Imagine you have a squad of five little helpers:

**Secret Keeper** 📌 – Safely stashes your Base32 secrets in Chrome storage.  
**Code Maker** ⏱️ – Uses those secrets to generate new codes every 30 seconds.  
**Clipboard Hero** 📋 – Copies a code with a click and shows a tiny “Copied!” message so you know it worked.  
**Organizer** 🗂️ – Lets you rename, delete, and drag to reorder your accounts.  
**Timer** ⏳ – Counts down the seconds and refreshes the codes right on schedule.

Together they let you:

- 📜 Store multiple secrets  
- 🔄 Refresh and display codes automatically  
- 👀 Copy codes to the clipboard  
- 💼 Manage your list with rename, delete, and drag-and-drop  

## File Structure
- **manifest.json** – Chrome extension manifest  
- **popup.html** – Main popup UI  
- **popup.js** – Logic for secrets, code generation, and UI interactions  
- **RandomCat.png** – Cute icon for the extension  

## Getting Started
Load the project directory as an unpacked extension in a Chromium-based browser.  

Enjoy convenient two-factor codes! 🚀
