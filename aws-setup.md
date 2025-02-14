Steps to Create an AWS Account:
Visit the AWS Website:

Go to aws.amazon.com.
Sign Up for AWS:

Click on the "Create an AWS Account" button.
Enter your email address and accept the terms and conditions.
Provide your personal details including payment information.
Verify Your Account:

Follow the verification steps, which may include receiving an SMS or a phone call.
Select an AWS Support Plan:

Choose a support plan that suits your needs (basic support is free).
Steps to Set Up a Basic EC2 Instance:
Log In to the AWS Management Console:

Navigate to the AWS Management Console and log in with your new credentials.
Navigate to EC2 Dashboard:

In the AWS Management Console, find and select the EC2 service.
Launch an Instance:

Click on "Launch Instance".
Choose an Amazon Machine Image (AMI):

Select an AMI, such as the Amazon Linux 2 AMI.
Choose an Instance Type:

Select a suitable instance type like t2.micro (eligible for free tier).
Configure Instance Details:

Configure the instance details as needed. For a basic setup, default settings will suffice.
Set the number of instances to 1.
Add Storage:

Specify any additional storage if needed.
Add Tags:

Create a tag with Key: Name and Value: MyFirstInstance (for easy identification).
Configure Security Group:

Create a new security group or select an existing one.
Add rules to allow SSH (port 22), HTTP (port 80), and any other required ports.
Review and Launch:

Review the settings and launch the instance.
You will be prompted to create a new key pair or use an existing one. Download the key pair (.pem file) and keep it secure.
Steps to Deploy a Sample Python Script:
Connect to Your EC2 Instance:

Use SSH to connect to your EC2 instance. On your local machine, run:
ssh -i /path/to/your-key-pair.pem ec2-user@your-instance-public-dns
Install Required Packages:

Install Python if it is not already installed. You can also install pip and any libraries needed (e.g., boto3 if using AWS SDK).
Create the Python Script:

Use a text editor like nano to create the Python script. For example:
nano add_two_numbers.py
Write the script to add two numbers and save the file.
Run the Script:

Execute the script using Python. For example:
python add_two_numbers.py
Additional Considerations:
Security: Make sure your EC2 instance is secure. Restrict access to your instance by modifying the security group rules appropriately.
Cost Management: Monitor your AWS usage to avoid unexpected charges, especially if you exceed the free tier limits.
Termination: When you are done, make sure to terminate the EC2 instance to stop incurring charges.
By following these steps, you will be able to create an AWS account, set up an EC2 instance, and deploy a basic Python script successfully.


