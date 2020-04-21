# Serverless Data Engineering Pipeline through AWS
This project is created to demonstrate the serverless data engineering pipeline on AWS. The application obtains data from the DynamoDB and triggers Producer Lambda, then sends the data to SQS. Once the data reaches the SQS, the Consumer Lambda will get triggered and run the Amazon Comprehend to do sentiment analysis. The final output is in csv file and saved in S3 bucket. The artchitecture flow of the project is as below.

![Archetecture](https://user-images.githubusercontent.com/58792/55354483-bae7af80-547a-11e9-9909-a5621251065b.png)
