# Simple Co-op Application Tracker

This is a minimal deployment guide for the Co-op Application Tracker app. All you need is these files:

1. `index.html` - Contains all the app code, CSS and JavaScript
2. `manifest.json` - Web App Manifest file for PWA functionality
3. `sw.js` - Service Worker for offline functionality
4. `icon-192.png` - Small app icon (192×192 pixels)
5. `icon-512.png` - Large app icon (512×512 pixels)
6. `favicon.ico` - Favicon for browser tabs (optional)

## Deployment Steps

1. **Create icon files** - Create two PNG icons:
   - icon-192.png (192×192 pixels)
   - icon-512.png (512×512 pixels)

   You can use any image editor or icon generator to create these.

2. **Create a GitHub repository**:
   - Sign in to GitHub
   - Click the "+" in the top-right corner and select "New repository"
   - Name your repository (e.g., `coop-tracker`)
   - Make it public
   - Click "Create repository"

3. **Upload files**:
   - Once your repository is created, click "uploading an existing file"
   - Drag and drop all files listed above
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to the "GitHub Pages" section
   - Under "Source", select "main" branch and "/" (root) folder
   - Click "Save"
   - GitHub will provide you with the URL where your app is hosted (typically `https://yourusername.github.io/coop-tracker/`)

5. **Add to Dock/Home Screen**:
   - On desktop browsers that support PWAs (Chrome, Edge):
     - Visit your GitHub Pages URL
     - Look for the install icon in the address bar or menu
     - Click "Install" when prompted
   - On iOS:
     - Open the site in Safari
     - Tap the share button
     - Select "Add to Home Screen"
   - On Android:
     - Open the site in Chrome
     - Tap the menu button (three dots)
     - Select "Add to Home Screen"

## Features

- Track co-op/job applications
- Sort and filter applications
- Store application details
- Export/Import data
- Works offline
- Local storage for data persistence

## Local Storage

All your data is stored in your browser's local storage. This means:
- Data persists even when you close the browser
- Data is private to your device
- No server or database is needed
- You can backup your data using the Export function

To back up your data, use the Export button in the app.
