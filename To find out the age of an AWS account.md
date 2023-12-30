https://stackoverflow.com/questions/8679018/is-there-a-way-to-find-out-the-age-of-an-aws-account

### Login to your root account or any account that has access to billing.

#### Then go to https://us-east-1.console.aws.amazon.com/billing/rest/v1.0/account

![1](https://github.com/Chaitu95p/AWS-Notes/assets/46298683/cf8a1c60-5c94-4210-902b-0e217f6f0594)

You'll find the **registrationDate** in epoch format.

**Note**: Use https://www.unixtimestamp.com/ to convert epoch time to normal time.
