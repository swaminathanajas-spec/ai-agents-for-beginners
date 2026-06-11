Analyze these deployment-related repositories as one system:

- kubernetes
- infra-terraform
- keds
- kube-jobs
- pipeline injection
- pipeline consumer

Create a dependency map showing:

Repo | Purpose | Inputs | Outputs | Depends On | Used By | Owner Area

Explain:
- Which repo runs first
- Which repo creates infrastructure
- Which repo deploys workloads
- Which repo creates temporary environments
- Which repo runs batch/maintenance jobs
- Which repo modifies or injects CI/CD behavior
- Which repo consumes pipeline events

Use file references for every conclusion.
