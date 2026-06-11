Trace the full deployment flow across all repositories.

Start from:
Developer commits code / opens PR

End at:
Application running in Kubernetes

Include:

1. PR validation
2. Build
3. Test
4. Docker image build
5. Image push
6. Pipeline injection
7. Pipeline event consumption
8. Terraform dependency
9. Kubernetes manifest generation
10. Secret/config resolution
11. Deployment rollout
12. Health check
13. Ephemeral environment creation
14. Promotion to stable environment
15. Rollback

Output:
- Step-by-step flow
- Responsible repo for each step
- File evidence
- Commands/scripts involved
- Failure points
- Manual approvals
- Mermaid sequence diagram
