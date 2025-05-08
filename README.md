# LeadsTracker

LeadsTracker is a lightweight Chrome extension built using HTML, CSS, and JavaScript that helps users quickly save and manage useful URLs. Whether you want to save the current browser tab or manually enter a link, LeadsTracker makes it easy and efficient.

## ✨ Features

- **Save Current Tab:**  
  Click the **SAVE TAB** button to automatically capture and save the URL of your active browser tab using the `chrome.tabs.query` API.

- **Save Input URL:**  
  Enter any URL into the input box and click **SAVE INPUT** to store it alongside other saved links.

- **View Saved Links:**  
  All saved URLs are listed below the buttons, allowing you to easily access them later.

- **Delete All:**  
  Use the **DELETE ALL** button to clear all stored URLs at once.

- **Local Storage Integration:**  
  Saved links are stored locally using the browser’s `localStorage` API, so your data stays persistent even after closing the browser.

## 🛠️ Tech Stack

- HTML  
- CSS  
- JavaScript  
- Chrome Extensions API (`chrome.tabs.query`)  
- Browser Local Storage

## 📦 How to Use

1. Install the extension in Chrome (load as an unpacked extension in developer mode).
2. Open any website and click **SAVE TAB** to save its URL.
3. Or, paste a link into the input field and click **SAVE INPUT**.
4. Click **DELETE ALL** to clear your saved links.
