<h1 align="center">
 <img src="https://cdn.freebiesupply.com/logos/large/2x/aws-iam-logo-png-transparent.png" width="40" height="70" /> 
  AWS IAM
</h1>

AWS Identity and Access Management (IAM) enables organizations to securely control access to AWS cloud services and resources for their users. \
Using IAM, organisations can create and manage AWS users and groups and use permissions to allow and deny their acess to AWS resources. \
<br></br>
<img src="https://user-images.githubusercontent.com/53964007/122317782-b31d6400-cf3b-11eb-89f6-3e19574dc446.png" />

IAM uses traditional identity concepts such as users,
groups, and access control policies to control who can use your AWS account, what services
and resources they can use, and how they can use them.




## Principals
```
1. A principal is an IAM entity that is allowed to interact with AWS resources.
2. There are three types of principals: root users, IAM users, and roles/temporary security tokens.
``` 

<table>
  <tr>
    <th colspan=2>IAM Principals.</th>
  </tr>
  <tr>
    <td><b>Root User</b></td>
    <td>When you first create an AWS account, you begin with only a single sign-in principal that has
complete access to all AWS Cloud services and resources in the account. This principal is
called the root user.</td>
  </tr>
  <tr>
    <td><b>IAM Users</b></td>
    <td>1. The concept of allowing a person or process interacting with your AWS resources to perform
exactly the tasks they need but nothing else.
     2. they are permanent entities that exist until an IAM administrator takes an
action to delete them.
   
   </td>
  </tr>
  <tr>
    <td><b>Roles/Temporary Security Tokens</b></td>
    <td>Roles are used to grant specific privileges to specific actors for a set duration of time.
   The range of a temporary security token lifetime is 15 minutes to 36 hours
     Amazon EC2 Roles—Granting permissions to applications running on an Amazon EC2
instance.
Cross-Account Access—Granting permissions to users from other AWS accounts,
whether you control those accounts or not.
Federation—Granting permissions to users authenticated by a trusted external system.

   </td>
  </tr>
</table>

## Authentication

<table>
  <tr>
    <th colspan=2>There are three ways that IAM authenticates a principal</th>
  </tr>
  <tr>
    <td><b>User Name/Password</b></td>
    <td>When you first create an AWS account, you begin with only a single sign-in principal that has
complete access to all AWS Cloud services and resources in the account. This principal is
called the root user.</td>
  </tr>
  <tr>
    <td><b>Access Key</b></td>
    <td>1. The concept of allowing a person or process interacting with your AWS resources to perform
exactly the tasks they need but nothing else.
     2. they are permanent entities that exist until an IAM administrator takes an
action to delete them.
   
   </td>
  </tr>
  <tr>
    <td><b>Access Key/Session Token</b></td>
    <td>Roles are used to grant specific privileges to specific actors for a set duration of time.
   The range of a temporary security token lifetime is 15 minutes to 36 hours
     Amazon EC2 Roles—Granting permissions to applications running on an Amazon EC2
instance.
Cross-Account Access—Granting permissions to users from other AWS accounts,
whether you control those accounts or not.
Federation—Granting permissions to users authenticated by a trusted external system.

   </td>
  </tr>
</table>








### what happens if i am unable to pay the aws bill
### does aws has right to automatically deduct from my card if no then why it asks for card details
### what if i gave a IAM user fulIAMacess so it means it has full aws control as it can create other users with like fullec2 acess. ans i think yes.
### what are the conditions necessary to specify in the policy - action,services,
### 
