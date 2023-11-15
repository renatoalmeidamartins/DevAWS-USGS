# Class links for Developing on AWS

## My contact info
- Email: renatoalmeidamartins@gmail.com
- [Limkedin](https://www.linkedin.com/in/renatodealmeidamartins/)

## Additional learning
- [Skillbuider](https://skillbuilder.aws)
- [Free practie test](https://explore.skillbuilder.aws/learn/course/external/view/elearning/13757/exam-prep-official-practice-question-set-aws-certified-developer-associate-dva-c02-english)
- [Landing page for the exam](https://aws.amazon.com/certification/certified-developer-associate/)

## Navigating the class
- [Labs and course material](https://us-east-1.student.classrooms.aws.training/class/3n585N1dVNEFi1qcoGzT8e)
- [Vitrual classroom](https://netcomlearning.webex.com/)

## Day 1 links
- [Sandbox.zip - application built in class](sandbox.zip)
- [AWS developert tools](https://aws.amazon.com/developer/tools/)
- [Instructions for signing requests](https://docs.aws.amazon.com/IAM/latest/UserGuide/create-signed-request.html)
- [Installing the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [AWS ClI repo](https://github.com/aws/aws-cli)
- [Configuring the retry behavior in the SDK and CLI](https://docs.aws.amazon.com/sdkref/latest/guide/feature-retry-behavior.html)
- [.Net-specific retry configuration (using the Amazon.Runime.ClientConfig class)](https://docs.aws.amazon.com/sdk-for-net/v3/developer-guide/retries-timeouts.html)
- [Pagination in the CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-usage-pagination.html)
- [Pagination with the Java SDK](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/pagination.html)
- [Pagination with the Python SDK](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/paginators.html)
- [Pagination with the .Net SDK](https://docs.aws.amazon.com/sdk-for-net/v3/developer-guide/paginators.html)
- There are waiters for most of the services, covering the long-running operations. Some examples below:
    - [Waiters for EC2](https://docs.aws.amazon.com/cli/latest/reference/ec2/wait/)
    - [Waiters for DynamoDB](https://docs.aws.amazon.com/cli/latest/reference/dynamodb/wait/)
    - [Waiters for Redshift](https://docs.aws.amazon.com/cli/latest/reference/redshift/wait/)
- Metrics collection with the SDK
    - [Java](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/metrics.html)
    - [.Net](https://aws.amazon.com/blogs/developer/retrieving-request-metrics-from-the-aws-sdk-for-net/)
    - [Python](https://boto3.amazonaws.com/v1/documentation/api/1.17.109/guide/sdk-metrics.html)
- [CodeWhisperer setup](https://docs.aws.amazon.com/codewhisperer/latest/userguide/whisper-setup-indv-devs.html)
- [IAM Policy generator](https://awspolicygen.s3.amazonaws.com/policygen.html)
- [JVM DNS TTL settings](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/jvm-ttl-dns.html)
-   [Best practices for the Java SDK](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/best-practices.html)
- [Identity x resource-based policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_identity-vs-resource.html)
- [Configuring credentials and profiles on the CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html)
- [Valid condition key values](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html)
- [EBS multi-attach allows multiple instances to talk to the same volume of block storage](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volumes-multi.html)
- [EBS volume types](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volume-types.html)
- [About S3 11 9's durability](https://aws.amazon.com/s3/faqs/#Durability_.26_Data_Protection)
- [Listing S3 Keys and objects](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ListingKeysUsingAPIs.html)
- [TransferManager Java class - handles multipart upload](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/transfer-manager.html)
- [Additional multipart upload samples in all languages](https://docs.aws.amazon.com/AmazonS3/latest/userguide/mpu-upload-object.html)
- [S3 Select](https://docs.aws.amazon.com/AmazonS3/latest/userguide/selecting-content-from-objects.html)
- [Presign URL, be careful with setting the region in the request to match the bucket region](https://docs.aws.amazon.com/cli/latest/reference/s3/presign.html)

## Day 2 links
- [CORS definition by Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
- [Credential precedence](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-authentication.html)
- [Neo4J and the Panama papers - example of using a graph database](https://neo4j.com/blog/analyzing-panama-papers-neo4j/)
- [Dynamo paper](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
- [PartiQL - SQL-style language for querying non relational databases](https://partiql.org/)
- [NoSQL design best practices](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-general-nosql-design.html)
[DynamoDB burst capacity](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-partition-key-design.html#bp-partition-key-throughput-bursting)
- [NoSQL workbench](https://aws.amazon.com/dynamodb/nosql-workbench/)
- [DynamoDB local](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html)
- [DynamoDB object persistence model](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Programming.SDKs.Interfaces.Mapper.html)
[DynamoDB single table design with Rick Houlihan](https://www.youtube.com/watch?v=KYy8X8t4MB8)
[DyamoDB advanced design patterns](https://aws.amazon.com/dynamodb/resources/reinvent-2019-advanced-design-patterns/)
- [DynamoDB parallel scans](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-query-scan.html#QueryAndScanGuidelines.ParallelScan)
- [.Net parallel scan](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/LowLevelDotNetScanning.html)
- [DynamoDB conditional expressions - puts, deletes, and updates](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Expressions.ConditionExpressions.html)
- [Using DAX](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DAX.client.html)
- [CDK workshop](https://cdkworkshop.com/)
- [AWS Construct Library](https://docs.aws.amazon.com/cdk/api/v2/docs/aws-cdk-lib.aws_s3.Bucket.html)
- [Lambda - My Shot Parody](https://www.youtube.com/watch?v=zMua0cuhFnc)
[Lambda best practices](https://docs.aws.amazon.com/lambda/latest/dg/best-practices.html)
- [Lambda SnapStart](https://aws.amazon.com/blogs/compute/starting-up-faster-with-aws-lambda-snapstart/)
- [Lambda function URLs](https://aws.amazon.com/blogs/aws/announcing-aws-lambda-function-urls-built-in-https-endpoints-for-single-function-microservices/)
- [Billing unit for Lambda is 1ms](https://aws.amazon.com/about-aws/whats-new/2020/12/aws-lambda-changes-duration-billing-granularity-from-100ms-to-1ms/)
- [Lambda function as a container image](https://github.com/aws/aws-lambda-python-runtime-interface-client)

## Day 3 links
- [Choosing between a HTTP and REST API](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-vs-rest.html)
- [Using the StranglerFig pattern on AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/cloud-design-patterns/strangler-fig.html)
- [Strangler Fig Pattern, as proposed originally by Martin Fowler](https://martinfowler.com/bliki/StranglerFigApplication.html)
- [AWS Tutorial to break a monolith into microservices](https://aws.amazon.com/tutorials/break-monolith-app-microservices-ecs-docker-ec2/)
- [10+ deploys per day at flickr](https://www.youtube.com/watch?v=LdOe18KhtT4)
- [The phoenix project](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/1942788290)
- [The unicorn project](https://www.amazon.com/Unicorn-Project-Developers-Disruption-Thriving/dp/1942788762)
- [DevOps handbook](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1950508404)
- [Accelerate book](https://www.amazon.com/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339)
- Wipe out resources from an AWS account (probably triggered by a budget alert)
    - [aws-nuke](https://github.com/rebuy-de/aws-nuke)
    - [AWS-resource-cleanup (keep in mind it only deletes S3, EC2 and RDS)](https://github.com/paulmercy/AWS-Resource-Cleanup-Script)
    - [AWSweeper](https://github.com/jckuester/awsweeper)
    - [awsrm](https://github.com/jckuester/awsrm)
    - [AWS SAM resource types](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-specification-resources-and-properties.html)
- [SAM CLI](https://github.com/aws/aws-sam-cli)
- [Serverless application model - SAM repo](https://github.com/aws/serverless-application-model)
- [Using Application Insights](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/appinsights-what-is.html)
- [INstrumenting an application for X-Ray](https://docs.aws.amazon.com/xray/latest/devguide/xray-instrumenting-your-app.html)