# Scenario overview

This scenario is interesting because it presents a case where you don't have any initial access or credentials for the AWS account. It's a realistic example of an external attack that doesn't rely on credentials being exposed in a repo or similar situations.

In this case, the attacker exploits a misconfiguration in an EC2 instance to gain access to the EC2 credentials. From there, they can use those credentials to access an S3 bucket containing sensitive data. This type of exploit is fairly common in cloud environments, making it a valuable scenario to explore.

![image](https://github.com/user-attachments/assets/9e5b5541-8b07-41b9-a586-2607d0c52684)
