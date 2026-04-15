![alt text](<Screenshot 2026-04-15 at 11.38.37 AM.png>)

# Day 5: Create GP3 Volume

## Introduction

The Nautilus DevOps team is strategizing the migration of a portion of their infrastructure to the AWS cloud. Recognizing the scale of this undertaking, they have opted to approach the migration in incremental steps rather than as a single massive transition. To achieve this, they have segmented large tasks into smaller, more manageable units. This granular approach enables the team to execute the migration in gradual phases, ensuring smoother implementation and minimizing disruption to ongoing operations. By breaking down the migration into smaller tasks, the Nautilus DevOps team can systematically progress through each stage, allowing for better control, risk mitigation, and optimization of resources throughout the migration process.

## The Task

Create a volume with the following requirements:

- Name of the volume should be xfusion-volume.

- Volume type must be gp3.

- Volume size must be 2 GiB.

## Credentials

Use below given **AWS Credentials**: 

![alt text](<Screenshot 2026-04-15 at 11.16.35 AM.png>)

**Notes**:

Create the resources only in **us-east-1** region.

### Step 1 — LogIn Using Provided Credentials

![alt text](<Screenshot 2026-04-15 at 11.17.49 AM.png>)

### Step 2 — Verify location of Region

![alt text](<Screenshot 2026-04-13 at 12.10.25 PM-1.png>)

### Step 3 — Navigate to Volume Settings

Om order to create the new volume successfully, you must first navigate to the Volume settings which are under the EC2 settings as shown below:

![alt text](<Screenshot 2026-04-15 at 11.34.00 AM.png>)

Once in the EC2 settings, you need to scroll down to Volumes under the **Elastic Block Store** section on the left as shown below:

![alt text](<Screenshot 2026-04-15 at 11.34.18 AM.png>)

### Step 4 — Creating the Volume

When you are in the Volume settings, by default there are none listed. In order to create a Volume, you must first click on Create Volume on the right side as shown below:

![alt text](<Screenshot 2026-04-15 at 11.34.35 AM.png>)

Enter the provided settings as provided above: 

![alt text](<Screenshot 2026-04-15 at 11.36.07 AM.png>)

![alt text](<Screenshot 2026-04-15 at 11.36.18 AM.png>) 

Once you hit **Save Changes**, you'll notice the name of the Volume is blank. In order to edit it, you need to click on the pencil icon under the *Name* field.

![alt text](<Screenshot 2026-04-15 at 11.36.41 AM.png>)

## Step 5 - Editing the Name and Save Changes

Lastly, edit the *Name* field to the required setting as mentioned above, and then click on the *Check Mark* to save. Hit the Refresh button to reflect the changes made.

![alt text](<Screenshot 2026-04-15 at 11.37.15 AM.png>)