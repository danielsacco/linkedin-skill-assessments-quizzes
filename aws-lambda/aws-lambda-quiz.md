## AWS Lambda

#### Q1. How can you increase the CPU resources for your Lambda?

- [ ] Increase the configured CPU value
- [ ] Increase the configured timeout value
- [ ] Increase the configured memory value
- [ ] Increase the configured concurrency value

#### Q2. How can additional code or content be provided for your Lambda?

- [ ] blocks
- [ ] layers
- [ ] aliases
- [ ] handlers

#### Q3. How can Step Functions call Lambdas?

- [ ] in sequence
- [ ] both of these answers
- [ ] neither of these answers
- [ ] in parallel

#### Q4. Which AWS CLI command invokes a function?

- [ ] aws lambda invoke --function ReturnBucketName outputfile.txt
- [ ] aws lambda execute --function-name ReturnBucketName outputfile.txt
- [ ] aws lambda invoke --function-name ReturnBucketName outputfile.txt
- [ ] aws lambda execute --function ReturnBucketName outputfile.txt

#### Q5. What adds tracing capabilities to a Lambda?

- [ ] AWS Trace
- [ ] CloudStack
- [ ] CloudTrail
- [ ] AWS X-Ray

#### Q6. You need to build a continuous integration/deployment pipeline for a set of Lambdas. What should you do?

- [ ] Create configuration files and deploy them using AWS CodePipeline.
- [ ] Create CloudFormation templates and deploy them using AWS CodeBuild
- [ ] Create configuration file and deploy using AWS CodeBuild
- [ ] Create CloudFormation templates and deploy them using AWS CodePipeline.

#### Q7. What can you use to monitor function invocations?

- [ ] API Gateway
- [ ] S3
- [ ] SAS
- [ ] CloudTrail

#### Q8. It is AWS best practice to enable Lambda logging by which of these methods.

- [ ] Use S3 metrics and CloudWatch alarms
- [ ] Create custom metrics within your Lambda code.
- [ ] Create custom metrics within your CloudWatch code.
- [ ] Use Lambda metrics and CloudWatch alarms.

#### Q9. What may be provided for environment variables?

- [ ] an SSL certificate
- [ ] a bitmask
- [ ] an AWS KMS key
- [ ] an HTTP protocol

#### Q10. Lambdas allow for running of what other things?

- [ ] binaries.
- [ ] all of these answers
- [ ] executables
- [ ] Shell scripts

#### Q11. In what style must you write Lambda code?

- [ ] MVC
- [ ] virtual
- [ ] stateless
- [ ] protocol

#### Q12. How can a developer provide Lambda code?

- [ ] by uploading a .zip file
- [ ] all of these answers
- [ ] by editing inline
- [ ] from an S3 bucket

#### Q13. You are performance-testing your Lambda to verify that you set the memory size adequately. Where do you verify the execution overhead?

- [ ] CLoudWatch logs
- [ ] DynamoDB logs
- [ ] S3 logs
- [ ] Lambda logs.

#### Q14. What facilitates continuous delivery of Lambdas?

- [ ] CodeStack
- [ ] ElasticStack
- [ ] Mobile Hub
- [ ] CodeDeploy

#### Q15. How are computing resources allocated to Lambdas?

- [ ] proportionally
- [ ] equally
- [ ] periodically
- [ ] daily

#### Q16. You can restrict the scope of a user's permissions by specifying which two items in an IAM policy?

- [ ] resources and users
- [ ] resources and conditions
- [ ] events and users
- [ ] events and conditions

#### Q17. What does Lambda logging include?

- [ ] logging streams
- [ ] rotating streams
- [ ] logging events
- [ ] advancing log groups

#### Q18. What can AWS Amplify NOT do for a Lambda?

- [ ] create a Lambda
- [ ] be an event source
- [ ] assign an IAM role
- [ ] delete a Lambda

#### Q19. How do you author a Lambda in a programming language that AWS does not support?

- [ ] Create a Lambda function with a custom runtime and reference the function in your Lambda
- [ ] Create a Lambda layer with a custom runtime and reference the layer in your lambda
- [ ] You cannot use Lambda in this situation
- [ ] Create a Lambda function with a custom runtime

#### Q20. What are listed downstream resources based on?

- [ ] the execution policy
- [ ] the Lambda configuration
- [ ] the Lambda nodes
- [ ] the IAM user

