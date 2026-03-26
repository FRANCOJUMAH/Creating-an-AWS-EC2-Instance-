# Introduction to Cloud Computing Training / Mentorship - Ajira Digital


## 🎯 Task Overview

![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/7f19c7ebde1540ea02377bb90e4616605f546a7e/resources/ec2.png)

- **Create an EC2 (Elastic Compute Cloud) Instance on AWS**

## 📝 Steps for Creating an Amazon EC2 Instance

1. **Login into your AWS account**
   - Log in to the AWS Management Console (https://signin.aws.amazon.com/), if you don't have one - you will be prompted to sign up.
   - You can either sign in as the root user or an IAM User depending on your preferrence.
   - Enter you email and password then validate the MFA (Multifactor Authentication)
![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/2efa99f82ef7d9d4d59a3921a3ef55a47846d58a/resources/Login.png)


2. **Navigate to Console Home**
   - After successful login. Go to console home where you get to see different AWS resources listed : VPC, IAM, EC2, RDS as shown in the image below
   - In this case, we are interested with EC2 only. Click on EC2
![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/2efa99f82ef7d9d4d59a3921a3ef55a47846d58a/resources/Console.png)

3. **Launch Instance**
   - Here you get to see if there are any running instances, key pairs, security groups, load balancers, Auto Scaling groups etc. 
   - Click on launch instance to create a new EC2 instance.
![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/2efa99f82ef7d9d4d59a3921a3ef55a47846d58a/resources/Launch.png)

3. **Specify Instance name & type, AMI Image, Keypair**
   - Here you get to see if there are any running instances, key pairs, security groups, load balancers, Auto Scaling groups etc. 
   - Click on launch instance to create a new EC2 instance.

![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/7c8970fbcdc6c61be51fe14cbfec0fdecee33a96/resources/Specify.png)

 - In this case Instance name is Shujaa server, Amazon Linux as the AMI, instance type t3.micro, key pair - shujaa, set the instance to create a new security group during creation, allow SSH connection to the instance from anywhere (Note: Not a good security practice for your cloud resources). With all these parameters set, you can now go ahead to launch your instance

 ![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/b1490931573c970e9e3d233946101c9063449049/resources/instance%20name.png)

 ![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/b1490931573c970e9e3d233946101c9063449049/resources/instance%20type.png)

  ![image](https://github.com/FRANCOJUMAH/Creating-an-AWS-EC2-Instance-/blob/b1490931573c970e9e3d233946101c9063449049/resources/security%20group.png)
