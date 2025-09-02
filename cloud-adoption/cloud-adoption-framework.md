# 🏗️ AWS Cloud Adoption Framework (CAF)

## Overview
CAF (Cloud Adoption Framework) - AWS CAF identifies specific organizational capabilities that underpin successful cloud transformations.
AWS CAF groups its capabilities in six perspectives: Business, People, Governance, Platform, Security, and Operations.

## Best Practices
• Leverage agile methods to rapidly iterate and evolve
• Organize your teams around products and value streams

## 📊 CAF Perspectives

| Perspective | Focus Area | Key Stakeholders |
|:------------|:-----------|:-----------------|
| Business    | Value realization, business goals | Business managers, Finance managers, Budget owners |
| People      | Culture, organizational change | HR, Staffing managers, People managers |
| Governance  | Risk, compliance, process alignment | CIO, Program managers, Enterprise architects |
| Platform    | Infrastructure, applications | CTO, IT managers, Solutions architects |
| Security    | Data protection, security controls | CISO, Security analysts, Risk managers |
| Operations  | Operations management, service monitoring | Operations managers, Site reliability engineers |

---

# 💰 Data Transfer Costs in AWS

## Overview
Fundamental drivers of cost with AWS: compute, storage, and outbound data transfer.

## Cost Structure
### Inbound Transfer
• No charge for inbound data transfer or data transfer between other AWS services within the same region

### Outbound Transfer
• Outbound data transfer is aggregated across services and then charged at the outbound data transfer rate.

💡 **Example:**
As per AWS pricing, data transfer between S3 and EC2 instances within the same region is not charged