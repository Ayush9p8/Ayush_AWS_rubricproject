Project Title: Static Website Deployment on AWS

---

Project Overview:
This project demonstrates how to deploy a static website using Amazon Web Services (AWS). The website consists of HTML, CSS, JavaScript, and image assets, hosted on Amazon S3 and delivered globally using Amazon CloudFront for improved performance and low latency.

---

Objectives:

* Deploy a static website using Amazon S3
* Configure secure public access using IAM policies
* Improve performance using CloudFront CDN
* Provide global access via CloudFront endpoint

---

Services Used:

* Amazon S3 – Static website hosting
* AWS IAM – Access control and security
* Amazon CloudFront – Content Delivery Network (CDN)

---

Project Structure:

* index.html → Main webpage
* /css → Stylesheets
* /vendor → Bootstrap, jQuery, FontAwesome libraries
* /img → Images used in website (beach.jpg, van image, etc.)
* /screenshots → All required project screenshots
* README.txt → Project documentation

---

Implementation Steps:

1. Created an S3 bucket and configured region.
2. Disabled "Block Public Access" to allow website hosting.
3. Enabled Static Website Hosting:

   * Index Document: index.html
4. Uploaded all project files (HTML, CSS, JS, images).
5. Applied bucket policy to allow public read access.
6. Created a CloudFront distribution using S3 as origin.
7. Successfully deployed and accessed the website via CloudFront.

---

CloudFront Endpoint URL:
https://d2ql5k30n6wefs.cloudfront.net

---

Screenshots Included:
(All screenshots are available in the /screenshots folder)

* s3.png → S3 bucket creation
* off blocking access.png → Public access configuration
* static website hosting.png → Hosting enabled
* s3 bucket all files.png → Files uploaded
* policy.png → Bucket policy
* website distribution.png → CloudFront setup
* cloudfront.png → Distribution deployed
* domain.png → Endpoint URL
* web app.png → Final website output

---

Notes:

* All configurations were done using AWS Management Console
* Website is publicly accessible via CloudFront URL
