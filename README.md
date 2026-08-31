# 🌍 WhatsApp International Community Exporter (Privacy-First)

A lightweight, secure Google Chrome extension created by **DaxBuilds22** for WhatsApp Community and Group admins to extract participant numbers and automatically sort them cleanly into columns by country code with an automated dashboard summary.

---

### 🔒 100% Privacy Guaranteed (Zero Data Collection)
Unlike commercial scrapers on the Chrome Web Store, **this tool does not use external servers or databases.** 
* All scraping, country mapping, and spreadsheet generation happen **locally inside your computer's browser memory**.
* Your community's phone numbers are **never shared, transmitted, or uploaded to the internet**.

---

### 🚀 How to Install (Developer Mode)

Because this tool is private and open-source, you install it directly as a local developer folder:

1. Click the **Code** button at the top right of this GitHub page and select **Download ZIP**.
2. Unzip the file onto your desktop (you will see a folder containing `manifest.json`, `popup.html`, `popup.js`, and this `README.md`).
3. Open Google Chrome and type `chrome://extensions/` into the address bar.
4. In the top-right corner, turn on the **Developer mode** toggle switch.
5. In the top-left corner, click the **Load unpacked** button.
6. Select the extracted `WhatsApp-Exporter` folder from your desktop. 

*The extension icon will now appear in your browser's extension menu (the puzzle piece icon).*

---

### 📊 How to Use for 100% Accuracy

To bypass WhatsApp's dynamic screen loading limits and guarantee every single number is caught, use this specific routine:

1. Open **WhatsApp Web** on your computer.
2. Click to open the specific **Group Info** or **Community Info** sidebar panel showing the members list.
3. Click the extension icon in your Chrome bar and click **1. Start Tracking Memory**.
4. **Scroll down the participant list very slowly** from top to bottom. (Use your keyboard's down-arrow key for a steady pace).
5. If a loading wheel appears, pause for 2 seconds to let the numbers render.
6. Once you reach the very bottom, **scroll all the way back up to the top** just as slowly. This secondary pass catches any block dropped by browser memory on the way down.
7. Open the extension popup again and click **2. Export & Sort Clean List**.

---

### 📈 What You Get in Excel (Example Output)

Your download will save instantly as a clean `.csv` spreadsheet, perfectly divided into three native cells with a structural tally box at the bottom:

| Country Code | Phone Number | Country |
| :--- | :--- | :--- |
| +43 | 6643001414 | Austria |
| +359 | 878868750 | Bulgaria |
| +91 | 6207693309 | India |
| +1 | 4168289133 | United States |

**Bottom Summary Row Breakdown Example:**
* India: 1247 members
* United States: 12 members
* Iran: 16 members

---

### ⚠️ Disclaimer
This tool is intended for administrative metrics, regional group cleanup, and audience analytics by authorized group managers. Automated scraping may violate WhatsApp's terms of service. The creators assume zero liability for account misuse or platform restrictions. Use responsibly.

---
Maintained with 💻 by [DaxBuilds22](https://github.com)
