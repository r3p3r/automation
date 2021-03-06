# AWS CIS Foundations Benchmark v1.1.0 11-09-2016 remediation template

### Purpose

Automate the creation of the necessary resources to satify the CIS Foundations Benchmark monitoring (3.x) section.

* [AWS CIS Foundations Benchmark](https://d0.awsstatic.com/whitepapers/compliance/AWS_CIS_Foundations_Benchmark.pdf)

---

This CloudFormation template creates resources to remediate the following CIS Foundations Benchmark requirements:

#### Logging Section
- [x] 2.01 Ensure CloudTrail is enabled in all regions (Scored)
- [x] 2.02 Ensure CloudTrail log file validation is enabled (Scored)
- [x] 2.03 Ensure the S3 bucket CloudTrail logs to is not publicly accessible (Scored)
- [x] 2.04 Ensure CloudTrail trails are integrated with CloudWatch Logs (Scored)

#### Monitoring Section
- [x] 3.01 Ensure a log metric filter and alarm exist for unauthorized API calls (Scored)
- [x] 3.02 Ensure a log metric filter and alarm exist for Management Console sign-in without MFA (Scored)
- [x] 3.03 Ensure a log metric filter and alarm exist for usage of "root" account (Scored)
- [x] 3.04 Ensure a log metric filter and alarm exist for IAM policy changes (Scored)
- [x] 3.05 Ensure a log metric filter and alarm exist for CloudTrail configuration changes (Scored)
- [x] 3.06 Ensure a log metric filter and alarm exist for AWS Management Console authentication failures (Scored)
- [x] 3.07 Ensure a log metric filter and alarm exist for disabling or scheduled deletion of customer created CMKs (Scored)
- [x] 3.08 Ensure a log metric filter and alarm exist for S3 bucket policy changes (Scored)
- [x] 3.09 Ensure a log metric filter and alarm exist for AWS Config configuration changes (Scored)
- [x] 3.10 Ensure a log metric filter and alarm exist for security group changes (Scored)
- [x] 3.11 Ensure a log metric filter and alarm exist for changes to Network Access Control Lists (NACL) (Scored)
- [x] 3.12 Ensure a log metric filter and alarm exist for changes to network gateways (Scored)
- [x] 3.13 Ensure a log metric filter and alarm exist for route table changes (Scored)
- [x] 3.14 Ensure a log metric filter and alarm exist for VPC changes (Scored)
- [ ] 3.15 Ensure appropriate subscribers to each SNS topic (Not Scored)

