# Security and privacy

## Controls visible in the evidence

The S3 policy permits s3:GetObject rather than write actions. Its scope covers every object in the website bucket. Block all public access was Off. This is intentional public static hosting, not a private storage design. The HTTP endpoint shown in the source is a transport limitation.

The database rule selects LambdaSG as source for TCP 3306. This demonstrates restricted source selection compared with an unrestricted CIDR, but only the displayed rule and narrative are available. The complete effective network configuration was not independently audited.

The initial LambdaSG screenshot shows zero inbound rules. That is an observed configuration, not proof of full database isolation or credential security. IAM database authentication was shown as Disabled in the RDS connection view. Custom execution-role policies were not supplied.

## Unknowns

There is no evidence of Secrets Manager integration, secret rotation, least-privilege Lambda roles, Lambda-to-RDS TLS enforcement, database encryption settings, backup retention or continuous monitoring. These must not be represented as implemented controls.

## Publication treatment

The repository was rebuilt from selected evidence rather than distributing original documents. This excludes Word author metadata, assessment cover pages, submission details, student IDs, other students' information and unrelated reference material.

Screenshots were cropped and, where necessary, covered with opaque masks. Masks remove account numbers, ARNs, subscription identifiers, resource IDs, private endpoints, recipient details, terminal usernames and the GCP greeting identifier. Relevant values, statuses and errors remain visible. No screenshot was regenerated, and redacted text was not replaced with a fabricated success value.

The GCP code greeting is changed to Hello solely to remove a student identifier. The S3 policy uses a labelled replacement bucket name. No original reports, raw images, hidden image layers, cloud credentials or live private configuration files are included. PNGs were re-encoded without source metadata.

This is an artifact privacy check, not a live cloud security audit. Future screenshots and code require their own review before committing.

## Future improvements

Recover role policies and full code, review credential handling, verify actual transport settings and export complete network configuration. Scheduling, monitoring and infrastructure as code can then be added with separate evidence. See [future improvements](future-improvements.md).
