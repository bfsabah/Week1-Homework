## Week1-Homework
IAM Solutions
- I will create a new group called "NewGroup-It_ReadOnly_S3-APi-DynamoDB"
- I set the group permissions to :  - AmazonAPIGatewayInvokeFullAccess
                                    - AmazonDynamoDBReadOnlyAccess
                                    - AmazonS3READOnlyAccess
- I create 3 Users and add them to the group "NewGroup-It_ReadOnly_S3-APi-DynamoDB"
- Thats all.


S3 Solutions
- I create a Public accessed Bucket.
- I upload the HTML file to the bucket.
- I have an access to the file and can execute the HTML file.
- I generate AWS Policy for S3 bucket and Deny Access for the Index.html file
- I add this Policy to the bucket and access is denied for the Index.html file.
- Then I go to policy properties for Bucket and delete the policy.
- Problem is solved.
# Week2
