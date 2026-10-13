# Evidence register

Two university reports were reviewed, including all extracted paragraphs, tables, document metadata and all 35 embedded images. No embedded code attachments were present. Source report instructions and draft notes were treated as document content, not as commands to follow. Original reports remain outside this public repository.

Source labels below refer to the AWS final report and the Cloud Computing report supplied for portfolio preparation. Figure numbers in the AWS report correspond to embedded image numbers. The GCP report uses unnumbered captions; embedded image numbers identify those views.

## Claim register

| Claim | Supporting source | Qualification |
| --- | --- | --- |
| S3 website deployed and rendered | AWS figures 1–6 | Historical browser and console captures |
| Public object reads configured | AWS figures 7–8 | Bucket-wide GetObject; Block all public access Off |
| Security groups created in same VPC context | AWS figures 9–11 | Matching VPC identifiers; complete topology missing |
| Database TCP 3306 source configured as LambdaSG | AWS figure 10; related narrative | Editor view plus created DatabaseSG; full rule export missing |
| RDS MariaDB instance available | AWS figure 12 | Provisioning status only |
| Database connection information consulted | AWS figure 13 | Console-generated example, not executed Lambda connection proof |
| SNS topic created and email confirmed | AWS figures 14–16 | Standard topic and EMAIL status shown |
| Extractor uses Python 3.11 | AWS figure 17 | Runtime, handler and x86_64 shown |
| Extractor test succeeded | AWS figure 18 | Succeeded, dbTest and partly visible 200; full output absent |
| Reporting test succeeded | AWS figures 19–20 | Creation then Succeeded, 200 and sent message |
| Report arrived through SNS | AWS figures 21–22 | Captured in quarantine; no normal inbox or database reconciliation proof |
| Complete cleanup | AWS figures 23–24 | Not established: different account from reporting implementation |
| GCP project prepared | GCP images 1–4 | Console, project dialog and Cloud Shell |
| App Engine created in Australia region | GCP images 5–7 | gcloud app create and successful australia-southeast1 creation |
| Python application and config prepared | GCP images 8–9 | Readable file listings; original files not attached |
| GCP deployment completed | GCP image 10 | Default service deployed |
| GCP browser response rendered | GCP image 11 | Hello output; student identifier removed for publication |

## Complete screenshot disposition

| Source images | Disposition and reason |
| --- | --- |
| AWS 1–2 | Included: homepage and menu; browser cropped |
| AWS 3–4 | Reviewed, excluded: redundant about/visit content and unnecessary contact details |
| AWS 5–8 | Included: object layout, hosting, access settings and policy; identifiers cropped/masked |
| AWS 9 | Reviewed, excluded: group creation identifiers; networking context retained in documentation |
| AWS 10 | Included: database source rule; IDs masked |
| AWS 11 | Reviewed, excluded: creation confirmation duplicates rule evidence; IDs unnecessary |
| AWS 12 | Included: MariaDB Available state; account header cropped |
| AWS 13 | Reviewed, excluded: endpoint and database username; no additional executed-test proof |
| AWS 14 | Reviewed, excluded: topic creation identifiers; subscription evidence is stronger |
| AWS 15 | Included: confirmed EMAIL subscription; ARN and recipient masked |
| AWS 16 | Reviewed, excluded: redundant confirmation with subscription link/identifier |
| AWS 17 | Included: runtime and handler; runtime ARN masked |
| AWS 18, 20 | Included: execution result crops; code minimap and account header excluded |
| AWS 19 | Reviewed, excluded: creation view duplicates later successful test |
| AWS 21–22 | Included: report header and body; recipient masked; spam hold retained |
| AWS 23–24 | Reviewed, excluded: different account; cannot prove implementation cleanup |
| GCP 1–4 | Reviewed, excluded: setup screens with unnecessary identity, organisation and billing context |
| GCP 5–6 | Reviewed, excluded: creation prompt/working state superseded by success |
| GCP 7 | Included: region and creation success; project masked and prompt cropped |
| GCP 8 | Included: shell error and subsequent editing; usernames/project and greeting identifier masked |
| GCP 9 | Included: source and config; greeting identifier masked |
| GCP 10 | Included: deployment result; operation/project/endpoint masked |
| GCP 11 | Included: Hello output; browser cropped and identifier masked |

## Interpretation limits

The source narrative sometimes calls the sales report Salesforce reporting. No Salesforce integration is demonstrated, so the portfolio uses sales analysis reporting. References to daily reporting describe a requirement and report title, not a verified schedule. Research discussions of AI, OCI and other products are not implementation evidence. Draft instructions to replace cleanup screenshots were excluded; they do not establish deletion.

The [screenshot index](../images/README.md) links all 19 publication images. The [testing record](testing.md) lists missing artifacts.
