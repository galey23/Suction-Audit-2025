# 🏥 Suction Equipment Audit App

This is a browser-based audit tool for hospital staff to perform suction equipment audits across wards. It features random bed selection, standardized audit forms, and is designed for mobile, tablet, and desktop use.

---

## 📋 Features

- Login via dropdown auditor list
- Ward selection from 42 pre-defined options
- Input total number of beds per ward
- Automatically selects **7 unique random beds**
- Generates 9-point suction equipment checklist per bed
- Responsive design for smartphones, tablets, and computers

---

## 🚀 How to Use

1. Open `index.html` in any modern browser (Chrome, Edge, Safari)
2. Select your name from the **Auditor** dropdown
3. Choose a **Ward**
4. Enter the **total number of beds** in the selected ward (minimum: 7)
5. Click **“Generate Bed Audits”**
6. Fill out the 7 audit forms (one per bed, bed number is auto-labeled)
7. (Optional) Connect to Microsoft Excel via Power Automate to save audit data

---

## 💾 Data Storage (Optional Integration)

To store audit results automatically in Excel:

1. Create an Excel file on **OneDrive or SharePoint** with a formatted table
2. Build a **Power Automate flow** that:
   - Triggers from an HTTP POST request
   - Parses submitted data
   - Inserts rows into the Excel table
3. Add a `submit` button + JavaScript in this app to send data to the flow
4. ---

## 📱 Device Compatibility

| Device       | Supported |
|--------------|-----------|
| Smartphones  | ✅        |
| Tablets      | ✅        |
| Desktops     | ✅        |
| Offline Mode | ✅ (no sync) |

---

## 🔐 Privacy Notice

This version does **not include password protection**. While it’s safe for internal use, if hosted publicly (e.g., GitHub Pages), it may be indexed by search engines unless blocked.

**For internal/private hosting**, consider:
- Microsoft SharePoint
- Netlify with password protection
- Internal hospital web server

---

## 👨‍⚕️ Authors & Contributors

Developed by your clinical audit team.  
You’re welcome to expand or adapt it for your department’s needs.

---
