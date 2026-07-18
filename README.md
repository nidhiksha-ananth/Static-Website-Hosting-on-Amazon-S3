# Static-Website-Hosting-on-Amazon-S3

# 🌐 Static Website Hosting on Amazon S3

![AWS](https://img.shields.io/badge/AWS-S3-orange?logo=amazonaws)
![HTML](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview

This project demonstrates how to deploy a static website using **Amazon S3 Static Website Hosting**.

The website consists of HTML, CSS, JavaScript, images, and other static assets. During deployment, I configured S3 bucket permissions, enabled static website hosting, and resolved issues related to bucket policies and resource paths.

---

## 🚀 Live Website

🔗 **Website URL**

http://nextwork-website-project-nidhiksha.s3-website.ap-south-2.amazonaws.com

---

## 📸 Screenshots

### Homepage

<img width="1385" height="817" alt="Final website" src="https://github.com/user-attachments/assets/21b3ece2-6c1e-4f6c-a2cf-bbec83901f7d" />


### Amazon S3 Bucket

<img width="1033" height="372" alt="S3 buckets" src="https://github.com/user-attachments/assets/0b6e76af-77c6-449c-9c77-dd420036f6f2" />


### Static Website Hosting Configuration

<img width="1507" height="485" alt="Static website hosting" src="https://github.com/user-attachments/assets/d688ce3c-1cf1-4729-9084-02710d8f85e2" />


---

## 🏗️ Architecture

```text
User
   │
   ▼
Amazon S3 Bucket
   │
   ├── index.html
   ├── CSS
   ├── JavaScript
   ├── Images
   └── Static Assets
```

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Amazon S3
- Git
- GitHub

---

## 📂 Project Structure

```text
.
├── index.html
├── NextWork - Everyone should be in a job they love_files/
│   ├── nextwork-staging.webflow.dc303a7da.min.css
│   ├── webflow.e2351bb6c.js
│   ├── images
│   └── other assets
└── README.md
```

---

## ⚙️ Deployment Steps

1. Created an Amazon S3 bucket.
2. Enabled **Static Website Hosting**.
3. Uploaded website files and assets.
4. Disabled Block Public Access (for this static website).
5. Added a Bucket Policy to allow public read access.
6. Verified website accessibility through the S3 website endpoint.
7. Uploaded the project to GitHub.

---

## 🔧 Challenges Faced

- CSS and images were not loading.
- Incorrect folder structure after uploading.
- Missing Bucket Policy.
- Resource path issues.
- GitHub push conflicts.

### ✅ Solutions

- Corrected folder hierarchy.
- Configured Bucket Policy for public access.
- Used the S3 Website Endpoint.
- Verified object paths and permissions.
- Resolved Git synchronization issues.

---

## 📚 Learning Outcomes

- Amazon S3 Static Website Hosting
- S3 Bucket Policies
- Public Access Configuration
- Static Asset Management
- Git Version Control
- GitHub Repository Management

---

## 👩‍💻 Author

**Nidhiksha Ananth**

GitHub: https://github.com/nidhiksha-ananth

---

⭐ If you found this project helpful, feel free to star the repository!
