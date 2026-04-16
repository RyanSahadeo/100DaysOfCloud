![alt text](<Screenshot 2026-04-16 at 5.32.41 PM.png>)

# Day 6: Launch EC2 Instance

## Introduction

The Nautilus DevOps team is strategizing the migration of a portion of their infrastructure to the AWS cloud. Recognizing the scale of this undertaking, they have opted to approach the migration in incremental steps rather than as a single massive transition. To achieve this, they have segmented large tasks into smaller, more manageable units.

## The Task

For this task, create an EC2 instance with following requirements:

1) The name of the instance must be **xfusion-ec2**.

2) You can use the **Amazon Linux** AMI to launch this instance.

3) The Instance type must be **t2.micro**.

4) Create a new RSA key pair named **xfusion-kp**.

5) Attach the default (available by default) security group.

## Credentials

Use below given **AWS Credentials**: 

![alt text](<Screenshot 2026-04-16 at 4.02.39 PM.png>)

**Notes**:

Create the resources only in **us-east-1** region.

### Step 1 — LogIn Using Provided Credentials

![alt text](<Screenshot 2026-04-16 at 4.06.15 PM.png>)

### Step 2 — Verify location of Region

![alt text](<Screenshot 2026-04-13 at 12.10.25 PM-1.png>)

### Step 3 — Navigate to Instance Settings

Om order to create the new Instance successfully, you must first click on EC2, after which there are two ways to create an instance as shown below:

![alt text](<Screenshot 2026-04-16 at 5.26.19 PM.png>)

Once in the EC2 settings, you can scroll down to Instances on the left hand side or **Launch Instance** show below:

![alt text](<Screenshot 2026-04-16 at 5.28.14 PM.png>)

### Step 4 — Creating new RSA Pair

Once you update the Instance settings as required in Step 3, you now need to create teh RSA pair bbefore you can finish the task. 

Click on *Create New key pair* and enter all details as required:

![alt text](<Screenshot 2026-04-16 at 5.29.29 PM.png>)

![alt text](<Screenshot 2026-04-16 at 5.29.42 PM.png>)

Click on *Create new pair* once all information has been entered, to go back to the previous Instance screen.

Click on *Create new instance* to set up the new EC2 instance. 

## Step 5 - Save Changes

Lastly, once you hit **Save Changes**, you'll be able to verify that the new instance shows up in the list of EC2 instances, as shown below:

![alt text](<Screenshot 2026-04-16 at 5.30.41 PM.png>)