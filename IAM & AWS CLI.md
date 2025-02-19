## IAM & AWS CLI
- IAM = Identity & Access Management, Global Service
- Root Account created by default, shouldn't be used or shared.

### IAM Permissions
- Users or groups can be assigned JSON documents called policies.
- These policies define the permissions of the users.
- In AWS you apply <b> the least privilege principle </b> : don't give more permissions than a user needs
```
{
    version: "2012-03-21",
    "Statement":  [
        {
            "Effect": "Allow",
            "Action": "ec2:Describe",
            "Resource": "*"
        }
    ]
}
```