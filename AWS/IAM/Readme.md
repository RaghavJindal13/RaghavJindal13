<h1 align="center">
 <img src="https://cdn.freebiesupply.com/logos/large/2x/aws-iam-logo-png-transparent.png" width="40" height="70" /> 
  AWS IAM
</h1>

AWS Identity and Access Management (IAM) enables organizations to securely control access to AWS cloud services and resources for their users. \
Using IAM, organisations can create and manage AWS users and groups and use permissions to allow and deny their acess to AWS resources. \
<br></br>
<img src="https://user-images.githubusercontent.com/53964007/122317782-b31d6400-cf3b-11eb-89f6-3e19574dc446.png" />

<table>
  <tr>
    <th colspan=2>Execution Role (Common Execution Role Available).</th>
  </tr>
  <tr>
    <td><b>AWSLambdaBasicExecutionRole</b></td>
    <td>Grants permissions only for the Amazon CloudWatch Logs actions to write logs.</td>
  </tr>
  <tr>
    <td><b>AWSLambdaKinesisExecutionRole</b></td>
    <td>Grants permissions for Amazon Kinesis Streams actions, and CloudWatch Logs actions.</td>
  </tr>
  <tr>
    <td><b>AWSLambdaDynamoDBExecutionRole</b></td>
    <td>Grants permissions for DynamoDB streams actions and CloudWatch Logs actions.</td>
  </tr>
  <tr>
    <td><b>AWSLambdaVPCAccessExecutionRole</b></td>
    <td>Grants permissions for Amazon Elastic Compute Cloud (Amazon EC2) actions to manage elastic network interfaces (ENIs).</td>
  </tr>
  <tr>
    <td><b>AWSXrayWriteOnlyAccess</b></td>
    <td>Grants permission for X-ray to to upload trace data to debug and analyze.</td>
  </tr>
</table>



## VPC
```
1. When you enable VPC, your Lambda function will lose default internet access.
2. If you require external internet access for your function, ensure that your security group allows outbound connections.
   and that your VPC has a NAT gateway.
``` 
### what happens if i am unable to pay the aws bill
### does aws has right to automatically deduct from my card if no then why it asks for card details
### what if i gave a IAM user fulIAMacess so it means it has full aws control as it can create other users with like fullec2 acess. ans i think yes.
### what are the conditions necessary to specify in the policy - action,services,
### 