#### Q21. Which is an equivalent and valid tag for a pair of Lambdas?

- [ ] department:Sales,department:Sales
- [ ] department:Sales,department:sales
- [ ] aws:demo;aws:demo
- [ ] aws:demo;aws:DEMO

#### Q22. Outbound connections from Lambdas must be `_`.

- [ ] neither of these answers
- [ ] UDP/IP
- [ ] TCP/IP
- [ ] both of these answers

#### Q23. How are CloudWatch actions configured?

- [ ] automatically
- [ ] none of these answers
- [ ] manually
- [ ] ad hoc

#### Q24. You are testing your stream-based application and the associated Lambda. AWS best practice advises you to test by varying what?

- [ ] stream and record sizes
- [ ] stream and shard sizes
- [ ] batch and record sizes
- [ ] batch and shard sizes

#### Q25. You need to make your Lambda available to services in multiple VPCs. What do you do?

- [ ] Place each subnet in a VPC. Associate all subnets to your Lambda.
- [ ] Place all subnets in a VPC. Associate all subnets to your Lambda.
- [ ] Configure your Lambda to be available to multiple VPCs.
- [ ] Configure all application VPCs to be peered.

#### Q26. How is the cost associated with Lambda function calculated?

- [ ] number of function calls
- [ ] amount of code run
- [ ] compute time
- [ ] amount of infrastructure used

#### Q27. What is the fastest way to get started with Lambda?

- [ ] Author a Lambda from scratch.
- [ ] Use a blueprint.
- [ ] Use a .zip deployment package.
- [ ] Use the serverless app repository.

#### Q28. Where is the disk space allocated for Lambda functions?

- [ ] /tmp
- [ ] /default
- [ ] /temp
- [ ] /ds

#### Q29. How do you stop a running Lambda that is stuck in a recursive loop?

- [ ] Delete the function.
- [ ] Set the function concurrent execution limit to 0 while you update the code.
- [ ] Reset the function.
- [ ] Set the function concurrent execution limit to 100 while you update the code.

#### Q30. What is AWS best practice for Lambda configuration?

- [ ] Overprovision memory to run your functions faster and reduce your costs. Do not overprovision your function timeout settings.
- [ ] Overprovision memory and your function timeout settings to run your functions faster and reduce your costs.
- [ ] Do not overprovision memory. Overprovision your function timeout settings to run your functions faster and reduce costs.
- [ ] Do not overprovision memory. Do not overprovision your function timeout settings to run your functions faster and reduce costs.

#### Q31. Basic Lambda permissions include permissions for what?

- [ ] removing log groups
- [ ] none of these answers
- [ ] creating log groups
- [ ] updating log groups

#### Q32. How are environment variables stored?

- [ ] DynamoDB tables
- [ ] key-value pairs
- [ ] S3 buckets
- [ ] none of these answers

#### Q33. You need to use a Lambda to provide backend logic to your website. Which service do you use to make your Lambda available to your website?

- [ ] S3
- [ ] API Gateway
- [ ] X-Ray
- [ ] DynamoDB

#### Q34. You are creating a Lambda to trigger on change to files in an S3 bucket. Where should you put the bucket name?

- [ ] in the Lambda function code
- [ ] in a Lambda environment variable
- [ ] in the Lambda tags
- [ ] in another S3 bucket

#### Q35. What action is needed before you can test a Lambda?

- [ ] Deploy the Lambda
- [ ] Export the function
- [ ] none of these answers
- [ ] Configure a test event

#### Q36. What kind of packages can you use with Node.js for Lambdas?

- [ ] Fleece
- [ ] NPM
- [ ] none of these answers
- [ ] Pod

#### Q37. Lambdas are monitored by default using which service?

- [ ] CloudTrail
- [ ] CloudWatch
- [ ] CloudFormation
- [ ] LogWatch

#### Q38. What can trigger a Lambda function execution?

- [ ] a table definition
- [ ] queue isolation
- [ ] STS Write
- [ ] an SNS topic

#### Q39. You need to set an S3 event trigger on your Lambda to respond when data is added to your bucket from another S3 bucket. Which event type do you configure?

- [ ] POST
- [ ] "All object create events"
- [ ] PUT
- [ ] COPY

#### Q40. To make Lambdas more testable, it is AWS best practice to separate which of these?

