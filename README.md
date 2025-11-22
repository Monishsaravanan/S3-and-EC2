# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

# Name: MONISH S
# Register Number: 212223040115

# Aim: To understand and implement basic cloud operations in Amazon Web Services (AWS) by:
Creating a secure and scalable cloud storage system using Amazon S3, and
Launching and configuring a virtual server using Amazon EC2.

# Procedure:
Launching an EC2 Instance in AWS
Step 1: Login

Open AWS Console.

Sign in to your AWS account.

Step 2: Open EC2 Dashboard

Search for EC2 in the services search bar.

Click EC2 Dashboard.

Step 3: Create a New Instance

Click Launch Instance.

Step 4: Choose AMI

Select the provided AMI (usually Amazon Linux 2 AMI or Ubuntu).

Step 5: Choose Instance Type

Select t2.micro (free-tier eligible).

Step 6: Configure Instance Settings

Keep default settings unless lab instructions mention changes.

Choose a VPC and subnet if required.

Leave IAM role as default unless instructed.

Step 7: Add Storage

Keep the default EBS storage (usually 8GB).

Step 8: Configure Security Group

Add a rule:

SSH → Port 22 → Source: My IP

Additional rules only if the lab requires (e.g., HTTP 80).

Step 9: Create/Use Key Pair

If prompted, create new key pair → download .pem file.

Or select an existing key pair (in labs, Coursera may preconfigure this).

Step 10: Launch

Click Launch Instance.

Wait until instance state becomes Running.

# Output:
<img width="1918" height="1078" alt="ec2" src="https://github.com/user-attachments/assets/ff9d353f-0271-4d95-a3a0-020b5c61a884" />

# Result:
Launching an EC2  instance is successfully done

# Creating an s3 bucket
# Procedure:
Step 1: Open S3 Console

In AWS search bar → type S3 → open S3 dashboard.

Step 2: Create Bucket

Click Create Bucket.

Step 3: Enter Bucket Name

Enter a globally unique bucket name.

Step 4: Choose AWS Region

Select the same region as your EC2 instance (recommended).

Step 5: Configure Bucket Settings

Keep defaults unless lab requires changes:

Uncheck Block all public access only if labs need public access.

Versioning (enable/disable as per lab).

Encryption (AES-256 usually default).

Step 6: Bucket Creation

Scroll down → click Create Bucket.

# Output:
<img width="1918" height="1078" alt="s3" src="https://github.com/user-attachments/assets/018b23f8-d86b-4428-8e65-0c58c39079ed" />

# Result:
Creating an s3 bucket is done successfully.


