![alt text](<Screenshot 2026-04-21 at 3.56.00 PM.png>)

# Day 7: Change EC2 Instance Type

## Introduction

During the migration process, the Nautilus DevOps team created several EC2 instances in different regions. They are currently in the process of identifying the correct resources and utilization and are making continuous changes to ensure optimal resource utilization. Recently, they discovered that one of the EC2 instances was underutilized, prompting them to decide to change the instance type.

## The Task

Please make sure the **Status check** is completed (if its still in *Initializing* state) before making any changes to the instance.

1) Change the instance type from *t2.micro* to *t2.nano* for **devops-ec2** instance.

2) Make sure the ec2 instance **devops-ec2** is in *running* state after the change.

## Credentials

Use below given **AWS Credentials**: 

![alt text](<Screenshot 2026-04-21 at 3.45.02 PM.png>)

**Notes**:

Create the resources only in **us-east-1** region.

### Step 1 — LogIn Using Provided Credentials

![alt text](<Screenshot 2026-04-21 at 3.45.54 PM.png>)

### Step 2 — Verify location of Region

![alt text](<Screenshot 2026-04-21 at 3.46.31 PM.png>)

### Step 3 — Navigate to Instance Settings

In order to change the **devops-ec2**** Instance successfully, you must first click on EC2, then once in the EC2 settings, you can scroll down to Instances on the left hand side:

![alt text](<Screenshot 2026-04-21 at 3.47.23 PM.png>)

### Step 4 — Changing the Instance Type

Once in the Instance settings as shown in Step 3, first take note of the state **devops-ec2** instance. It is curently *Running*. 

In order to change the Instance type you must navigate to *Instnce Settings*, then click on *Change Instance Type*. As shown in the below screenshot, an instance type can not be changed while an Instance is running.

![alt text](<Screenshot 2026-04-21 at 3.52.02 PM.png>)

Change the Instance State from *Running* to *Stopped* by clicking on Actions, and then *Stop Instance*. 

![alt text](<Screenshot 2026-04-21 at 3.52.12 PM.png>)

As shown above, a Warning will appear. Click on *Stop* and wait about 2 minutes for the instance to complete it's *Stop* downtime. 

Once the Instance State is successfully stopped, the *Change Instance Type* setting becomes available, as shown below:

![alt text](<Screenshot 2026-04-21 at 3.53.18 PM.png>)

Change the Instance Type as required in the instructions (shown below), 

![alt text](<Screenshot 2026-04-21 at 3.54.06 PM.png>)

and then scroll down to the **Change Instance Type** button at the bottom. 

![alt text](<Screenshot 2026-04-21 at 3.54.20 PM.png>)

## Step 5 - Save Changes

Lastly, once you hit **Change Instance Type** as mentioned above in Step 4, you'll be able to verify that the changed instance shows up in the list of EC2 instances, as shown below:

![alt text](<Screenshot 2026-04-21 at 3.55.08 PM.png>)

**Note**: If the Instance State isn't *Running*, click on *Action*, then *Start Instamce* to restart the instance and the Instance State will change after about 1 minute. 