- [ ] Lambda configuration from logging code
- [ ] Lambda handler from logging code
- [ ] Lambda handler from core logic
- [ ] Lambda configuration from core logic

#### Q41. What is included in an exported Lambda deployment package?

- [ ] YAML definition
- [ ] CloudFormation stack configuration
- [ ] SAML deployment stack
- [ ] Zip file of all related files

#### Q42. When can you change the execution role of a Lambda?

- [ ] only at creation
- [ ] only before deployment
- [ ] never
- [ ] anytime via configuration

#### Q43. What is the relationship between SAM template and CloudFormation template files?

- [ X] SAM templates are a superset of CloudFormation templates. SAM templates include additional resource types.
- [ ] SAM templates have some overlap with CloudFormation templates. Both SAM and CloudFormation templates include resource types that are not in the other type of template.
- [ ] CloudFormation templates are a superset of SAM templates. CloudFormation templates include additional resource types.
- [ ] SAM templates are a different name for CloudFormation templates. Both template types include the same resource types.

#### Q44. What service deploys Lambdas regionally?

- [ ] EdgeCloud
- [ ] CloudEdge
- [ ] CloudFront
- [ ] CloudStack

#### Q45. What programming language does AWS Lambda support?

- [ ] custom
- [ ] all of these answers
- [ ] Java
- [ ] Ruby

#### Q46. You need to setup a mechanism to put controls in place to notify you when you have a spike in Lambda concurrency. What should you do?

- [ ] Deploy a CloudTrail alarm that notifies you when function metrics exceed your threshold. Create an AWS budget to monitor costs.
- [ ] Deploy a CloudWatch alarm that notifies you when function metrics exceed your threshold. Create an AWS budget to monitor costs.
- [ ] Deploy a CloudWatch alarm that notifies you when function metrics exceed your threshold. Create an AWS CostMonitor to monitor costs.
- [ ] Deploy a CloudTrail alarm that notifies you when function metrics exceed your threshold. Create an AWS CostMonitor to monitor costs.

#### Q47. You want to minimize cold start time for your Lambda. What do you do?

- [ ] Add extra code to check if the transient cache, or the /tmp directory, has the data that you stored.
- [ ] Add extra code to check if the permanent cache, or the /cache directory, has the data that you stored.
- [ ] Do nothing. AWS minimizes cols start time by default.
- [ ] Create a warm-up Lambda that calls your Lambda every minute

