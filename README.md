# AWS Audit Scripts

You should install awscli and jq before using these. Most of these will accept
input from STDIN, making them amenable to receiving piped input.

| Script        | Purpose       |
| ------------- |:-------------:|
| iam_inline_policies_in_use.sh | Find if IAM inline policies are in use and if so, where and how many. |
| s3_buckets_logging_disabled.sh | Find S3 buckets with access logging disabled. |
| rds_instance_unencrypted_storage.sh | Find RDS instances using unencrypted storage. |
