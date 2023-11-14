# Class links for Developing on AWS
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