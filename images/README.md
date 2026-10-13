# Screenshot index

All images are extracted evidence from the supplied university reports. Cropping removes unrelated UI; opaque masks remove identifiers. Statuses, error messages and output have not been fabricated. Original reports and unedited images are excluded.

| Screenshot | Source | What it shows | Publication edits |
| --- | --- | --- | --- |
| [s3-website-homepage](aws/s3-website-homepage.png) | AWS figure 1 | Cafe homepage rendered in browser | Crop |
| [s3-website-menu](aws/s3-website-menu.png) | AWS figure 2 | Cafe menu with loaded image assets | Crop |
| [s3-website-object-layout](aws/s3-website-object-layout.png) | AWS figure 5 | S3 website object layout | Crop |
| [s3-static-hosting-enabled](aws/s3-static-hosting-enabled.png) | AWS figure 6 | Static website hosting enabled | Crop; opaque privacy masks |
| [s3-public-access-settings](aws/s3-public-access-settings.png) | AWS figure 7 | Block all public access shown as Off | Crop |
| [s3-public-read-policy](aws/s3-public-read-policy.png) | AWS figure 8 | Public GetObject bucket policy | Crop; opaque privacy masks |
| [database-inbound-lambda-rule](aws/database-inbound-lambda-rule.png) | AWS figure 10 | TCP 3306 database rule with LambdaSG source | Crop; opaque privacy masks |
| [rds-mariadb-available](aws/rds-mariadb-available.png) | AWS figure 12 | RDS MariaDB instance Available | Crop |
| [sns-email-subscription-confirmed](aws/sns-email-subscription-confirmed.png) | AWS figure 15 | SNS EMAIL subscription Confirmed | Crop; opaque privacy masks |
| [lambda-python-runtime](aws/lambda-python-runtime.png) | AWS figure 17 | Extractor Python 3.11 runtime and handler | Crop; opaque privacy masks |
| [lambda-extractor-test](aws/lambda-extractor-test.png) | AWS figure 18 | dbTest successful execution | Crop |
| [lambda-report-test](aws/lambda-report-test.png) | AWS figure 20 | salesReportTest 200 and sent message | Crop |
| [sns-report-pastries](aws/sns-report-pastries.png) | AWS figure 21 | SNS report in quarantine: pastries | Crop; opaque privacy masks |
| [sns-report-drinks-desserts](aws/sns-report-drinks-desserts.png) | AWS figure 22 | SNS report continuation: drinks and desserts | Crop; opaque privacy masks |
| [app-engine-region-created](gcp/app-engine-region-created.png) | GCP embedded image 7 | App Engine creation completed in Australia region | Crop; opaque privacy masks |
| [shell-error-and-file-editing](gcp/shell-error-and-file-editing.png) | GCP embedded image 8 | Shell return error and file editing | Crop; opaque privacy masks |
| [flask-source-and-app-config](gcp/flask-source-and-app-config.png) | GCP embedded image 9 | Flask source, pins and App Engine config | Crop; opaque privacy masks |
| [app-engine-deployment-result](gcp/app-engine-deployment-result.png) | GCP embedded image 10 | Default service deployment completed | Crop; opaque privacy masks |
| [hello-web-output](gcp/hello-web-output.png) | GCP embedded image 11 | Hello browser output | Crop; opaque privacy masks |

The GCP output retains the original Hello text while masking its identifier. The published Python source replaces that identifier with no suffix; the original screenshot is not altered to imitate the sanitised source.

See [evidence register](../docs/evidence.md) for all reviewed images and [security notes](../docs/security.md) for the publication policy.
