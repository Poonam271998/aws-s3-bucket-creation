# AWS S3 Bucket Creation Project

![AWS](https://img.shields.io/badge/AWS-S3-orange)
![Cloud](https://img.shields.io/badge/Cloud-Storage-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
---
## Project Overview

This project demonstrates the **step-by-step process of creating an Amazon S3 bucket using the AWS Management Console**.

Amazon S3 (Simple Storage Service) is an object storage service that offers industry-leading scalability, data availability, security, and performance.

---
## Objectives

The main objectives of this project are:

- Understand Amazon S3 storage service
- Create an S3 bucket
- Configure bucket settings
- Upload and manage files in the bucket

---
## Prerequisites

Before performing this project ensure the following:

- AWS Account
- Access to AWS Management Console
- Basic understanding of AWS services
- IAM permissions to create S3 resources

---
## Architecture

```
User
  │
  ▼
AWS Management Console
  │
  ▼
Amazon S3 Service
  │
  ▼
S3 Bucket
  │
  ▼
Objects (Files / Images / Backups)
```

---

## Steps to Create S3 Bucket

### Step 1: Login to AWS Console

1. Open AWS Management Console  
2. Enter login credentials  
3. Click **Sign In**

---

### Step 2: Open Amazon S3 Service

1. In the AWS search bar type **S3**
2. Click **Amazon S3**
3. S3 dashboard will open

---

### Step 3: Create Bucket

1. Click **Create Bucket**
2. Enter bucket details

---

### Step 4: Configure Bucket Name

Provide a unique bucket name.

Example:

```
my-s3-demo-bucket
```

Bucket naming rules:

- Must be globally unique
- Use lowercase letters
- No spaces allowed

---

### Step 5: Select AWS Region

Choose the AWS region closest to your application.

Example:

```
Asia Pacific (Mumbai) – ap-south-1
```

---

### Step 6: Configure Bucket Settings

Configure the following options:

Object Ownership
```
ACLs Disabled (Recommended)
```

Block Public Access
```
Enable all block public access settings
```

Versioning
```
Optional
```

Encryption
```
Server-side encryption (SSE-S3)
```

---

### Step 7: Create Bucket

After reviewing configuration:

Click **Create Bucket**

The bucket will be created successfully.

---

### Step 8: Upload Files to Bucket

1. Open the created bucket
2. Click **Upload**
3. Select files
4. Click **Upload**

Files will be stored as **objects** in the S3 bucket.

---

## S3 Key Concepts

### Bucket
A container used to store objects in Amazon S3.

### Object
A file stored inside an S3 bucket.

### Key
Unique identifier used to access objects inside a bucket.

Example:

```
bucket-name/folder/file.txt
```

---

## Benefits of Amazon S3

- Highly scalable storage
- Durable and secure data storage
- Easy integration with other AWS services
- Pay-as-you-go pricing model

---

## Use Cases

Amazon S3 is commonly used for:

- Application file storage
- Database backups
- Static website hosting
- Log storage
- Data archiving

---

## Repository Structure

```
aws-s3-bucket-creation
│
├── README.md
└── project-documentation
```

---
## Author

Your Name

---
## Project Status

Completed
