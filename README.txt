SIMPLE EC2 WITH CLOUDFORMATION: 

{ This project contains a basic AWS CloudFormation template that provisions a single Amazon EC2 instance using the latest Amazon Linux 2023 AMI. 
  Instead of hardcoding an AMI ID, the template dynamically retrieves the latest AWS-managed Amazon Linux image through AWS Systems Manager (SSM) Parameter Store, 
  making the template reusable and region-aware.

  RESOURCES CREATED : 
  AWS::EC2::Instance

  DEPLOYMENT : 
  Open the AWS CloudFormation Console.
  Create a new stack.
  Upload the Simple_EC2_CF.yaml template.
  Review the stack configuration.
  Create the stack and check the deployment }

