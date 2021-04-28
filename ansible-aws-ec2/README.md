# AWS related plabooks
Simple playbook for vm provisioning.
Please create environment file in /ec2_env at first, the content is as below:

```
REGION: ${region}
AMI_ID: ${AMI Image id}
AWS_ACCESS_KEY: ${Your AWS access id}
AWS_SECRET_KEY : ${Your AWS access key}
INSTANCE_TYPE: ${Your instance type}
VPC_SUBNET_ID: ${Your VPC subnet id}
WINDOWS_ADMIN_PASSWORD: ${windows admin's password}
```
