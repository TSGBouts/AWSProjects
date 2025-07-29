# Host a Static Website on Amazon S3

This project demonstrates how to host a static website using **Amazon S3**. It was completed as part of the [NextWork](https://learn.nextwork.org/) platform to gain hands-on experience with AWS services.

---

## 📌 Objectives

- Create and configure an S3 bucket
- Upload static website files (HTML and assets)
- Enable static website hosting
- Set appropriate permissions and make the content publicly accessible
- Understand and resolve common S3 hosting issues (e.g., 403 Forbidden)

---

## ⚙️ Tools & Services Used

- **AWS S3**
- **Bucket Policies**
- **Access Control Lists (ACLs)**
- **Static Website Hosting Configuration**

---

## 🛠️ Steps Taken

### 1. Create an S3 Bucket

Chose the **Europe (Stockholm)** region for low latency and created a globally unique bucket.

![S3 Bucket Created](./images/bucket-created.png)

---

### 2. Upload Website Files

Uploaded:
- `index.html`
- A folder with image assets

These make up the content of the static website.

![Files Uploaded](./images/upload-files.png)

---

### 3. Enable Static Website Hosting

Enabled static website hosting via the **Properties** tab and set `index.html` as the default document.

![Static Hosting Enabled](./images/enable-hosting.png)

---

### 4. Resolve 403 Forbidden Error

At first, visiting the site URL returned a **403 Forbidden**. The issue was fixed by correcting the public access settings.

---

### ✅ Final Deployed Website

The static site was successfully deployed and accessed via the **S3 website endpoint URL**.

![Website Live](./images/website-final.png)

---

## ⏱ Time Taken

Approximately **30 minutes** to complete the entire project.

---

## 🧠 Key Concepts Learned

- S3 bucket creation and naming rules
- Uploading and organizing static content
- Enabling and configuring static website hosting
- Understanding and managing public access via ACL and policies

---

## 📁 Project Files

This folder includes:

- `index.html` – Main page of the website
- `assets/` – Images and supporting resources
- `images/` – Screenshots for documentation
- `README.md` – Project documentation