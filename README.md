# serverless-web-application
Deploy a serverless web applications in AWS

step-1: Create IAM role 
i) AWSLambdaBasicrole
ii)AWSDynamoDBFullAccess

Step2: create a Lambda Fucntion 
attach iam role with fucntion
then copy and past the code in (lambda fucntion-1.txt)

Step3: Create DynamoDB 
Step4: Create API Gateway 
choose REST API
then add methods (/GET AND /POST) and deploy
you will see a invoke URL 

At last enter the data in contactus.html page and the data will be automatically get stored in DynamoDB.
