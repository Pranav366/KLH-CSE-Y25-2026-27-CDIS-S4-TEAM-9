# Cloud-Based Application Performance Benchmarking and Auto Scaling Evaluation

## Team Details

**Team Number: 9**

| S.No. | Team Member Name | Roll Number |
|---|---|---|
| 1 | S. Jayanth | 2520030421 |
| 2 | Pranav Chowdary | 2520030555 |
| 3 | G. Akshay | 2520030363 |

---

## Abstract

The project titled **“Cloud-Based Application Performance Benchmarking and Auto Scaling Evaluation”** aims to develop a cloud-based platform to analyze web application performance under different workload conditions using Amazon Web Services (AWS). The main objective is to evaluate application scalability, availability, response time, and resource utilization by deploying a sample web application on Amazon EC2 instances.

The application will be containerized using Docker and deployed within an AWS Virtual Private Cloud (VPC) consisting of public and private subnets with proper IP address planning. An Application Load Balancer (ALB) will distribute incoming traffic across EC2 instances, while an Auto Scaling Group will automatically increase or decrease the number of instances based on workload demands. Apache JMeter will be used to generate controlled user traffic and simulate different workload conditions. Amazon CloudWatch will monitor CPU utilization, request counts, response time, error rates, and scaling activities. Amazon S3 will provide persistent storage for benchmarking results and performance reports.

The collected metrics will be analyzed to compare different auto scaling configurations and identify performance bottlenecks. Finally, the project will recommend an optimized cloud infrastructure configuration that balances application performance, scalability, reliability, and operational cost.

---

## AWS Services

The following AWS services will be used in this project:

1. **Amazon EC2** – To host and run the sample web application.
2. **Amazon VPC** – To create an isolated cloud network with public and private subnets.
3. **Application Load Balancer (ALB)** – To distribute incoming application traffic.
4. **EC2 Auto Scaling Group** – To automatically scale instances according to workload demands.
5. **Amazon CloudWatch** – To monitor performance metrics, logs, alarms, and scaling activities.
6. **Amazon S3** – To store benchmarking results and performance reports.
7. **Amazon EBS** – To provide persistent block storage for EC2 instances.
8. **AWS IAM** – To manage access permissions and secure AWS resources.
9. **NAT Gateway** – To provide internet access to resources in private subnets.

## Additional Tools

- **Docker** – For application containerization.
- **Apache JMeter** – For generating simulated user traffic and performance testing.
- **AWS CLI** – For managing AWS services through command-line operations.

---

## Project Objectives

- Deploy a sample web application on AWS EC2 instances.
- Configure AWS VPC with public and private subnets.
- Distribute application traffic using an Application Load Balancer.
- Implement automatic scaling based on workload demands.
- Generate different workloads using Apache JMeter.
- Monitor application and infrastructure performance using Amazon CloudWatch.
- Store benchmarking results and reports using Amazon S3.
- Compare auto scaling configurations and identify performance bottlenecks.
- Recommend an optimized cloud infrastructure configuration.

---

## Expected Outcomes

- A functional cloud-based application deployment on AWS.
- Performance measurements under different workload conditions.
- Evaluation of EC2 Auto Scaling behaviour.
- Monitoring and analysis of application performance metrics.
- Identification of performance bottlenecks.
- Recommendations for balancing performance, scalability, reliability, and operational cost.

---

## Course Details

**Course:** Cloud Infrastructure and Services  
**Course Code:** 25CS2206E  
**Project Team:** Team 9
**Guide:**Dr. V. Sireesha
---

## Team Members

- **S. Jayanth** – 2520030421
- **Pranav Chowdary** – 2520030555
- **G. Akshay** – 2520030363
