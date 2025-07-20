# 🌩️ AWS Services: Functionality & Use-Cases

| S.No | **Service Name**   | **Functionality**                                                                                                                                      | **Common Use-Cases**                                 |
|:----:|:------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------|
| 1    | **AWS X-Ray**     | Uses Traces: contains data about each request.<br>Creates a service map to see data latencies, HTTP status codes, and metadata.                        | Debug apps on microservices & serverless architectures |
| 2    | **VPC Endpoint**  | Private connection between AWS services and VPC.<br>**Types:**<br>a) Gateway Endpoint:<br>• Uses route table entries<br>• For S3 and DynamoDB only<br>• Basic access control<br><br>b) Interface Endpoint:<br>• Uses private IP in subnet<br>• For most AWS services<br>• Fine-grained access control | • Secure private access to AWS services<br>• Bulk data transfer (Gateway)<br>• Managed service access (Interface) |

---

✨ *Tip: For VPC Endpoints, remember: Gateway (S3/DynamoDB, simple) vs Interface (All services, advanced)*
