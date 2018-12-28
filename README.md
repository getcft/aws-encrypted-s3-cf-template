# aws-encrypted-s3-cfn-template

## Description:

This solution creates an encrypted [AWS S3 Bucket](https://aws.amazon.com/s3/) leveraging a [AWS KMS](https://aws.amazon.com/kms/) key.

The AWS CloudFormation template creates a AWS KMS encryption key for S3, and an encrypted S3 bucket leveraging the KMS key.

When you use server-side encryption, Amazon S3 encrypts an object before saving it to disk in its data centers and decrypts it when you download the objects.

AWS S3 server-side encryption uses one of the strongest block ciphers available, 256-bit Advanced Encryption Standard (AES-256), to encrypt your data.

***please note AWS S3 and AWS KMS will incur costs**

* [S3 pricing](https://aws.amazon.com/s3/pricing/)
* [KMS pricing](https://aws.amazon.com/kms/pricing/)

## Prerequisites:

* AWS account and environment configured with AWS Credentials
* IAM user with AWSKeyManagementServicePowerUser, AWSCloudFormationReadOnlyAccess, AmazonS3FullAccess

## See how it works:

AWS Management Console

* Login to AWS Management Console
* Launch in CloudFormation encrypted-s3.yml (from the repo you cloned)

CloudFormation Fields

* Stack name (Enter a name to associate to your AWS S3 Bucket) then **Next**
* Continue choosing **Next** and then **Create**
