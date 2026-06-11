Analyze the kube-jobs repository.

Identify all Kubernetes jobs and scheduled jobs.

For each job:

Job Name | File | Trigger | Image | Command | Inputs | Outputs | Secrets | Schedule | Failure Handling

Explain:
- Whether jobs are manual, scheduled, pipeline-triggered, or event-driven
- Which jobs are required before deployment
- Which jobs are post-deployment
- Which jobs are maintenance/admin jobs
- Which jobs are data migration jobs
- How job logs are collected
- How job success/failure is validated
- How reruns are handled
