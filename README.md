# AWS S3 Static Website Hosting with Versioning & Lifecycle Management

## 👤 Student Details

**Name:** Rishi Balodi
**Registration Number:** 12319907

---

## 🌐 Deployed Website  
 [View Live Website](http://rishi-static-site-2929.s3-website.ap-south-1.amazonaws.com/)

---

## 📌 Assignment Objective

This project demonstrates the use of Amazon S3 for:

* Static website hosting
* Versioning of objects
* Lifecycle management for cost optimization

---

## ⚙️ Steps Performed

### 1. Created S3 Bucket

* Created a globally unique bucket
* Configured region (Mumbai)

### 2. Enabled Versioning

* Uploaded multiple versions of `index.html`
* Verified version history

### 3. Static Website Hosting

* Enabled static website hosting
* Configured index document

### 4. Permissions Setup

* Disabled block public access
* Added bucket policy for public read access

### 5. Lifecycle Rules

* Transitioned objects to Standard-IA after 30 days
* Deleted old versions after 7 days

---

## 📸 Screenshots

### Bucket Objects
<img width="957" height="476" alt="Screenshot 2026-04-27 163120" src="https://github.com/user-attachments/assets/c9033741-3fcf-4eca-ac80-e4dfce61dff3" />



### Versioning

<img width="959" height="474" alt="Screenshot 2026-04-27 163138" src="https://github.com/user-attachments/assets/c158b0ab-c907-493e-bcba-f51d295203ff" />


### Lifecycle Rule

<img width="959" height="473" alt="Screenshot 2026-04-27 163059" src="https://github.com/user-attachments/assets/1851c438-828e-4a62-ad1b-a2f86691689b" />


### Website Output

<img width="959" height="476" alt="Screenshot 2026-04-27 163154" src="https://github.com/user-attachments/assets/074baa4a-98c2-4931-a4d8-0cc197019baa" />


---

## ⚠️ Challenges Faced

* Faced "Access Denied" error due to incorrect permissions
* Resolved by configuring bucket policy and public access settings
* Browser caching issue while updating website

---

## 🚀 Conclusion

This assignment helped in understanding AWS S3 services including hosting, version control, and lifecycle automation.
