# Deploying Static website in AWS

The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. In this project, you will deploy a static website to AWS.

- First, you will create an S3 bucket, configure the bucket for website hosting, and secure it using IAM policies.

- Next, you will upload the website files to your bucket and speed up content delivery using AWS’s content distribution network service, CloudFront.

- Lastly, you will access your website in a browser using the unique S3 endpoint.

### Project Submission Checklist
Before submitting your project, please review and confirm the following items.

 - [x] I am confident all rubric items have been met and my project will pass as submitted.

 - [x] My project builds correctly without errors and runs.

 - [x] All required functionality exists and my project behaves as expected per the project's specifications.

 - [x] I have included the required screenshots in my submission folder

 - [x] I have included a README.txt file in the submission folder that includes the CloudFront endpoint URL for my project

 
### S3 Bucket creation
![Image 1](https://github.com/sdkdeepa/Udacity-CDnano-Project-1/blob/main/Project1-Deepa%20Subramanian_AWS-Static-Website/Deepa-S3BucketCreation.png)

### IAM Bucket Policy
![Image 2](https://github.com/sdkdeepa/Udacity-CDnano-Project-1/blob/main/Project1-Deepa%20Subramanian_AWS-Static-Website/Deepa-S3-IAM-Bucket-Policy.png)

### S3 configration for Static Web Hosting
![Image 3](https://github.com/sdkdeepa/Udacity-CDnano-Project-1/blob/main/Project1-Deepa%20Subramanian_AWS-Static-Website/Deepa-S3-Config-Support-Static-Web-hosting.png)

### Files uploaded to S3 bucket
![Image 4](https://github.com/sdkdeepa/Udacity-CDnano-Project-1/blob/main/Project1-Deepa%20Subramanian_AWS-Static-Website/Deepa-Files-Uploaded-To-S3bucket.png)

### CloudFront Configration
![Image 5](https://github.com/sdkdeepa/Udacity-CDnano-Project-1/blob/main/Project1-Deepa%20Subramanian_AWS-Static-Website/Deepa-CloudFront-Configuration.png)

### Static AWS Website 
![Image 6](https://github.com/sdkdeepa/Udacity-CDnano-Project-1/blob/main/Project1-Deepa%20Subramanian_AWS-Static-Website/Deepa-Aws-Static-Website.png)

Note: In step 4 of the project instruction(Secure Bucket via IAM), disable "Blocking public access" to allow public access.(Had to figure out on my own. This step has changed as of 10/25/2020). 
