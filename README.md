# aws-s3-bucket-creation

## Project Overview
This project demonstrates the step-by-step process of creating an S3 bucket using the AWS Management Console.

Amazon S3 (Simple Storage Service) is an object storage service provided by Amazon Web Services (AWS) that offers scalable, highly available, and secure storage for data such as files, images, backups, and logs.

---

## Prerequisites

Before creating an S3 bucket, ensure the following:

- AWS account
- Access to AWS Management Console
- Basic knowledge of AWS services
- Internet connection

---

## Steps to Create an S3 Bucket

### Step 1: Login to AWS Console
1. Open the AWS Management Console.
2. Enter your username and password.
3. Navigate to the Services menu.

---

### Step 2: Open Amazon S3 Service
1. In the search bar, type **S3**.
2. Click on **Amazon S3**.
3. The S3 dashboard will open.

---

### Step 3: Click Create Bucket
1. On the S3 dashboard, click the **Create bucket** button.
2. This will open the bucket configuration page.

---

### Step 4: Configure Bucket Name

Rules for bucket naming:

- Bucket name must be globally unique.
- Use only lowercase letters, numbers, and hyphens.
- No spaces allowed.

Example:

my-s3-demo-bucket-2026

---

### Step 5: Select AWS Region

Choose the region closest to your application.

Example:

Asia Pacific (Mumbai) – ap-south-1

---

### Step 6: Configure Object Ownership

Select the recommended option:

ACLs Disabled (Bucket owner enforced)

Benefits:
- Simplified access management
- Improved security

---

### Step 7: Block Public Access

Enable all **Block Public Access** settings to prevent public access to your bucket.

Recommended configuration:
- Block public access to buckets and objects
- Block public access via ACLs
- Block public access via bucket policies

---

### Step 8: Enable Versioning (Optional)

Versioning allows you to store multiple versions of an object.

Example:

file_v1.txt  
file_v2.txt  
file_v3.txt  

Benefits:
- Prevent accidental deletion
- Recover previous versions

---

### Step 9: Enable Encryption

Enable server-side encryption for data protection.

Recommended option:

Server-side encryption using SSE-S3 (Amazon managed keys)

Alternative option:

SSE-KMS (AWS Key Management Service)

---

### Step 10: Create the Bucket

After reviewing all configurations:

Click **Create Bucket**

Your S3 bucket will be created successfully.

---

## Upload Files to the Bucket

1. Open the created bucket.
2. Click **Upload**.
3. Select files from your system.
4. Click **Upload**.

The files will be stored as objects in the bucket.

---

## S3 Key Concepts

Bucket  
A container used to store objects.

Object  
A file stored in an S3 bucket.

Key  
A unique identifier for an object inside a bucket.

Example path:

bucket-name/folder/file.txt

---

## Repository Structure

aws-s3-bucket-creation
│
├── README.md
├── S3-bucket-creation.docx
└── screenshots
    ├── step1-login.png
    ├── step2-s3-dashboard.png
    ├── step3-create-bucket.png
    └── step4-upload-file.png

---

## Use Cases of Amazon S3

- Application data storage
- Database backups
- Static website hosting
- Log storage
- Data archiving

---

## Conclusion

Amazon S3 provides a reliable, scalable, and secure object storage solution widely used in cloud architectures for storing and retrieving data from anywhere.
