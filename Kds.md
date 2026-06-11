Analyze the keds / Kubernetes Ephemeral Deployment System repository.

Explain:

1. What triggers ephemeral environment creation
2. What input it receives
3. How environment name/namespace is generated
4. What Kubernetes resources are created
5. How image tags/branches/PR numbers are mapped
6. How DNS/Ingress is created
7. How secrets/config are copied or generated
8. How database dependencies are handled
9. How cleanup/delete works
10. Timeout/TTL behavior
11. Failure handling and retry behavior

Output:

Step | Trigger | Code/File | Action | Output | Failure Case

Also generate a Mermaid sequence diagram showing PR/build → ephemeral environment → validation → cleanup.
