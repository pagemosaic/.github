# Welcome to Page Mosaic!

Page Mosaic CMS is an open-source platform optimized for AWS to efficiently host static websites. 
It simplifies the process of creating, managing, and publishing content online with an emphasis on cost-effectiveness and efficient use of AWS resources.

[The source code](https://github.com/pagemosaic/pagemosaic-cms)

## Key Features
### Core Functionality
Designed for ease of use, Page Mosaic enables users to host static websites on AWS, leveraging AWS services such as S3 for file storage (images, videos, etc.) and CloudFront for content delivery network (CDN) capabilities. 
It incorporates free SSL for secure connections, provided by AWS, ensuring that custom domains are both secure and easy to set up.
### Admin Panel
The heart of the CMS is its admin panel, accessible directly via /admin on a user’s browser. This interface allows users to upload and manage files on AWS S3, edit website content in real-time, and configure custom domains. 
It supports immediate HTML page previews during editing and enables direct modifications of HTML, CSS, and JavaScript within the panel itself.
### Content Editing 
Page Mosaic offers a dynamic approach to content management. 
Users can modify website pages using input forms that feature a variety of elements, arranged into manageable blocks. 
These forms are highly configurable, allowing users to specify labels, input types, and other settings. 
The input data integrates seamlessly with HTML templates through Liquid JS syntax, akin to static site generators like Hugo or Jekyll, facilitating the injection of data into templates.
### Static Site Generation 
An embedded generator within the admin panel automatically produces and publishes HTML, CSS, and other static files to the AWS CDN. 
This process includes the creation of essential service files such as sitemap.xml and robots.txt.
### Deployment and Customization 
The system is designed for deployment on a user's AWS account using the AWS Cloud Development Kit (CDK) for resource creation. 
This setup process requires just a single CLI command, making it straightforward to get started. 
Users can create unlimited pages, select HTML templates, and add data effortlessly, allowing for extensive customization and scalability.
### Cost and Efficiency
Page Mosaic prioritizes cost-effectiveness and the efficient use of AWS resources. 
Users pay only for the resources they consume, with the CMS architecture designed to optimize these costs.

## Technical Overview
### AWS-Based Serverless Architecture
* `Hosted on AWS:` Utilizing Amazon Web Services for reliable, scalable cloud infrastructure.
* `Serverless Design:` Employs AWS services like Lambda, CloudFront, and S3 to create a serverless architecture, optimizing for efficiency and scalability.

### Key AWS Services
* `AWS Lambda:` Manages backend processes without dedicated servers, triggering functions as needed.
* `Amazon CloudFront:` Acts as the content delivery network, enhancing global content delivery speed and security.
* `Amazon S3:` Used for secure and scalable storage of files and data.

### Deployment
* `AWS Cloud Development Kit (CDK):` Infrastructure defined and deployed using CDK, simplifying the deployment process through Command Line Interface (CLI), even for users with minimal technical background.

### Admin Panel
* `Technologies Used:` Developed with React and TailwindCSS. React for building the user interface, TailwindCSS for styling.
* `User Interface Components:` Includes various components for managing system features and AWS resources.

---

Follow [Alex Pust](https://twitter.com/alex_pustovalov) on Twitter for updates on the Page Mosaic CMS development.

---
