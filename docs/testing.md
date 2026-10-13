# Testing and evidence limits

## Historical checks

| Check | Source observation | Confidence boundary |
| --- | --- | --- |
| S3 frontend | Homepage, menu, about and visit views | Rendered at capture time; endpoint not retested |
| S3 configuration | Object paths, hosting enabled, policy and access settings | Captured settings; no complete export |
| RDS | cafe-db Available with MariaDB engine | Provisioning status only |
| Database rule | TCP 3306 with LambdaSG source | Rule editor and group creation shown; full topology absent |
| Lambda extractor | dbTest Succeeded, partly visible 200 | Successful test; exact SQL and output unavailable |
| Lambda reporter | salesReportTest Succeeded, 200, sent message | Successful test; full code unavailable |
| SNS | Standard topic; EMAIL subscription Confirmed | Notification setup established |
| Report receipt | SNS sender and sales quantities in quarantine | Arrival demonstrated; inbox delivery and reconciliation absent |
| GCP App Engine | Region creation completed; deployed default service | Historical deployment completed |
| GCP output | Browser shows Hello plus student identifier | Historical response visible; identifier masked |

Function tests were console invocations. A report titled Daily Sales Analysis Report does not establish scheduled daily execution. Figures shown are lab output; no database dump was provided for comparison.

## Missing artifacts

- Complete salesAnalysisReportDataExtractor and salesAnalysisReport source, dependency manifests and deployment archives.
- Original cafe index.html, CSS and image assets, plus attribution or licence information.
- Database schema, seed data, SQL queries and complete extractor output.
- Invocation/data exchange configuration between the two Lambda functions.
- Lambda execution-role policies, environment configuration and credential storage evidence.
- Lambda VPC/subnet configuration, RDS subnet group, routing, outbound rules and endpoint/NAT configuration.
- Scheduler configuration and execution history proving automatic daily runs.
- Full logs and database reconciliation confirming reported quantities.
- Same-account deletion evidence for the implemented RDS instance and other AWS resources.
- Email release/inbox confirmation, performance testing, cost measurements, backup/restore evidence and monitoring.
- Original GCP source files; published files are transcriptions of visible screenshot content.

These omissions allow a documentation portfolio but prevent a claim that the repository reproduces the complete AWS system.

## Portfolio packaging validation

Checks cover relative file/image links, image decoding and metadata, Markdown structure, recovered Python syntax, policy JSON, sensitive identifier patterns and ZIP contents. Both reports and all 35 embedded images were reviewed; 19 selected images are included. No live cloud resources were accessed or changed.

See [packaging results](packaging-validation.md).
