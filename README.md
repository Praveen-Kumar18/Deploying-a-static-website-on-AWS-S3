# Deploying a Static Website on AWS S3

## 📌 Introduction

This project demonstrates how to deploy a static website using **Amazon Web Services (AWS) S3 (Simple Storage Service)**. AWS S3 provides a cost-effective, scalable, and highly available solution for hosting static web applications consisting of HTML, CSS, JavaScript, and other static assets. The project covers the complete deployment process, from creating an S3 bucket to configuring it for public website hosting.

---

## 🎯 Objectives

* Understand the fundamentals of static website hosting on AWS S3.
* Create and configure an S3 bucket for website deployment.
* Upload website files (HTML, CSS, JavaScript, images, etc.).
* Configure bucket policies and permissions for public access.
* Enable Static Website Hosting and access the website through the generated endpoint.
* Learn a simple and scalable cloud deployment workflow.

---

## 🛠️ Technology Used

* **Amazon Web Services (AWS)**
* **AWS S3 (Simple Storage Service)**
* **HTML5**
* **CSS3**
* **JavaScript**
* **AWS Management Console**

---

## ⚙️ Methodology

1. Log in to the AWS Management Console.
2. Create a new S3 bucket with a globally unique name.
3. Disable Block Public Access settings (if required for public hosting).
4. Upload all static website files to the bucket.
5. Configure bucket permissions using an appropriate bucket policy.
6. Enable the **Static Website Hosting** feature in the bucket properties.
7. Specify the index document (e.g., `index.html`) and error document (optional).
8. Access the website using the AWS S3 static website endpoint.
9. Verify that the website is publicly accessible and functioning correctly.

---

## 📊 Output / Result

* Successfully hosted a static website on AWS S3.
* Website is accessible through the generated S3 website endpoint.
* Demonstrated cloud-based deployment without the need for a traditional web server.
* Achieved a scalable, reliable, and low-cost hosting solution for static content.

---

## ✅ Conclusion

This project illustrates the process of deploying a static website using AWS S3, showcasing the simplicity and efficiency of cloud-based hosting. It provides hands-on experience with AWS storage services, bucket configuration, access management, and static website hosting, making it an excellent foundation for learning cloud deployment and web hosting concepts.

---

## 🚀 Future Enhancements

* Configure a custom domain using **Amazon Route 53**.
* Enable HTTPS using **Amazon CloudFront** and SSL certificates.
* Automate deployment using **GitHub Actions** or AWS CI/CD services.
* Implement versioning and lifecycle policies for better management.

