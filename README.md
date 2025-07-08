# 💻 Tech For Girls - Registration Website

Welcome to the **Tech For Girls Community Registration** mini project!  
This is a modern, interactive registration webpage built for the **Tech For Girls initiative**.

---

## 🔥 Features

- ✅ Clean and modern UI (inspired by Dribbble/Behance)
- ✅ Collects basic user information:
  - Name
  - Phone number
  - Email ID
  - College/Department
- ✅ WhatsApp share button with live click counter (5-click limit)
- ✅ Screenshot upload (image or PDF)
- ✅ Stores all form data in a connected **Google Sheet**
- ✅ Uploaded file is saved to **Google Drive folder**
- ✅ Single submission lock using `sessionStorage` (per browser tab)
- ✅ GitHub Pages hosted (CORS-safe via `<iframe>` submission)

---

## 🛠 Tech Stack

- **HTML5 + CSS3 + JavaScript**
- **Google Apps Script** for backend
- **Google Sheets & Drive API**
- **GitHub Pages** for hosting

---

## 🚀 How It Works

1. User fills out the registration form
2. Must click the **WhatsApp share button 5 times** (tracked via counter)
3. Uploads a screenshot (image/pdf)
4. Once sharing is complete, **Submit** is enabled
5. Data is submitted through a hidden `<iframe>` (CORS-safe)
6. Google Apps Script:
   - Appends form data to a Google Sheet
   - Saves uploaded file to a Google Drive folder
7. Shows success message and disables form for that session

---

## 📝 Setup Instructions

### 1. 🔗 Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/tech-for-girls-registration.git
cd tech-for-girls-registration
