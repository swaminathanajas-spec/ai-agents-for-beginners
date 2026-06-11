Analyze the kubernetes repository in detail.

Identify all Kubernetes resources:

- Namespace
- Deployment
- StatefulSet
- DaemonSet
- Service
- Ingress
- ConfigMap
- Secret
- ServiceAccount
- Role/ClusterRole
- RoleBinding/ClusterRoleBinding
- CronJob
- Job
- HorizontalPodAutoscaler
- PodDisruptionBudget
- NetworkPolicy
- PersistentVolumeClaim
- ExternalSecret
- Gateway/VirtualService if service mesh exists

For each resource provide:

Resource | File | Purpose | Environment | App Component | Dependencies | Risk

Explain:
- How manifests are organized
- Whether Helm/Kustomize/plain YAML is used
- How environment-specific overlays work
- How image tags are injected
- How config and secrets are injected
- How rollout is performed
- How health checks are configured
- How traffic reaches the pods
