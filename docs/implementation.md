# Implementation

This account describes historical academic work recorded in the reports. It is not an exact deployment runbook: complete AWS code and configuration exports are missing.

## S3 website

1. Website files were extracted and uploaded to a bucket in us-east-1.
2. The object layout retained index.html, css/ and images/.
3. Static website hosting was enabled.
4. Block all public access was shown as Off. A policy allowed public s3:GetObject on website bucket objects.
5. Browser captures show the homepage and menu with loaded assets. About and visit views were also reviewed in the source report.

The [policy snapshot](../config/aws/s3-website-public-read-policy.example.json) is transcribed from the visible policy, with a replacement bucket name. Original HTML/CSS files were not embedded as attachments and cannot be recovered as full source from screenshots.

## Database and access controls

1. LambdaSG was created for reporting functions.
2. DatabaseSG was created for the cafe database.
3. A MySQL/Aurora TCP 3306 inbound rule was configured with LambdaSG as source.
4. The cafe-db RDS MariaDB instance reached Available status.
5. Connection information was consulted, showing an instance endpoint and a console-generated MySQL connection command.

The connection-command screenshot is not published because its endpoint and database username are unnecessary. The console command is not evidence that Lambda used the same connection or TLS options.

## Lambda and SNS

1. The extractor was configured with Python 3.11, x86_64 and the displayed module.lambda_handler setting.
2. Visible code uses pymysql.connect and catches pymysql.Error. The editor tree shows packaged PyMySQL files; complete source is not visible.
3. dbTest produced a successful execution and partly visible 200 response.
4. SalesReportTopic was created as an SNS Standard topic with display name Sales Report.
5. An email subscription was confirmed.
6. salesAnalysisReport was created and updated. salesReportTest succeeded with 200 and the report-sent response.
7. The report was inspected in the university email quarantine portal.

These establish discrete configuration and test milestones. Full IAM policies, credentials, SQL, data exchange between functions and schedule configuration were not supplied.

## GCP exercise

Cloud Shell was used to create the App Engine application with gcloud app create, select australia-southeast1, create or edit main.py, requirements.txt and app.yaml, and deploy the default service. Screenshot-transcribed files are in [src/gcp-hello](../src/gcp-hello/README.md). Later browser output supports a successful historical deployment.

## Contribution statement

The AWS report attributes static website evidence, AWS implementation evidence and report documentation to the portfolio owner. The reports name the same student author. Group member identifiers and assessment contribution percentages are excluded. No authorship claim is made for unavailable website assets or unseen Lambda source.
