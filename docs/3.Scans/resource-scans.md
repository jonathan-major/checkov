---
layout: default
title: Resource scans
nav_order: 1
---

# Resource scans (auto generated)

|    | Id          | Type     | Entity                            | Policy                                                                                                           |
|----|-------------|----------|-----------------------------------|------------------------------------------------------------------------------------------------------------------|
|  0 | CKV_AWS_29  | resource | aws_elasticache_replication_group | Ensure all data stored in the Elasticache Replication Group  is securely encrypted at rest                       |
|  1 | CKV_AWS_31  | resource | aws_elasticache_replication_group | Ensure all data stored in the Elasticache Replication Group  is securely encrypted at transit and has auth token |
|  2 | CKV_AWS_30  | resource | aws_elasticache_replication_group | Ensure all data stored in the Elasticache Replication Group  is securely encrypted at transit                    |
|  3 | CKV_AWS_11  | resource | aws_iam_account_password_policy   | Ensure IAM password policy requires at least one lowercase letter                                                |
|  4 | CKV_AWS_10  | resource | aws_iam_account_password_policy   | Ensure IAM password policy requires minimum length of 14 or greater                                              |
|  5 | CKV_AWS_14  | resource | aws_iam_account_password_policy   | Ensure IAM password policy requires at least one symbol                                                          |
|  6 | CKV_AWS_13  | resource | aws_iam_account_password_policy   | Ensure IAM password policy prevents password reuse                                                               |
|  7 | CKV_AWS_15  | resource | aws_iam_account_password_policy   | Ensure IAM password policy requires at least one uppercase letter                                                |
|  8 | CKV_AWS_12  | resource | aws_iam_account_password_policy   | Ensure IAM password policy requires at least one number                                                          |
|  9 | CKV_AWS_9   | resource | aws_iam_account_password_policy   | Ensure IAM password policy expires passwords within 90 days or less                                              |
| 10 | CKV_AWS_26  | resource | aws_sns_topic                     | Ensure all data stored in the SNS topic is encrypted                                                             |
| 11 | CKV_AWS_21  | resource | aws_s3_bucket                     | Ensure all data stored in the S3 bucket have versioning enabled                                                  |
| 12 | CKV_AWS_20  | resource | aws_s3_bucket                     | S3 Bucket has an ACL defined which allows public access.                                                         |
| 13 | CKV_AWS_18  | resource | aws_s3_bucket                     | Ensure the S3 bucket has access logging enabled                                                                  |
| 14 | CKV_AWS_19  | resource | aws_s3_bucket                     | Ensure all data stored in the S3 bucket is securely encrypted at rest                                            |
| 15 | CKV_AWS_35  | resource | aws_cloudtrail                    | Ensure CloudTrail logs are encrypted at rest using KMS CMKs                                                      |
| 16 | CKV_AWS_36  | resource | aws_cloudtrail                    | Ensure CloudTrail log file validation is enabled                                                                 |
| 17 | CKV_AWS_34  | resource | aws_cloudfront_distribution       | Ensure cloudfront distribution ViewerProtocolPolicy is set to HTTPS                                              |
| 18 | CKV_AWS_3   | resource | aws_ebs_volume                    | Ensure all data stored in the EBS is securely encrypted                                                          |
| 19 | CKV_AWS_28  | resource | aws_dynamodb_table                | Ensure Dynamodb point in time recovery (backup) is enabled                                                       |
| 20 | CKV_AWS_5   | resource | aws_elasticsearch_domain          | Ensure all data stored in the Elasticsearch is securely encrypted at rest                                        |
| 21 | CKV_AWS_6   | resource | aws_elasticsearch_domain          | Ensure all Elasticsearch has node-to-node encryption enabled                                                     |
| 22 | CKV_AWS_25  | resource | aws_security_group                | Ensure no security groups allow ingress from 0.0.0.0:0 to port 3389                                              |
| 23 | CKV_AWS_24  | resource | aws_security_group                | Ensure no security groups allow ingress from 0.0.0.0:0 to port 22                                                |
| 24 | CKV_AWS_23  | resource | aws_security_group                | Ensure every security groups rule has a description                                                              |
| 25 | CKV_AWS_17  | resource | aws_db_instance                   | Ensure all data stored in the RDS bucket is not public accessible                                                |
| 26 | CKV_AWS_16  | resource | aws_db_instance                   | Ensure all data stored in the RDS is securely encrypted at rest                                                  |
| 27 | CKV_AWS_17  | resource | aws_rds_cluster_instance          | Ensure all data stored in the RDS bucket is not public accessible                                                |
| 28 | CKV_AWS_27  | resource | aws_sqs_queue                     | Ensure all data stored in the SQS queue  is encrypted                                                            |
| 29 | CKV_AWS_4   | resource | aws_ebs_snapshot                  | Ensure all data stored in the EBS Snapshot is securely encrypted                                                 |
| 30 | CKV_AWS_32  | resource | aws_ecr_repository_policy         | Ensure ECR policy is not set to public                                                                           |
| 31 | CKV_AWS_8   | resource | aws_launch_configuration          | Ensure all data stored in the Launch configuration EBS is securely encrypted                                     |
| 32 | CKV_AWS_8   | resource | aws_instance                      | Ensure all data stored in the Launch configuration EBS is securely encrypted                                     |
| 33 | CKV_AWS_2   | resource | aws_alb_listener                  | Ensure ALB protocol is HTTPS                                                                                     |
| 34 | CKV_AWS_2   | resource | aws_lb_listener                   | Ensure ALB protocol is HTTPS                                                                                     |
| 35 | CKV_AWS_33  | resource | aws_ecr_repository                | Ensure ECR image scanning on push is enabled                                                                     |
| 36 | CKV_AWS_23  | resource | aws_security_group_rule           | Ensure every security groups rule has a description                                                              |
| 37 | CKV_AWS_23  | resource | aws_db_security_group             | Ensure every security groups rule has a description                                                              |
| 38 | CKV_AWS_23  | resource | aws_elasticache_security_group    | Ensure every security groups rule has a description                                                              |
| 39 | CKV_AWS_23  | resource | aws_redshift_security_group       | Ensure every security groups rule has a description                                                              |
| 40 | CKV_AWS_7   | resource | aws_kms_key                       | Ensure rotation for customer created CMKs is enabled                                                             |
| 41 | CKV_AWS_22  | resource | aws_sagemaker_notebook_instance   | Ensure all data stored in the Sagemaker is securely encrypted at rest                                            |
| 42 | CKV_GCP_7   | resource | google_container_cluster          | Ensure Legacy Authorization is set to Disabled on Kubernetes Engine Clusters                                     |
| 43 | CKV_GCP_8   | resource | google_container_cluster          | Ensure Stackdriver Monitoring is set to Enabled on Kubernetes Engine Clusters                                    |
| 44 | CKV_GCP_12  | resource | google_container_cluster          | Ensure Network Policy is enabled on Kubernetes Engine Clusters                                                   |
| 45 | CKV_GCP_13  | resource | google_container_cluster          | Ensure a client certificate is used by clients to authenticate to Kubernetes Engine Clusters                     |
| 46 | CKV_GCP_1   | resource | google_container_cluster          | Ensure Stackdriver Logging is set to Enabled on Kubernetes Engine Clusters                                       |
| 47 | CKV_GCP_3   | resource | google_compute_firewall           | Ensure Google compute firewall ingress does not allow unrestricted rdp access                                    |
| 48 | CKV_GCP_2   | resource | google_compute_firewall           | Ensure Google compute firewall ingress does not allow unrestricted ssh access                                    |
| 49 | CKV_GCP_9   | resource | google_container_node_pool        | Ensure 'Automatic node repair' is enabled for Kubernetes Clusters                                                |
| 50 | CKV_GCP_10  | resource | google_container_node_pool        | Ensure 'Automatic node upgrade' is enabled for Kubernetes Clusters                                               |
| 51 | CKV_GCP_6   | resource | google_sql_database_instance      | Ensure all Cloud SQL database instance requires all incoming connections to use SSL                              |
| 52 | CKV_GCP_11  | resource | google_sql_database_instance      | Ensure that Cloud SQL database Instances are not open to the world                                               |
| 53 | CKV_GCP_5   | resource | google_storage_bucket             | Ensure Google storage bucket have encryption enabled                                                             |
| 54 | CKV_GCP_4   | resource | google_compute_ssl_policy         | Ensure Google SSL policy minimal TLS version is TLS_1_2                                                          |
| 55 | CKV_AZURE_3 | resource | azurerm_storage_account           | Ensure that 'Secure transfer required' is set to 'Enabled'                                                       |
| 56 | CKV_AZURE_2 | resource | azurerm_managed_disk              | Ensure Azure managed disk have encryption enabled                                                                |
| 57 | CKV_AZURE_1 | resource | azurerm_virtual_machine           | Ensure Azure Instance does not use basic authentication(Use SSH Key Instead)                                     |
| 58 | CKV_AWS_1   | data     | aws_iam_policy_document           | Ensure IAM policies that allow full "*-*" administrative privileges are not created                              |


---


