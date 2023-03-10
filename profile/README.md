# BOILERPLATE

## CREATE ACCOUNTS

### GMAIL

### AWS

#### AWS ORGANIZATIONS

Create Root, Dev, QA, and Prod accounts

#### AWS CREDENTIALS

To create an access key for the root user:

To run the following command or API operation as the root user, you must already have one active access key pair. If you don't have any access keys, create the first access key using the AWS Management Console. Then, you can use the credentials from that first access key with the AWS CLI to create the second access key, or to delete an access key.

```bash
aws iam create-access-key
```

```json
{
    "AccessKey": {
        "UserName": "MyUserName",
        "AccessKeyId": "AKIAIOSFODNN7EXAMPLE",
        "Status": "Active",
        "SecretAccessKey": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY",
        "CreateDate": "2021-04-08T19:30:16+00:00"
    }
}
```

See <https://docs.aws.amazon.com/accounts/latest/reference/root-user-access-key.html>

### Docker

### Jenkins

## DEFINE DYNAMO DB SCHEMA

## UPDATE API

### ADD ENDPOINTS

### ADD FUNCTIONALITY
