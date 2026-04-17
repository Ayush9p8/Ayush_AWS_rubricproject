PROJECT TITLE
Static Website Deployment on AWS

---

PROJECT OVERVIEW
This project demonstrates the deployment of a static website using Amazon Web Services (AWS). The website consists of HTML, CSS, JavaScript, and image assets. It is hosted on Amazon S3 and delivered globally using Amazon CloudFront to achieve low latency and high performance.

---

OBJECTIVES

* Deploy a static website using Amazon S3
* Configure secure public access using IAM policies
* Improve website performance using CloudFront CDN
* Provide global accessibility via CloudFront endpoint

---

SERVICES USED

* Amazon S3 – Static website hosting
* AWS IAM – Access control and security
* Amazon CloudFront – Content Delivery Network (CDN)

---

PROJECT STRUCTURE

* index.html → Main webpage
* /css → Stylesheets
* /vendor → Bootstrap, jQuery, FontAwesome libraries
* /img → Image assets (e.g., beach.jpg, van image)
* /screenshots → Project screenshots
* README.txt → Project documentation

---

IMPLEMENTATION STEPS

1. Created an S3 bucket with a unique name and selected region.
2. Disabled "Block Public Access" to allow website hosting.
3. Enabled Static Website Hosting:

   * Index Document: index.html
4. Uploaded all website files (HTML, CSS, JavaScript, images).
5. Configured bucket policy to allow public read access.
6. Created a CloudFront distribution with the S3 bucket as origin.
7. Deployed the distribution and accessed the website via CloudFront.

---

ACCESS URLS

S3 Website Endpoint:
http://static-website-1650a.s3-website-us-east-1.amazonaws.com

CloudFront Endpoint URL:
https://d2ql5k30n6wefs.cloudfront.net

---

SCREENSHOTS INCLUDED
(All screenshots are available in the /screenshots folder)

* s3.png → S3 bucket creation
* off blocking access.png → Public access configuration
* static website hosting.png → Hosting enabled
* s3 bucket all files.png → Files uploaded
* policy.png → Bucket policy
* website distribution.png → CloudFront distribution setup
* cloudfront.png → Distribution deployed
* domain.png → Endpoint URL
* web app.png → Final website output

---

NOTES

* All configurations were performed using the AWS Management Console
* The website is publicly accessible via the CloudFront endpoint