[Reference](https://aws.amazon.com/blogs/compute/new-for-aws-lambda-predictable-start-up-times-with-provisioned-concurrency/

#### Q48. When is Lambda code stored encrypted?

- [ ] at rest
- [ ] at runtime
- [ ] at deployment
- [ ] non of these answers

[Reference](https://docs.aws.amazon.com/whitepapers/latest/security-overview-aws-lambda/lambda-functions-and-layers.html)

#### Q49. When you use a resource-based policy to give a service, resource, or account access to your function, how can you apply the scope of that permission??

- [ ] at the function level
- [ ] at the alias or function level
- [ ] at the version, alias, or function level
- [ ] at the version or function level

[Reference](https://docs.aws.amazon.com/lambda/latest/dg/access-control-resource-based.html)

#### Q50. Lambda can read events from which other AWS services? (ref-https://docs.aws.amazon.com/lambda/latest/dg/lambda-services.html)

- [ ] Kinesis, S3, and SQS
- [ ] Kinesis, S3, and SNS
- [ ] Kinesis, DynamoDB, and SNS
- [ ] Kinesis, DynamoDB, and SQS

**Explanation**

- `Lambda can used for all services mentioned on the question: Kinesis, S3, SNS, SQS, DynamoDB. But as you can see in the reference, Lambda's responsibility and method invocation can be categorized by Lambda polling and Event Driven (synchronous invocation). When you implement an event-driven architecture, you grant the event-generating service permission to invoke your function in the function's resource-based policy. Then you configure that service to generate events that invoke your function. When you implement a Lambda polling architecture, you grant Lambda permission to access the other service in the function's execution role. Lambda reads data from the other service, creates an event, and invokes your function. According to this analytics, Kinesis-DynamoDB-SQS use same method invocation, Lambda polling.`

#### Q51. Via what can a Lambda be called?

- [ ] all of these answers
- [ ] a DynamoDB trigger
- [ ] an API Gateway
- [ ] an S3 bucket event

**Explanation** (source google)

- `With DynamoDB Streams, you can trigger a Lambda function to perform additional work each time a DynamoDB table is updated. Lambda reads records from the stream and invokes your function synchronously with an event that contains stream records.`
- `These events are considered synchronous events. Simply put, it means that when somebody is calling an API Gateway, it will trigger your Lambda function. It's a synchronous event because your Lambda function has to respond to the client directly at the end of its invocation.`
- `You can use Lambda to process event notifications from Amazon Simple Storage Service. Amazon S3 can send an event to a Lambda function when an object is created or deleted.`

#### 52. which is use case of lambda ?

- [ ] Image processing
- [ ] web application
- [ ] both
- [ ] Neither 1st and 2nd

#### Q53. Events are AWS resources that trigger the Lambda function. What data type is the SAM file Events property?

- [ ] Integer
- [ ] Float
- [ ] Array
- [ ] String

#### Q54. A company is using an API built using Amazon Lambda, Amazon API Gateway, and Amazon DynamoDB in production. The developer has observed high latency during peak periods. Which approach would best resolve the issue?

- [ ] Increase the Lambda function timeout
- [ ] Route traffic to API Gateway using a Route 53 alias
- [ ] Disable payload compression for the API
- [ ] Enable API Gateway stage-level caching

#### Q55. The AWS Serverless Application Model (AWS SAM) is a model that \_\_\_\_ .

- [ ] defines serverless applications
- [ ] associates permissions policies
- [ ] creates Lambda functions
- [ ] packages deployment artifacts

#### Q56. The code that you want AWS Lambda to invoke as per some defined triggers is known as **\_**.

- [ ] the event source
- [ ] the downstream resource
- [ ] the log stream
- [ ] the Lambda function

#### Q57. A developer has created a Lambda function to scrub real-time data of extraneous information and then send the scrubbed data to Kinesis for further processing and storage. Some of the data showing up in Kinesis seems to be inaccurate. What's the best way for the developer to debug this?

- [ ] Look directly at the Lambda Logs in CloudWatch
- [ ] Send the Lambda failures to a Dead Letter Queue
- [ ] Use AWS X-Ray to step through the function
- [ ] Use Kinesis to write their own custom logging tool

#### Q58. Lambdas can be created **\_**.

- [ ] All of these answers
- [ ] From scratch
- [ ] From the app repository
- [ ] Using a blueprint

#### Q59. You need to quickly understand execution times for two different Lambda functions with different invocation types: asynchronous and synchronous. What do you do?

- [ ] Enable tracing, rerun the lambdas, and view in the lambda console
- [ ] View the logs in CloudTrail
- [ ] View the logs in CloudWatch
- [ ] Enable tracing, rerun the Lambdas, and view in the X-Ray console

#### Q60. Which tool would you use to test a Lambda locally?

- [ ] AWS SAM
- [ ] AWS CLI
- [ ] AWS CloudFormation
- [ ] AWS SAM CLI

#### Q61. Your function failed to execute due to a timeout. What type of error is this?

- [ ] Caller
- [ ] Runtime
- [ ] Request
- [ ] Account

#### Q62. A company will be modernizing their application which is currently running on Amazon Elastic Cloud Compute (EC2) instances. They have experience with scaling this infrastructure using Amazon EC2 Autoscaling. They want to move to serverless infrastructure consisting of an Amazon API Gateway that triggers Lambda functions. They are consulting you about scaling this new infrastructure. What should the company consider in order to make sure the serverless infrastructure scales to their needs?

- [ ] Enable Auto Scaling Groups for AWS Lambda to ensure that enough Lambda functions are ready to handle the incoming requests
- [ ] Throttle Lambda functions by configuring reserved concurrency, sending the excess traffic to Dead Letter Queues (DLQ) that will be handled when the request volume reduces.
- [ ] Look at service limits for Amazon API Gateway and Lambda functions used in order to identify potential bottlenecks and balance performance requirements, costs, and business impact
- [ ] Do nothing. API Gateway and AWS Lambda are managed services that have built-in horizontal scaling, security, and high availability to handle unlimited amount of requests

**Explanation**

In serverless it is important to understand the service limits of all the services used end to end to understand the level of requests that can be handled.
