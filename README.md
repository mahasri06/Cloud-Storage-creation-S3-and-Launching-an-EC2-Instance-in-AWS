## Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS

Name : Beatrice Thomas <br>
Register Number: 212223110005

## Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 

## Procedure
a)	Steps to Create a first S3 Bucket: <br> <br> 
Step 1: Sign in to the AWS Management Console <br>
Go to https://console.aws.amazon.com/s3. <br> <br> 
Step 2: Open the S3 Service <br>
In the console, type S3 in the search bar and select S3 to open the service dashboard. <br> <br> 
Step 3: Create Bucket <br> 
Click the Create bucket button. <br> <br> 
Step 4: Configure Bucket Settings <br> 
•	Bucket name: Choose a globally unique name. <br>
•	AWS Region: Select the region where you want to store your data. <br> <br> 
Step 5: Object Ownership <br> 
Choose between: <br>
	ACLs disabled (recommended) – Bucket owner has full control. <br>
	ACLs enabled – Control access via access control lists. <br> <br> 
Step 6: Block Public Access Settings <br> 
By default, all public access is blocked. Leave it as-is unless you need public access. <br> <br> 
Step 7: Bucket Versioning (optional) <br>
Choose whether to enable versioning for objects in the bucket. <br> <br> 
Step 8: Encryption (optional) 
Select encryption options (SSE-S3, SSE-KMS, or none). <br> <br> 
Step 9: Advanced Settings (optional) <br>
Add tags, configure logging, etc. <br> <br> 
Step 10: Create the Bucket <br>
Click Create bucket at the bottom of the page. <br>  <br>  
b)	i. Steps to launch an EC2 Instance <br>
1.	Go to the EC2 Dashboard in AWS Console. <br> 
2.	Click on “Launch Instance”. <br>
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux). <br>
4.	Select an instance type (e.g., t2.micro for Free Tier). <br>
5.	Create or choose a key pair for SSH access. <br>
6.	Configure network settings (use default VPC/subnet). <br>
7.	Configure storage (default root volume is fine). <br>
8.	Review the settings and click “Launch Instance”. <br>
9.	Wait for the instance to enter the running state. <br>
<br> 
c)	Step 3: Connect to Your Instance <br>
•	Linux: Use SSH command with your .pem key. <br>
•	Windows: Use RDP with decrypted admin password. <br>
<br> 
d)	Steps to Clean Up (Terminate the Instance) <br>
1.	Go to EC2 Instances. <br>
2.	Select your instance → Instance State → Terminate. <br>


## Output 

Snap Shot 1: Simple Storage Service (S3)
 <img width="1004" height="539" alt="image" src="https://github.com/user-attachments/assets/0b9991b1-3d39-40e5-b7b9-f2d320762a80" />


Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance

<img width="981" height="583" alt="image" src="https://github.com/user-attachments/assets/2d8fab35-6b9c-40a2-9044-8feb871f3a6f" />


























Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
