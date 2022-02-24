# AWS Security
- [Introduction](#introduction)
- [Policy as Code with AWS CDK and Open Policy Agent](#policy-as-code-with-aws-cdk-and-open-policy-agent)
- [Payment Card Industry Data Security Standard compliance](#payment-card-industry-data-security-standard-compliance)
- [AWS IAM](#aws-iam)
- [AWS Organizations](#aws-organizations)
- [AWS Control Tower](#aws-control-tower)
- [AWS Firewalls](#aws-firewalls)
- [AWS WAF Web Application Firewall](#aws-waf-web-application-firewall)
- [AWS Secrets Manager](#aws-secrets-manager)
- [AWS Vault](#aws-vault)

## Introduction
- [AWS Security Blog](http://blogs.aws.amazon.com/security)
- [AWS Security](https://aws.amazon.com/security/)
- [AWS Security docs](https://docs.aws.amazon.com/security/)
- [Tutorial: Configure Apache Web Server on Amazon Linux to use SSL/TLS](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/SSL-on-an-instance.html)
- [The Most Popular AWS Security Blog Posts in 2015](http://blogs.aws.amazon.com/security/post/Tx4QX7W51NDSLO/The-Most-Popular-AWS-Security-Blog-Posts-in-2015)
- [dzone: Private Subnets Are Broken on AWS](https://dzone.com/articles/private-subnets-are-broken-on-aws)
- [Amazon’s customer service backdoor](https://medium.com/@espringe/amazon-s-customer-service-backdoor-be375b3428c4#.qyixu5mu3)
- [Announcing Industry Best Practices for Securing AWS Resources](http://blogs.aws.amazon.com/security/post/Tx3PTTZB14FWPBA/Announcing-Industry-Best-Practices-for-Securing-AWS-Resources)
- [The Most Viewed AWS Security Blog Posts so Far in 2016](http://blogs.aws.amazon.com/security/post/Tx2N52FR8XGJVL3/The-Most-Viewed-AWS-Security-Blog-Posts-so-Far-in-2016)
- [Oracle Database Encryption Options on Amazon RDS](https://aws.amazon.com/es/blogs/apn/oracle-database-encryption-options-on-amazon-rds/)
- [Learn AWS Security Fundamentals with Free and Online Training](https://aws.amazon.com/about-aws/whats-new/2016/06/learn-aws-security-fundamentals-with-free-and-online-training)
- [How to Restrict Amazon S3 Bucket Access to a Specific IAM Role](http://blogs.aws.amazon.com/security/post/TxK5WUJK3DG9G8/How-to-Restrict-Amazon-S3-Bucket-Access-to-a-Specific-IAM-Role)
- [Updated Whitepaper Available: AWS Best Practices for DDoS Resiliency](http://blogs.aws.amazon.com/security/post/Tx6QAIBSQTJPHB/Updated-Whitepaper-Available-AWS-Best-Practices-for-DDoS-Resiliency)
- [AWS Security Blog: In Case You Missed These: AWS Security Blog Posts from June, July, and August 2016](http://blogs.aws.amazon.com/security/post/Tx3KVD6T490MM47/In-Case-You-Missed-These-AWS-Security-Blog-Posts-from-June-July-and-August)
- [Amazon Inspector Announces General Availability for Windows](https://aws.amazon.com/es/about-aws/whats-new/2016/08/amazon-inspector-announces-general-availability-for-windows/)
- [encrypt and decrypt data: Importing Key Material in AWS Key Management Service (AWS KMS)](https://docs.aws.amazon.com/kms/latest/developerguide/importing-keys.html) Use your own encryption keys with AWS Key Management Service.
- [Amazon s2n: AWS’s new Open Source implementation of the SSL/TLS network encryption protocols](http://blogs.aws.amazon.com/security/post/TxLEHNNDPUFDU9/Automated-Reasoning-and-Amazon-s2n)
- [dzone: 9 AWS Security Best Practices: Securing Your AWS Cloud](https://dzone.com/articles/9-aws-security-best-practices-securing-your-aws-cl) Working with Amazon facilities, it is necessary to implement AWS security best practices to ensure the safety of the data and the cloud.
- [Encrypt global data client-side with AWS KMS multi-Region keys](https://aws.amazon.com/blogs/security/encrypt-global-data-client-side-with-aws-kms-multi-region-keys/) Today, AWS Key Management Service (AWS KMS) is introducing multi-Region keys, a new capability that lets you replicate keys from one Amazon Web Services (AWS) Region into another. Multi-Region keys are designed to simplify management of client-side encryption when your encrypted data has to be copied into other Regions for disaster recovery or is replicated in Amazon DynamoDB global tables.
- [dzone: Removing the Bastion Host and Improving the Security in AWS](https://dzone.com/articles/removing-the-bastion-host-and-improving-the-securi) This article covers the security in AWS and overcoming the classic SSH/RDP jump with a better alternative for all OS.
- [acloudguru.com: How to audit and secure an AWS account](https://acloudguru.com/blog/engineering/how-to-audit-and-secure-an-aws-account)
- [yobyot.com: AWS multi-region KMS keys and Data Lifecycle Manager: better together](https://www.yobyot.com/aws/aws-multi-region-keys-and-ec2-data-lifecycle-manager/2021/08/18/)
- [try.jupiterone.com: The Absolute Minimum Every Developer Must Know about AWS Security](https://try.jupiterone.com/the-absolute-minimum-every-developer-must-know-about-aws-security)
- [==How to automate AWS account creation with SSO user assignment==](https://aws.amazon.com/blogs/security/how-to-automate-aws-account-creation-with-sso-user-assignment/)
- [Security practices in AWS multi-tenant SaaS environments](https://aws.amazon.com/blogs/security/security-practices-in-aws-multi-tenant-saas-environments/) Many good tips, from identity management to tenant isolation.

## Policy as Code with AWS CDK and Open Policy Agent
- [Realize Policy-as-Code with AWS Cloud Development Kit through Open Policy Agent 🌟](https://aws.amazon.com/blogs/opensource/realize-policy-as-code-with-aws-cloud-development-kit-through-open-policy-agent/)

## Payment Card Industry Data Security Standard compliance
- [PCI DSS Standardized Architecture on the AWS Cloud: Quick Start Reference Deployment](https://aws.amazon.com/about-aws/whats-new/2016/05/pci-dss-standardized-architecture-on-the-aws-cloud-quick-start-reference-deployment/)

## AWS IAM
- [AWS Identity and Access Management - Getting Started](http://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started.html)
- [AWS Identity and Access Management (IAM) best practices in 2016](http://blogs.aws.amazon.com/security/post/Tx2OB7YGHMB7WCM/Adhere-to-IAM-Best-Practices-in-2016)
- [How to Record and Govern Your IAM Resource Configurations Using AWS Config](http://blogs.aws.amazon.com/security/post/Tx14ADBJOCAT9NS/How-to-Record-and-Govern-Your-IAM-Resource-Configurations-Using-AWS-Config)
- [How to Use SAML to Automatically Direct Federated Users to a Specific AWS Management Console Page](http://blogs.aws.amazon.com/security/post/Tx2CGWIB8SBYW2J/How-to-Use-SAML-to-Automatically-Direct-Federated-Users-to-a-Specific-AWS-Manage)
- [New IAMCTL tool compares multiple IAM roles and policies](https://aws.amazon.com/es/blogs/security/new-iamctl-tool-compares-multiple-iam-roles-and-policies/)
- [Bring your own CLI to Session Manager with configurable shell profiles](https://aws.amazon.com/es/blogs/mt/bring-your-own-cli-session-manager-configurable-shell-profiles/)
- [keepler.io: Gestionando el control de accesos en nuestro data lake en AWS](https://keepler.io/2021/03/gestionando-el-control-de-accesos-en-nuestro-data-lake-en-aws/)
- [aws.amazon.com: IAM Access Analyzer now supports over 100 policy checks with actionable recommendations to help you author secure and functional policies](https://aws.amazon.com/about-aws/whats-new/2021/03/iam-access-analyzer-supports-over-100-policy-checks-with-actionable-recommendations/)
- [aws.amazon.com: IAM Access Analyzer Update – Policy Validation](https://aws.amazon.com/blogs/aws/iam-access-analyzer-update-policy-validation/)
- [netflixtechblog.com: ConsoleMe: A Central Control Plane for AWS Permissions and Access](https://netflixtechblog.com/consoleme-a-central-control-plane-for-aws-permissions-and-access-fd09afdd60a8) - [github.com/Netflix/consoleme](https://github.com/Netflix/consoleme)
- [cloudkatha.com: Difference between Root User and IAM User in AWS You Need to Know](https://cloudkatha.com/difference-between-root-user-and-iam-user-in-aws-you-need-to-know/)
- [ben11kehoe.medium.com: AWS Authentication: Principals (users and roles) in AWS IAM](https://ben11kehoe.medium.com/principals-in-aws-iam-38c4a3dc322a) this article uses the boto3, the AWS Python SDK, as an example, but other SDKs have analogous features.
- [infoq.com: Incorrect IAM Policy Raised Questions About AWS Access to S3 Data](https://www.infoq.com/news/2022/01/aws-iam-s3-access/)
- [==iann0036/iamlive==](https://github.com/iann0036/iamlive) Generate an IAM policy from AWS calls using client-side monitoring (CSM) or embedded proxy
- [==awsiam.info: AWS IAM Search==](https://www.awsiam.info)

## AWS Organizations
- [Simplifying permissions management at scale using tags in AWS Organizations](https://aws.amazon.com/blogs/mt/simplifying-permissions-management-at-scale-using-tags-in-aws-organizations/)
- [Standardize compliance in AWS using DevOps and a Cloud Center of Excellence (CCOE) approach](https://aws.amazon.com/blogs/mt/standardize-compliance-in-aws-using-devops-and-a-cloud-center-of-excellence-ccoe-approach/)

## AWS Control Tower
- [==AWS Control Tower==](https://aws.amazon.com/controltower/) The easiest way to set up and govern a secure multi-account AWS environment
- [==aws.amazon.com: New – AWS Control Tower Account Factory for Terraform==](https://aws.amazon.com/blogs/aws/new-aws-control-tower-account-factory-for-terraform/)
- [hashicorp.com: HashiCorp Teams with AWS on New Control Tower Account Factory for Terraform](https://www.hashicorp.com/blog/hashicorp-teams-with-aws-on-new-control-tower-account-factory-for-terraform) AWS Control Tower Account Factory for HashiCorp Terraform (AFT), the evolution of Terraform Landing Zones, offers an easy way to set up and govern a secure, multi-account AWS environment.

## AWS Firewalls
- [doit-intl.com: AWS Firewalls 101: How and when to use each one](https://blog.doit-intl.com/aws-firewalls-101-how-and-when-to-use-each-one-d4ad8087a6b3)
- [Automatically block suspicious traffic with AWS Network Firewall and Amazon GuardDuty](https://aws.amazon.com/es/blogs/security/automatically-block-suspicious-traffic-with-aws-network-firewall-and-amazon-guardduty)

## AWS WAF Web Application Firewall
- [AWS WAF - Web Application Firewall](https://aws.amazon.com/waf/)
- [How to Automatically Update Your Security Groups for Amazon CloudFront and AWS WAF by Using AWS Lambda (boto3 python)](http://blogs.aws.amazon.com/security/post/Tx1LPI2H6Q6S5KC/How-to-Automatically-Update-Your-Security-Groups-for-Amazon-CloudFront-and-AWS-W)
- [How to Use AWS WAF to Block IP Addresses That Generate Bad Requests](http://blogs.aws.amazon.com/security/post/Tx223ZW25YRPRKV/How-to-Use-AWS-WAF-to-Block-IP-Addresses-That-Generate-Bad-Requests)
- [How to Reduce Security Threats and Operating Costs Using AWS WAF and Amazon CloudFront](http://blogs.aws.amazon.com/security/post/Tx1G747SE1R2ZWE/How-to-Reduce-Security-Threats-and-Operating-Costs-Using-AWS-WAF-and-Amazon-Clou)
- [AWS WAF sample rules](https://github.com/awslabs/aws-waf-sample)
- [medium: Blocking bots using AWS WAF](https://medium.com/cloud-techies/blocking-bots-using-aws-waf-d449e6d159ca)
- [medium: Protecting your Web Application or APIs using AWS WAF](https://medium.com/avmconsulting-blog/protecting-your-web-application-or-apis-using-aws-waf-1829ff79275a)

## AWS Secrets Manager
- [How to replicate secrets in AWS Secrets Manager to multiple Regions](https://aws.amazon.com/blogs/security/how-to-replicate-secrets-aws-secrets-manager-multiple-regions/)
- [AWS Secrets Manager controller POC: an EKS operator for automatic rotation of secrets](https://aws.amazon.com/blogs/containers/aws-secrets-manager-controller-poc-an-eks-operator-for-automatic-rotation-of-secrets/)
- [k21academy.com: AWS Secrets Manager](https://k21academy.com/amazon-web-services/aws-solutions-architect/aws-secrets-manager/)

## AWS Vault
- [AWS Vault](https://github.com/99designs/aws-vault) is a tool to securely store and access AWS credentials in a development environment.
- [AWS: Sourcing AWS CLI Credentials using a Custom AWS CLI Credential Provider and AWS Vault](https://thomas.geens.be/2020/05/24/aws-sourcing-aws-cli-credentials-using-a-custom-aws-cli-credential-provider-and-aws-vault/)
