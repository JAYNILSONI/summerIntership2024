# SummerIntership2024_21IT156

<h2>6th Sem Summer Internship</h2>
# 🌟 AWS Summer Internship 2024 - Project Showcase 🌟

Welcome to my GitHub repository for the AWS Summer Internship 2024! This project showcases the work done during the internship, including practical insights and hands-on experience with Amazon Web Services (AWS).

## 🚀 Introduction

### *25th May 2024*
- *AWS Bootcamp Live Session*: Basics of Amazon Web Services
- On 25th May, there was a live bootcamp led by Amit Arora (Security Architect at AWS) for an AWS Club where entry-level engineers could participate and build their AWS skills from the ground up. Although it wasn't the start of the internship, we learned the basics of Amazon Web Services and how it provides various functionalities to developers. The internship period is 4 weeks long, focusing on labs and practical insights to become familiar with AWS.



# Start of Internship

## 1️⃣ week 1
### *28th May 2024*
- *Orientation Meeting*: Introduction to AWS and overview of the internship tasks
- During the start of the meeting, I tackled questions about AWS to understand its basics. The agenda for the first week regarding the tasks to be done was discussed. The tasks included everything from creating an account to generating a portfolio hosted on an AWS instance.



### *Here is the Outline of Week-1:*

1. Create an AWS Free Tier account
2. Log on to the AWS Console
3. AWS Billing and Cost Management
4. Set up a zero-dollar limit budget
5. Launch an EC2 Instance
6. Connect to the EC2 Instance
7. Install Apache Web Server on the Linux Instance
8. Deploy a personal page.html on Apache
9. Open Security Group for Apache to accept connections on port 80
10. Access the page.html using the public IP address of the EC2 instance

## 📝 Day-by-Day Progress

### Day 1: Creating AWS Free Tier Account
- Created an AWS Free Tier account as part of Task 1.
- Logged on to the AWS Console (Task 2).
- Explored AWS Billing and Cost Management (Task 3).
- Set up a zero-dollar limit budget (Task 4).
- Launched an EC2 instance from the free tier options (Task 5).



### Day 2: Creating Instance with Apache Server to Deploy Web Page
➠ Connected to the EC2 Instance (Task 6):
- After launching the EC2 instance, I connected to it using SSH. This allowed me to access the virtual server, which is essentially a remote computer running on AWS infrastructure. The connection was established securely using the provided key pair, ensuring that my data remains protected.

➠ Installed an Apache Web Server on the Linux Instance (Task 7):
- Once connected, I installed Apache, a widely-used open-source web server software. Apache is crucial for serving web pages to users. The installation involved updating the package repositories and using package management commands to install Apache on the Linux-based EC2 instance.

➠ Deployed a Personal page.html on Apache (Task 8):
- With Apache running, I deployed a simple HTML page (Personalpage.html). This involved placing the HTML file in Apache’s root directory and configuring the server to serve this page. Deploying the HTML page allowed me to create a personal webpage accessible over the internet via the EC2 instance's public IP address.



### Day 3: Building the Portfolio

➠ Setting Up the Project Structure:
- Created a project directory on the EC2 instance for the portfolio website. This included folders for HTML, CSS, JavaScript, and assets like images and fonts.
- Initialized the project with a basic index.html file to serve as the homepage.

➠ Creating the HTML Structure:
- Developed the initial structure of the portfolio using HTML5. This involved creating sections for the header, about me, projects, and contact information.
- Ensured the HTML code was semantic and well-organized to improve readability and SEO.

➠ Integrating Bootstrap:
- Incorporated Bootstrap, a popular CSS framework, to make the portfolio responsive and visually appealing.
Used Bootstrap components like navigation bars, cards, and buttons to enhance the design and functionality of the website.



### Day 4: Enhancing with JavaScript, SASS, and CSS

➠ Adding Interactivity with JavaScript:
- Implemented JavaScript to add interactive features to the portfolio, such as form validation for the contact section and dynamic content loading for the projects section.
Utilized event listeners and DOM manipulation to create a more engaging user experience.

➠ Styling with SASS and CSS:
- Used SASS (Syntactically Awesome Style Sheets) to write more maintainable and modular CSS code. SASS variables, nesting, and mixins helped streamline the styling process.
- Compiled SASS files into CSS and applied custom styles to enhance the visual aesthetics of the portfolio. This included customizing Bootstrap themes and adding unique design elements.

➠ Finalizing the Deployment:
- Ensured all the files were correctly linked and the website was functioning as intended.
- Tested the portfolio on different browsers and devices to ensure compatibility and responsiveness.

➠ Technologies Explored:
- HTML5: Structured the content and elements of the portfolio.
- Bootstrap: Provided a responsive and modern design framework.
- JavaScript: Added interactivity and dynamic functionality to the website.
- SASS: Enhanced the CSS with advanced features for better maintainability and efficiency.
- CSS: Styled the website to improve visual appeal and user experience.



