# Future improvements

These extensions are proposed and are not implemented in the supplied evidence.

| Priority | Extension | Evidence needed for completion |
| --- | --- | --- |
| 1 | Recover AWS source and website assets | Reviewed files, manifests and attribution |
| 1 | Confirm credentials and role controls | Sanitised policy exports and credential handling code |
| 1 | Reconcile report output with database records | Schema, test data, SQL and matching reports |
| 1 | Verify cleanup in the implementation account | Same-account deletion records for each resource |
| 2 | Add a daily schedule | Scheduler configuration and dated runs |
| 2 | Make deployment reproducible | Infrastructure as code and verified steps |
| 2 | Verify TLS and network boundaries | Actual connection settings, routing and tests |
| 2 | Add monitoring and failure handling | Logs, alerts, failure tests and retries |
| 3 | Improve website delivery | Verified HTTPS hosting and access controls |
| 3 | Refresh GCP source snapshot | Reviewed dependencies and new deployment tests |

Cost comparisons, load testing, backup/restore exercises and accessibility checks could add useful evidence after source and configuration recovery. Record each extension as completed only after its artifacts and tests exist.
