<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Access S3 from a VPC

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-s3)

**Author:** PATRICK ADDAI  
**Email:** patrickaddai1689@gmail.com

---

## Access S3 from a VPC

![Image](http://learn.nextwork.org/refreshed_amber_shy_cantaloupe/uploads/aws-networks-s3_3e1e79a2)

---

## Introducing Today's Project!

### What is Amazon VPC?

Amazon VPC is AWS's foundational networking service that allow us to create our own isolated networks with an AWS region and control network traffic and security etc.

### How I used Amazon VPC in this project

I launched a VPC with a public subnet and EC2 instance, and directly accessed/managed an Amazon S3 bucket through the EC2 instance using AWs CLI.

### One thing I didn't expect in this project was...

I didn't expect that access keys are require for EC2 instances/other applications to get access to my AWS environment.

### This project took me...

This project took me 90 mins including practical time.

---

## In the first part of my project...

### Step 1 - Architecture set up

In this step, I launch a VPC with a public subnet. I also launch an EC2 instance inside that public subnet.

### Step 2 - Connect to my EC2 instance

In this step I dorectly access an EC2 instance using EC2 instance connect.

