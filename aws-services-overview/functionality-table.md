# 🌩️ AWS Services: Functionality & Use-Cases

| S.No | **Service Name**   | **Functionality**                                                                                                                                      | **Common Use-Cases**                                 |
|:----:|:------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------|
| 1    | **AWS X-Ray**     | Uses Traces: contains data about each request.<br>Creates a service map to see data latencies, HTTP status codes, and metadata.                        | Debug apps on microservices & serverless architectures |
| 2    | **VPC Endpoint**  | Private connection between AWS services and VPC.<br>**Types:**<br>a) Gateway Endpoint:<br>• Uses route table entries<br>• For S3 and DynamoDB only<br>• Basic access control<br><br>b) Interface Endpoint:<br>• Uses private IP in subnet<br>• For most AWS services<br>• Fine-grained access control | • Secure private access to AWS services<br>• Bulk data transfer (Gateway)<br>• Managed service access (Interface) |
| 3    | **AWS Organizations** | Central Management system for AWS:<br>• Automate account creation - group these accounts based on business needs<br>• Apply policies on these groups for governance & security<br>• Simply billing by setting single payment method | Manage AWS accounts of all units and then share the reserved EC2 instances amongst all units |
| 4    | **EFS**          | File storage system with aws ec2 instances. Provides:<br>• File system interface<br>• File system access semantics<br>• Concurrent accessible storage with upto 1000s of ec2 instances | • When EBS/instance store doesn't support multi-instance access<br>• When S3 doesn't support file append operations<br>• Mount on instances across multiple AZs |
| 5    | **AWS Shield**    | Prevents AWS services from common network and transport layer DDoS attacks.<br>• Standard: Free, default for all customers<br>• Advanced: Customizable rules, 24/7 access to shield response team | Protection for internet-facing applications:<br>• Route 53<br>• Global Accelerator |
| 6    | **DynamoDB**      | Serverless, NoSQL, fully managed database with single-digit millisecond performance at any scale.<br><br>Global tables: fully managed, multi-region, multi-active database feature - automatically replicates table data across AWS Regions | Application needs AWS NoSQL database service to support active-active configuration in both East and West US AWS regions |
| 7    | **AWS Glue**      | A serverless data integration service that makes it easy to discover, prepare, and combine data.<br>• Works like a virtual data expert<br>• Automatically finds and catalogs your data<br>• Helps clean and transform data | • Converting data formats (like CSV to JSON)<br>• Combining data from different sources<br>• Preparing data for analysis |
| 8    | **Amazon Macie**  | Security service that uses machine learning to automatically find and protect sensitive data. Particularly in S3.<br>• Discovers sensitive data (like credit cards, passwords)<br>• Alerts you about data security risks<br>• Monitors data access patterns | • Finding personal information in S3 buckets<br>• Protecting customer data<br>• Meeting data privacy requirements |
| 9    | **Amazon Polly**  | Text-to-Speech service that turns text into natural-sounding speech.<br>• Supports multiple languages and voices<br>• Can create audio files from text<br>• Works in real-time | • Creating audio versions of articles<br>• Building talking applications<br>• Making accessible content |

---

✨ *Tip: For VPC Endpoints, remember: Gateway (S3/DynamoDB, simple) vs Interface (All services, advanced)*

💡 *Tip: Think resource performance monitoring, events, and alerts; think CloudWatch.<br>
Think account-specific activity and audit; think CloudTrail.<br>
Think resource-specific change history, audit, and compliance; think Config.*
