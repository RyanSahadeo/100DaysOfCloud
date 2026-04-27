![alt text](<Screenshot 2026-04-24 at 12.12.47 PM.png>)

# Day 9: Enable Termination Protection for EC2 Instance

## Introduction

As part of the migration, there were some components created under the AWS account. The Nautilus DevOps team created one EC2 instance where they forgot to enable the termination protection which is needed for this instance.

## The Task

An instance named **datacenter-ec2** already exists in **us-east-1** region. Enable termination protection for the same.

## Credentials

Use below given **AWS Credentials**: 

![alt text](<Screenshot 2026-04-24 at 9.44.25 AM-1.png>)

**Notes**:

Create the resources only in **us-east-1** region.

### Step 1 — LogIn Using Provided Credentials

![alt text](<Screenshot 2026-04-24 at 9.46.58 AM.png>)

### Step 2 — Verify location of Region

![alt text](<Verify AWS Region.png>)

### Step 3 — Navigate to Instance Settings

The task is to enable Terminate Protection on the existing EC2 instance. First step is to navigate to the Instance settigns which can be found under the EC2 settings, shown below:

![alt text](<Screenshot 2026-04-22 at 1.51.34 PM.png>)

Once there, click on Instances in the left hand side menu, which will bring up the instance shown below:

![alt text](<Screenshot 2026-04-24 at 9.47.46 AM.png>)

### Step 4 — Enable the Terminate Protection

To *Enable* Terminate Protection on the Instance, you must first click on *Actions*, then *Instance Settings*, followed by *Change Stop Protection* as shown in the below screenshot:

![alt text](<Screenshot 2026-04-24 at 9.48.33 AM.png>)

Once you click on *Change Terminate Protection*, a box appears with the Enable box as unchecked by default. Check the box and then click **Save**.

![alt text](<Screenshot 2026-04-24 at 9.48.42 AM.png>)

### Step 5 — Save Changes 

Once asved, you will get a green banner oon the Insance page showing that *Enable Stop Protection* has been activated as shown below: 

![alt text](<Screenshot 2026-04-24 at 9.48.54 AM.png>)

To test that the Terminate Protection is in place, you can go to *Instance State* and click on *Terminate Instance* as shown below:

![alt text](<Screenshot 2026-04-24 at 9.49.07 AM.png>) 

A pop up Warning box appears appears, as shown below: 

![alt text](<Screenshot 2026-04-24 at 9.49.15 AM.png>) 

Click on *Terminate (delete)*, and when the window refreshes the Instance list, the red notification banner appears above the list, (*as shown below*): 

![alt text](<Screenshot 2026-04-24 at 9.49.32 AM.png>)