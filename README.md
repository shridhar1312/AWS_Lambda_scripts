# AWS_Lambda_scripts


Lambda Function
Be sure to set the Lambda function timeout high enough (i.e. 1 minute) so that it can iterate through every instance in every region.
(Region part is not yet implemenred)

CloudWatch Event Rule
Cron expression: 0 23 ? * MON-FRI *

6:00pm EST (UTC-5) == 11:00pm (23:00) UTC
