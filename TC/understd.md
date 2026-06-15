I want to understand the end-to-end CI/CD process used by this workspace.

Context:
- TeamCity is used for build and deployment jobs.
- I can see TeamCity templates, steps, and scripts.
- The application repo contains a train.yaml file used in the build process.
- I have cloned the application repo, config repo, GitOps deployment repo, and supporting script/tooling repos into this VS Code workspace.

Please analyze the full workspace and explain the CI/CD flow end to end.

Focus on:
1. What triggers the build?
2. How TeamCity reads or uses train.yaml.
3. Which scripts are executed from TeamCity templates.
4. Where those scripts live in the workspace.
5. What each script does.
6. How application source code is built.
7. How artifacts/images/packages are created.
8. Where build outputs are published.
9. How deployment is triggered.
10. How config repo and GitOps repo are used.
11. Which deployment files are modified or consumed.
12. How environment-specific values are selected.
13. How Kubernetes/Helm/YAML manifests are generated or applied.
14. What is the sequence from code commit to deployment.
15. What approvals, gates, or manual steps exist.
16. What external systems are involved.

Please produce:
- A high-level architecture summary.
- A step-by-step sequence flow.
- A repo-by-repo responsibility breakdown.
- A file-by-file explanation for important CI/CD files.
- A Mermaid sequence diagram.
- A Mermaid flowchart.
- A list of unknowns or assumptions.
- Questions I should ask my team to confirm the process.
