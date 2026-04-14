![alt text](<Screenshot 2026-04-14 at 12.08.50 PM.png>)

# Day 4: Enable Versioning for S3 Bucket

## Introduction

Data protection and recovery are fundamental aspects of data management. It's essential to have systems in place to ensure that data can be recovered in case of accidental deletion or corruption. The DevOps team has received a requirement for implementing such measures for one of the S3 buckets they are managing.

The s3 bucket name is **nautilus-s3-21802**, enable **versioning** for this bucket.

## The Task

The s3 bucket name is **nautilus-s3-21802**, enable **versioning** for this bucket.

## Credentials

Use below given **AWS Credentials**: 

![alt text](<Screenshot 2026-04-14 at 11.27.21 AM.png>)

**Notes**:

Create the resources only in **us-east-1** region.

### Step 1 — LogIn Using Provided Credentials

![alt text](<Screenshot 2026-04-14 at 11.28.53 AM.png>)

### Step 2 — Verify location of Region

![alt text](<Screenshot 2026-04-13 at 12.10.25 PM-1.png>)

### Step 3 — Navigate to S3 bucket Settings

In order to create enable **versioning** within the designated S3 bucket, you have to navigate to the S3 settings as shown below:

![alt text](<Screenshot 2026-04-14 at 11.52.45 AM.png>)

### Step 4 — Enabling Versioning

![alt text](<Screenshot 2026-04-14 at 12.06.26 PM.png>)

After clicking on the chosen bucket,, the user must navigate to the Properties settings within that bucket to enable versioning.

By default, versioning within the chosen bucket, as shown above, is set to Disabled.

Click on Edit to toggle the setting to Enable. 

![alt text](<Screenshot 2026-04-14 at 12.06.48 PM.png>)

## Step 5 - Save Changes

Lastly, click on **Save changes** and successfully complete the day's challenge as shown below:

![alt text](<Screenshot 2026-04-14 at 12.07.05 PM.png>)