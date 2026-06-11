Review the deployment system for ABC readiness.

Analyze all deployment-related repositories:

- kubernetes
- infra-terraform
- keds
- kube-jobs
- pipeline injection
- pipeline consumer

Identify gaps in:

- Build compatibility
- Kubernetes compatibility
- Terraform compatibility
- Network/DNS
- Secrets
- Certificates
- Container registry
- IAM/RBAC
- CI/CD standards
- Security scanning
- Observability
- Rollback
- Disaster recovery
- Documentation

Output:

Issue | Repo | Evidence | Impact | Priority | Recommended Fix | Owner | Open Question

Classify:
P0 – Blocks build/deployment
P1 – Blocks non-prod deployment
P2 – Blocks production readiness
P3 – Improvement