### Day 5: Configuration and Final Touchup
- Configured the Security Group for the Apache server on the EC2 instance to accept incoming connections on port 80. This involved adding an inbound rule in the Security Group settings to allow HTTP traffic, ensuring that the web server is accessible from the internet. (Task 9)

- Verified the configuration by accessing the personal webpage hosted on the EC2 instance. Used the public IP address of the instance in a web browser to confirm that the Apache server is serving the webpage correctly. This demonstrated successful setup and configuration of the web server. (Task 10)





## Notes:
➠ We were given this repo which contains basic documentation of AWS services which can be helpful to everybody: [AWS Cheat Sheet](https://github.com/hamidgholami/accp-cheatsheet)

## 2️⃣ week 2

### *4th June 2024*
- *Online Session*: Learning about storage and S3 with its related services, also switching from EC2 to S3
- At the start of the meeting, we were asked rapid questions regarding week 1 tasks.



### *Here is the Outline of Week-2:*
1. Create a Bucket
2. Make it private
3. Upload files
4. Encrypt the files
5. Create a Distribution
6. Integrate it with S3
7. Create a new KMS Key
8. Change the Default Key for your bucket to this new key
9. Find out these events and logs for them in CloudTrail
10. Shutdown the EC2 instance we created in the first week

## 📝 Day-by-Day Progress

### Day 1: Creating and Configuring an S3 Bucket
➠ Created a new S3 bucket:
- Started by creating a new Amazon S3 bucket. Amazon S3 is a scalable object storage service that allows for the storage and retrieval of any amount of data at any time.

➠ Set the bucket's permissions to private:
- Ensured the bucket's security by setting its permissions to private, making sure that only authorized users have access to the stored data.

➠ Uploaded files to the bucket:
- Uploaded various files to the S3 bucket to test storage and retrieval capabilities. This provided hands-on experience with S3's upload functionalities and permissions settings.



### Day 2: Securing and Distributing Content
➠ *Enabled encryption for the uploaded files*:
  - To enhance data security, I enabled server-side encryption for the files uploaded to the S3 bucket. This ensures that data is encrypted at rest, protecting it from unauthorized access.

➠ *Created a CloudFront distribution and integrated it with the S3 bucket*:
  - Created an Amazon CloudFront distribution to deliver content stored in the S



3 bucket with low latency and high transfer speeds. Integration with CloudFront improves the availability and performance of the web content.

➠ *Created a new KMS key for encryption*:
  - Created a new AWS Key Management Service (KMS) key to use for encrypting the files in the S3 bucket. This allows for more control over the encryption keys and enhances security.

➠ *Changed the default key for the S3 bucket to the new KMS key*:
  - Configured the S3 bucket to use the newly created KMS key as the default key for encrypting objects. This ensures that all new files uploaded to the bucket are encrypted with the KMS key, enhancing the security of stored data.



### Day 3: Monitoring and Logging

➠ *Enabled CloudTrail for logging events*:
  - Enabled AWS CloudTrail to log and monitor activities related to the S3 bucket. CloudTrail provides detailed logs of API calls made to AWS services, allowing for auditing and compliance monitoring.

➠ *Configured CloudTrail to track bucket events*:
  - Configured CloudTrail to specifically track events related to the S3 bucket, such as file uploads, downloads, and permission changes. This helps in keeping an eye on activities and identifying any unauthorized access attempts.



### Day 4: Shutting Down EC2 Instance

➠ *Deactivated the EC2 instance from Week 1*:
  - As part of the task, I shut down the EC2 instance that was created and configured during the first week. This involved stopping the instance and ensuring that no further charges would be incurred.

➠ *Cleaned up associated resources*:
  - Cleaned up associated resources, such as security groups and key pairs, to ensure no leftover configurations were taking up resources or creating potential security risks.



## Notes:
➠ Throughout Week 2, I gained hands-on experience with Amazon S3, KMS, and CloudTrail. These skills are critical for managing and securing data storage solutions on AWS.

## 3️⃣ week 3

### *11th June 2024*
- *Online Session*: Introduction to DynamoDB and its functionalities.
- Discussed advanced topics related to AWS services, focusing on DynamoDB, a NoSQL database service.



### *Here is the Outline of Week-3:*
1. Create a DynamoDB table
2. Insert Items into the table
3. Query the table
4. Perform a scan operation
5. Create an index
6. Query the index
7. Enable DynamoDB Streams
8. Process stream records using AWS Lambda
9. Create a backup of the table
10. Restore the table from the backup

## 📝 Day-by-Day Progress

### Day 1: Creating and Managing DynamoDB Table
➠ *Created a DynamoDB table*:
  - Created a new DynamoDB table to store structured data. Configured the table's primary key and specified attributes.

➠ *Inserted items into the table*:
  - Added items to the DynamoDB table using the AWS Management Console. This involved specifying values for the primary key and other attributes.



### Day 2: Querying and Scanning DynamoDB
➠ *Performed query operations*:
  - Used DynamoDB's query functionality to retrieve items based on specific criteria. Queries are efficient when searching by primary key or secondary index.

➠ *Performed scan operations*:
  - Conducted scan operations to retrieve all items from the DynamoDB table. Scans are useful for analyzing data but can be less efficient for large datasets.



### Day 3: Indexing and Streams
➠ *Created a secondary index*:
  - Created a secondary index on the DynamoDB table to enable querying on non-primary key attributes. This enhances query flexibility.

➠ *Queried the secondary index*:
  - Used the secondary index to perform queries on attributes other than the primary key. This demonstrated the power of indexing in DynamoDB.

➠ *Enabled DynamoDB Streams*:
  - Enabled DynamoDB Streams to capture data modification events in the table. Streams provide real-time change data capture capabilities.



### Day 4: Lambda Integration and Backup
➠ *Processed stream records with AWS Lambda*:
  - Created an AWS Lambda function to process DynamoDB stream records. This function reacts to data changes in the DynamoDB table and performs specific actions based on the changes.

➠ *Created a backup of the DynamoDB table*:
  - Created an on-demand backup of the DynamoDB table to ensure data durability and disaster recovery capabilities.

➠ *Restored the table from the backup*:
  - Restored the DynamoDB table from the backup to verify the backup and restore functionality. This ensures that data can be recovered in case of any loss or corruption.



## Notes:
➠ Week 3 provided a deep dive into DynamoDB, highlighting its scalability and flexibility for handling NoSQL data. The integration with AWS Lambda for stream processing showcased the power of event-driven architecture.

## 4️⃣ week 4

### *18th June 2024*
- *Online Session*: Exploring API Gateway and AWS Lambda functions
- Focused on building serverless applications using API Gateway and Lambda. Discussed how these services integrate to create scalable and cost-effective applications.



### *Here is the Outline of Week-4:*
1. Create an API using API Gateway
2. Create a Lambda function
3. Integrate the API with the Lambda function
4. Deploy the API
5. Test the API
6. Enable logging and monitoring
7. Secure the API with API keys
8. Enable CORS for the API
9. Create a custom domain for the API
10. Monitor the API using CloudWatch

## 📝 Day-by-Day Progress

### Day 1: Setting Up API Gateway and Lambda
➠ *Created an API using API Gateway*:
  - Created a new REST API using Amazon API Gateway. Defined the resources and methods for the API.

➠ *Created a Lambda function*:
  - Developed a Lambda function to handle requests from the API. Lambda allows running code without provisioning or managing servers.



### Day 2: Integration and Deployment
➠ *Integrated API Gateway with the Lambda function*:
  - Linked the API Gateway methods to the Lambda function, enabling the API to trigger the Lambda function upon receiving requests.

➠ *Deployed the API*:
  - Deployed the API to a stage, making it accessible via a public endpoint. API Gateway handles the deployment process, ensuring the API is ready for use.



### Day 3: Testing and Securing the API
➠ *Tested the API*:
  - Performed various tests to ensure the API was functioning correctly. This involved sending requests and verifying the responses from the Lambda function.

➠ *Enabled logging and monitoring*:
  - Enabled detailed logging and monitoring for the API using AWS CloudWatch. This helps in tracking API usage and identifying potential issues.

➠ *Secured the API with API keys*:
  - Implemented API keys to restrict access to the API. This ensures that only authorized users can make requests to the API.



### Day 4: Enhancements and Monitoring
➠ *Enabled CORS for the API*:
  - Configured Cross-Origin Resource Sharing (CORS) to allow the API to be accessed from different domains. This is crucial for enabling web applications to interact with the API.

➠ *Created a custom domain for the API*:
  - Set up a custom domain for the API, making it easier to access and more professional-looking. This involved configuring DNS settings and linking the domain to the API Gateway.

➠ *Monitored the API using CloudWatch*:
  - Used Amazon CloudWatch to monitor the API's performance and usage metrics. This helps in identifying trends and potential issues in real-time.



## Notes:
➠ Week 4 focused on building and deploying serverless applications using API Gateway and Lambda. The hands-on experience with these services demonstrated the benefits of serverless architecture, such as scalability, cost-efficiency, and ease of management.

## 🌟 Conclusion
This internship has provided valuable hands-on experience with various AWS services, enhancing my skills in cloud computing and serverless architecture. The project tasks helped me understand the practical applications of AWS and

 how to leverage its services to build scalable, secure, and efficient solutions.

![Conclusion](https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif)

