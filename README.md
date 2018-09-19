# Creates-SG-and-EC2-ansible
Create security group and EC2 instance

Step 1   First create AWS user and assing Access key ID and secret access key

Step 2   Install AWS CLI 
Use https://docs.aws.amazon.com/cli/latest/userguide/installing.html

Step 3   Create Security Group
  - specify a region
  - name
  - VPC's id
  - rules: ports you want to open

Step 4 Create new key pair
  - specify a name
  - specify a region  
  
Step 5 Save a private key to your ansible master
  - specify the location you want to download the key

Step 6 Create EC2 instance
  - specify a region
  - instance type (ex: t2.micro)
  - AMI
  - Name or id of the Security Group
  - subnet id
  - assing public IP address
  
