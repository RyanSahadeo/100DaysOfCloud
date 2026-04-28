![alt text](<Screenshot 2026-04-28 at 1.22.39 PM.png>)

# Day 10: Attach Elastic IP to EC2 Instance

## Introduction

The Nautilus DevOps team has been creating a couple of services on AWS cloud. They have been breaking down the migration into smaller tasks, allowing for better control, risk mitigation, and optimization of resources throughout the migration process. Recently they came up with requirements mentioned below.

## The Task

There is an instance named **devops-ec2** and an elastic-ip named **devops-ec2-eip** in **us-east-1** region. Attach the **devops-ec2-eip** elastic-ip to the **devops-ec2** instance.

## Credentials

Use below given **AWS Credentials**: 

![alt text](<Screenshot 2026-04-28 at 12.35.38 PM.png>)

**Notes**:

Create the resources only in **us-east-1** region.

### Step 1 — LogIn Using Provided Credentials

![alt text](<Screenshot 2026-04-28 at 12.35.09 PM.png>)

### Step 2 — Verify location of Region

![alt text](<Verify AWS Region.png>)

### Step 3 — Navigate to Elastic IP Settings

The task is to attach the existing elastic IP to the existing EC2 instance. First step is to navigate to the Elastic IP settigns which can be found under the EC2 settings, shown below:

![alt text](<Screenshot 2026-04-28 at 12.40.44 PM.png>)

Once there, click on Elastic IPs in the middle, which will bring up the list of elastic IPs shown below:



### Step 4 — Attach the Elastic IP

To attach the elastic IP to the Instance, you must first click on *Actions*, then *Associate Elastic IP Address*, followed by as shown in the below screenshot:

![alt text](<Screenshot 2026-04-28 at 12.58.18 PM.png>)

Once you click on *Associate Elastic IP Address*, a box appears with the settings to be entered by default. Click into each field to select the default settings and then click **Associate**.

![alt text](<Screenshot 2026-04-28 at 12.58.28 PM.png>)

![alt text](<Screenshot 2026-04-28 at 12.58.38 PM.png>)

### Step 5 — Save Changes 

Once associated, you will get the green banner shown below as proof of a successful association:

![alt text](<Screenshot 2026-04-28 at 12.59.07 PM.png>)

Lastly, the Elastic IP does not show up right away, so you will need to refresh the list of Instances, then the Elastic IP will show up as shown below:

![alt text](<Screenshot 2026-04-28 at 12.59.29 PM.png>)