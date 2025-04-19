# Event-Driven-Architecture
# Project Description:
Let's build a simple event-driven application using AWS services like Amazon S3, AWS Lambda, and Amazon SNS (Simple Notification Service).

Use Case: Image Upload Notification System
When an image is uploaded to an S3 bucket, a Lambda function processes the event and sends a notification through SNS.
# Project Architecture:
![image](https://github.com/user-attachments/assets/34d5fd36-908c-4d15-8890-dc217cd30c9d)
# Steps to Build the Project:
# Step 1: Set Up an AWS Account
# Step 2: Create an S3 Bucket (S3 Bucket Name: eda-aws-p2)

#![Screenshot (6)](https://github.com/user-attachments/assets/32dfa136-dd5b-4db0-b274-4a14dd4bf70b)
# Step 3: Create an SNS Topic (SNS Topic Name: eda-p2)
![Screenshot (7)](https://github.com/user-attachments/assets/639e635a-a7aa-4101-9da9-eb6f23c4870b)

# Step 4: Create a Subscription 
![Screenshot (2)](https://github.com/user-attachments/assets/a083e7e9-722d-4a75-a7a1-c3e0ee432413)

# Step 5: Create a Lambda Function (Lambda Function Name: eda-aws)
![Screenshot (9)](https://github.com/user-attachments/assets/db8cbddb-3ed4-4c5f-974c-1ebe252a99ca)

# Step 6: Add S3 trigger
![Screenshot (10)](https://github.com/user-attachments/assets/62d56031-d605-4434-8440-6b25594ef049)

# Step 7: Write Lambda Function Code
![Screenshot (11)](https://github.com/user-attachments/assets/73cda1ab-e6e9-446d-b6de-5eb0f414af58)

# Expected Outcome:
# you will get notify whenever image is uploaded.and from following these steps, you will have created a simple event-driven application on AWS that demonstrates the core principles of EDA.

![Screenshot (5)](https://github.com/user-attachments/assets/a46224cd-c530-4e1b-ba22-e6b36bb4b1fb)






