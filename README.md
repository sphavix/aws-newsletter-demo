## AWS Newsletter Dummy Project



Newsletter Dummy Project.
This project demonstrates how you can utilize AWS services to send email alerts or newsletters to users. Using services like Amazon EventBridge Schedule to invoke a target one-time or at regular intervals, it can be easily integrated with other AWS services.

Services:
1. Amazon EventBridge -: I am using Amazon EventBridge to invoke the Lambda function to send the email alert.
2. Amazon Lambda -: The Lambda function retrieves and reads the S3 object that contains email addresses and email template written in HTML, Then sends email alerts to the users using Amazon SES.
3. Amazon Simple Email Service -: The Amazon SES has email addresses configured to send and receive email.
4. IAM Roles -: Amazon Lambda needs permissions to read S3 Bucket objects and also use Amazon SES to send email notifications.
5.  Amazon S3 -: The S3 Bucket contains a file that has email addresses and the HTML email template.
6.  Amazon CloudWatch -: CloudWatch provides you with data and actionable insights to monitor your applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health.







