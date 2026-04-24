![alt text](<Screenshot 2026-04-22 at 1.54.36 PM.png>)

# Day 8: Enable Stop Protection for EC2 Instance

## Introduction

As part of the migration, there were some components added to the AWS account. Team created one of the EC2 instances where they need to make some changes now.

## The Task

There is an EC2 instance named **datacenter-ec2** under **us-east-1** region, enable the stop protection for this instance.

## Credentials

Use below given **AWS Credentials**: 

![alt text](<Screenshot 2026-04-22 at 1.26.51 PM.png>)

**Notes**:

Create the resources only in **us-east-1** region.

### Step 1 — LogIn Using Provided Credentials

![alt text](<Screenshot 2026-04-22 at 1.30.54 PM.png>)

### Step 2 — Verify location of Region

![alt text](<Verify AWS Region.png>)

### Step 3 — Navigate to Instance Settings

The task is to enable Stop Protection on the existing EC2 instance. First step is to navigate to the Instance settigns which can be found under the EC2 settings, shown below:

![alt text](<Screenshot 2026-04-22 at 1.51.34 PM.png>)

Once there, click on Instances in the left hand side menu:

![alt text](<Screenshot 2026-04-22 at 1.51.42 PM.png>)

### Step 4 — Changing the Stop Protection Setting

To *Enable* Stop Protection on the Instance, you must first click on *Actions*, then *Instance Settings*, followed by *Change Stop Protection* as shown in the below screenshot:

![alt text](<Screenshot 2026-04-22 at 1.52.01 PM.png>)

Once you click on *Change Stop Protection*, a box appears with the Enable box as unchecked by default. Check the box and then click **Save**.

![alt text](<Screenshot 2026-04-22 at 1.52.08 PM.png>)

### Step 5 — Save Changes 

Once asved, you will get a green banner oon the Insance page showing that *Enable Stop Protection* has been activated as shown below: 

![alt text](<Screenshot 2026-04-22 at 1.52.57 PM.png>)