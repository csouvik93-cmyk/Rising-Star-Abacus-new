# 🚀 R-STAR TECH ACADEMY - ADMISSION PORTAL

THIS DOCUMENT PROVIDES AN OVERVIEW AND SETUP GUIDE FOR THE RISING STAR TECH ACADEMY'S SERVERLESS ADMISSION PORTAL.

---

### 🌟 PROJECT OVERVIEW

This is a modern, responsive, and secure admission portal designed to collect detailed student application data, including necessary documents (photos, ID proof), using Netlify's powerful serverless form features.

**KEY TECHNOLOGIES USED:**

* **Frontend:** HTML5, CSS3, JavaScript
* **Design/UX:** GSAP (Scroll Animations)
* **Backend:** Netlify Forms (Serverless Data Handling)

---

### 📋 FEATURES

* **Detailed Application Form:** Collects comprehensive information (Address split into Village, P.S., District, etc., Guardian details).
* **File Uploads:** Supports secure uploading of Student Photos and Guardian documents.
* **Animated Design:** Uses GSAP for smooth and professional scroll animations.
* **Admin Access Protection:** Implements a client-side PIN check for accessing the submissions dashboard.
* **Dynamic Course List:** Includes updated course offerings (`ADIT + AI`, `DT`, `Tally`, etc.).

---

### ⚠️ IMPORTANT LIMITATIONS (NETLIFY FREE TIER)

**FILE SIZE IS CRITICAL FOR SUCCESSFUL SUBMISSION.**

* **Total Limit:** The combined size of all file uploads (Photo, Signature, ID) in a single application **MUST NOT EXCEED 10MB**.
* **Failure:** Submissions with files larger than 10MB will result in a "Submission Failed" error.

---

### 🔑 ADMIN ACCESS AND SECURITY

The Admin Panel is hidden and protected to ensure only authorized personnel can view the collected data.

1.  **ACCESS URL:** Navigate to `YOUR_SITE_URL/admin-data.html`
2.  **PIN VERIFICATION:** Enter the pre-defined Admin PIN.
3.  **VIEW DATA:** Upon successful verification, you are redirected to the Netlify Forms dashboard for the site **`sweet-syrniki-5f1858`**.

> **SECURITY NOTE:** The PIN (`1234` by default) is set in the JavaScript of the `admin-data.html` file. **IT IS HIGHLY RECOMMENDED TO CHANGE THIS PIN** to a complex value immediately after deployment.

---

### 🚀 DEPLOYMENT GUIDE

This portal is optimized for deployment on Netlify.

1.  **COLLECT FILES:** Ensure you have all required files (`index.html`, `admin-data.html`, `script.js`, `style.css`) in one folder.
2.  **NETLIFY DEPLOY:** Log in to your Netlify account, go to the **"Deploys"** tab for your site, and **Drag & Drop** the project folder to initiate the build.
3.  **FORM CHECK:** Verify that "Form detection is enabled" in the Netlify Settings.
4.  
