# ECS-Start-Stop-Basic


Basic AWS Lambda Python function for exporting cloudwatch logs to S3 bucket

The lambda code is dynamic as theres no cluster and service hardcoded in the code

Set the Eventbridge trigger and set the cron, the lambda function will that the trigger time and export past 24 hours of logs,: 


```batch
Set the below Enviroment variables : 

AWS_ACCOUNT  : SANDBOX

S3_BUCKET : my_bucket
```
