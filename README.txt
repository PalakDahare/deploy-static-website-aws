Project: Deploy Static Website on AWS

Student: Palak Dahare

---

## Website URLs
- CloudFront Domain Name: https://d258ipksblvn0u.cloudfront.net/
- S3 Website Endpoint: http://my-985640785662-bucket.s3-website-us-east-1.amazonaws.com/



## Project Overview
This project demonstrates deploying a static website on AWS using S3, IAM policies, and CloudFront.

Steps performed:
1. Created an S3 bucket (my-985640785662-bucket).
2. Configured the bucket for static website hosting (index.html as root).
3. Uploaded all website files (HTML, CSS, JS, images).
4. Applied a public-read bucket policy to allow access.
5. Created a CloudFront distribution pointing to the S3 static website endpoint.
6. Verified the website is accessible through both S3 endpoint and CloudFront domain.

---

## Screenshots Included
The `Project Screenshots` folder contains:
1. **Project Screenshots/Screenshot Bucket.png** – Newly created bucket visible in AWS Console.
2. **Screenshot Upload Files.png** – Website files uploaded into the S3 bucket.
3. **Screenshot Static Website Hosting.png** – Static website hosting configuration page.
4. **Screenshot Bucket policy** – Bucket policy applied to allow public read.
5. **CloudFront Distributions Screenshot.png** – CloudFront distribution successfully deployed.
6. **Blog Screenshot.png** – Final website loaded in a browser via CloudFront URL.

---


## Notes
- Website customized with updated text and background image to make it unique.
- Default root object set as `index.html` in CloudFront to avoid “Access Denied” errors.
- CloudFront cache invalidated (`/*`) to ensure updated content is visible.



