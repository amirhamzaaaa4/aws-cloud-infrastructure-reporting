# S3 policy snapshot

[Policy example](s3-website-public-read-policy.example.json) transcribes the policy in AWS report image 8. The bucket name is replaced with example-public-cafe-website. Version, Sid, Effect, Principal, Action and wildcard object scope match the screenshot.

This example describes intentional public website reads. It grants all principals GetObject for all bucket objects and is unsuitable for private data. It does not configure hosting, account-level access settings or a complete deployment. It contains no real account identifier or credentials.

No IAM role, database credential or security group configuration file was supplied. None has been fabricated as a deployable example.
