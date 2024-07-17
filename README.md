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

## 3️⃣ Week 3
### 12th June 2024: Online Session: Introduction to AWS DynamoDB, API Gateway, and Lambda Functions

This week focused on building a serverless backend using AWS services like DynamoDB, API Gateway, and Lambda Functions. We worked on a project to create CRUD APIs for managing items in a DynamoDB table.

### Outline of Week 3
- **Create a table in DynamoDB**
- **Write a Lambda Function as a Backend**
- **Configure API Endpoints on API Gateway**
  - GET /items
  - PUT /items
  - GET /items/{id}
  - DELETE /items/{id}
- **Configure API Endpoints with Lambda Code**
- **Test Out APIs through Curl and Browser**

### 📝 Day-by-Day Progress

**Day 1: Creating a Table in DynamoDB**
- Created a new table in Amazon DynamoDB, a fast and flexible NoSQL database service designed for applications requiring consistent, single-digit millisecond latency at any scale. Configured the table with a primary key and other necessary attributes to store item data efficiently.

**Day 2: Writing Lambda Functions**
- Developed a Lambda function to serve as the backend logic for our CRUD operations. AWS Lambda allows you to run code without provisioning or managing servers. The function, written in Python, included logic to interact with DynamoDB for various operations like retrieving, inserting, updating, and deleting items.

**Day 3: Configuring API Endpoints**
- Set up API Gateway to expose our Lambda functions as RESTful API endpoints. Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. Configured the endpoints for the various CRUD operations.

**Day 4: Implementing CRUD Operations**
- **GET /items**: Configured the GET /items endpoint to retrieve all items from the DynamoDB table. This endpoint interacts with the Lambda function to fetch and return the list of items.
- **PUT /items**: Set up the PUT /items endpoint to add new items to the DynamoDB table. The Lambda function processes the incoming request and inserts the new item into the table.
- **GET /items/{id}**: Implemented the GET /items/{id} endpoint to retrieve a specific item by its ID. The Lambda function uses the ID parameter to query DynamoDB and return the requested item.
- **DELETE /items/{id}**: Configured the DELETE /items/{id} endpoint to remove an item from the DynamoDB table based on its ID. The Lambda function handles the deletion process and ensures the item is removed.
- **Configure API Endpoints with Lambda Code**: Linked the API Gateway endpoints with the corresponding Lambda functions. This integration allows API Gateway to invoke the correct Lambda function for each API request, ensuring the backend logic is executed properly.

**Day 5: Testing APIs**
- Tested the configured APIs using curl commands and a web browser to ensure they work as expected. Verified that the CRUD operations (Create, Read, Update, Delete) perform correctly and that the APIs return the appropriate responses for different scenarios.

## 4️⃣ Week 4
### 21st June 2024: Online Session: Introduction to AWS Bedrock, S3, and Knowledge Base Integration

This week focused on building a knowledge base using AWS Bedrock, creating a vector store for efficient data retrieval, and interacting with the knowledge base using an agent.

### Outline of Week 4
- **Create a Bucket**
- **Upload my Resume**
- **Create Knowledge Base in Bedrock**
- **Link S3 Bucket Object (Resume) with this Knowledge Base**
- **Create Vector Store using Embeddings and Data Source**
- **Test Knowledge Base using Generate Responses**
- **Test Knowledge Base without using Generate Responses**
- **Create an Agent**
- **Connect it with Knowledge Base**
- **Interact with your Resume**

### 📝 Day-by-Day Progress

**Day 1: Setting Up the S3 Bucket and Uploading Resume**
- **Create a Bucket**: Created a new S3 bucket for storing objects. Amazon S3 is a scalable object storage service that allows for the storage and retrieval of any amount of data at any time.
- **Upload my Resume**: Uploaded my resume to the S3 bucket. This step is crucial for linking the resume to the knowledge base in Bedrock.

**Day 2: Creating and Linking Knowledge Base in Bedrock**
- **Create Knowledge Base in Bedrock**: Created a knowledge base in AWS Bedrock, used for building intelligent applications with comprehensive knowledge management and natural language understanding capabilities.
- **Link S3 Bucket Object (Resume) with this Knowledge Base**: Linked the uploaded resume from the S3 bucket to the knowledge base, allowing Bedrock to use the resume as a data source for generating responses.

**Day 3: Building and Testing the Vector Store**
- **Create Vector Store using Embeddings and Data Source**: Created a vector store using embeddings to enable efficient data retrieval. This involved transforming the resume data into vector embeddings that Bedrock can use for quick search and retrieval.
- **Test Knowledge Base using Generate Responses**: Tested the knowledge base by generating responses from the linked resume data. This helped verify that the knowledge base correctly understands and retrieves information from the resume.
- **Test Knowledge Base without using Generate Responses**: Conducted tests on the knowledge base without using the generate response feature to ensure it can handle direct queries and return accurate information.

**Day 4: Creating and Connecting an Agent**
- **Create an Agent**: Created an agent in AWS Bedrock. Agents in Bedrock are responsible for interacting with users and providing responses based on the knowledge base.
- **Connect it with Knowledge Base**: Linked the created agent with the knowledge base to enable it to access and retrieve information from the resume stored in S3.

**Day 5: Interacting with the Resume**
- **Interact with your Resume**: Interacted with the resume through the agent, querying the agent to retrieve specific information from the resume, ensuring the setup was functional and effective.

### Problems Faced After Completion of Internship
After completing the internship on 30th June, I noticed that my billing charges were higher than expected. I contacted Amit Aurora sir, and we discovered that my Bedrock, KMS, and Agent Services were still active. We reached out to AWS support, explaining that we were students exploring the services and unintentionally went beyond our usage limits. Over several days, AWS support guided me to terminate the services, and by 15th July, the billing issue was resolved. Special thanks to AWS and Amit sir for their guidance.

## 🌟 Conclusion
This internship has provided valuable hands-on experience with various AWS services, enhancing my skills in cloud computing and serverless architecture. The project tasks helped me understand the practical applications of AWS and

 how to leverage its services to build scalable, secure, and efficient solutions.

![Conclusion](https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif)

