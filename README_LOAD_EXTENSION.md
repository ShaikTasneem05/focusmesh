# How to Load FocusMesh Extension (Developer Mode)

FocusMesh is currently provided as a privacy-first, on-device browser extension prototype.
For hackathons, demos, and early testing, it is loaded using Chrome’s **Developer Mode**.

This ensures:
- No user data is uploaded anywhere
- All analysis happens locally on the user’s device
- Full transparency of the codebase

---

## 🔹 Step-by-Step Installation (2 Minutes)

### 1. Download the Project
- Open the FocusMesh GitHub repository
- Click **Code → Download ZIP**
- Extract the ZIP file to any folder on your computer

---

### 2. Open Chrome Extensions Page
- Open Google Chrome
- Go to:  
  `chrome://extensions`

---

### 3. Enable Developer Mode
- Turn ON **Developer Mode** (top-right corner)

---

### 4. Load the Extension
- Click **Load Unpacked**
- Select the extracted `focusmesh-extension` folder
- The FocusMesh icon will appear in the Chrome toolbar

---

## 🔹 How FocusMesh Works

- Users set **one active task** using the extension popup
- The extension analyzes **only visible page text**, locally
- No browsing data, credentials, or personal information are stored or transmitted
- Behavioral signals (like tab switching and scrolling) are processed **on-device only**

---

## 🔐 Privacy by Design

- ❌ No cloud servers
- ❌ No user tracking
- ❌ No third-party analytics
- ✅ 100% local execution
- ✅ User-controlled data

This makes FocusMesh suitable for **students, institutions, and enterprises**.

---

## 🚀 Why Developer Mode?

Publishing to the Chrome Web Store requires review time and fees.
For hackathons and early-stage demos, Developer Mode is the fastest and most transparent way to showcase a fully working prototype.

> Chrome Web Store publishing is planned as a future step.

---

## 📌 Troubleshooting

- If the extension does not appear:
  - Ensure Developer Mode is ON
  - Reload the extension
- If a page does not respond:
  - Reload the tab once
  - Some system pages cannot be analyzed by Chrome extensions

---

## 📬 Feedback & Contributions

This is an early prototype built during a hackathon.
Feedback, suggestions, and contributions are welcome.

---

**FocusMesh — clarity over chaos.**
