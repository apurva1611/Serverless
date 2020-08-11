# serverless
## Problem Statement
Microservice of the Bill Tracking Application. 
This microservice is used to send emails of the bills pending of the user using Amazon SNS,Amazon SES and Amazon SQS.Amazon DynamboDb is used to store record of the user for 2 hrs and if any user asks for the bills in that time only one email is send.

## Repository to impleement serverless computing
1. Code to implement serverless computing serverless.
2. Continous Integration is done using CircleCI.
3. Environment variables should be present in CircleCI.
4. Run this build after creating cloudformation stack.
5. Also lambda function will be created using cloudformation.


