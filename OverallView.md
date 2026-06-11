Act as a Principal Enterprise Architect, Platform Architect, DevOps Architect, Kubernetes Architect, Cloud Architect, Security Architect, and Network Architect.

Context:

I have already analyzed all repositories and generated architecture documentation.

Repositories include:

- Application repositories
- Kubernetes repositories
- Infrastructure/Terraform repositories
- Deployment orchestration repositories
- CI/CD repositories
- Ephemeral deployment repositories
- Job execution repositories
- Pipeline injection repositories
- Pipeline consumer repositories

I want a COMPLETE multi-layer architecture model of the entire platform.

Do not summarize.

Act as if creating architecture documentation for onboarding a new Principal Engineer, Distinguished Engineer, or Platform Architect.

OBJECTIVE

Create a multi-layer architecture blueprint covering:

1. Business Architecture
2. Application Architecture
3. Service Architecture
4. Integration Architecture
5. CI/CD Architecture
6. Container Architecture
7. Kubernetes Architecture
8. Infrastructure Architecture
9. Cloud Architecture
10. Security Architecture
11. Network Architecture
12. Data Architecture
13. Observability Architecture
14. Open Source Dependency Architecture
15. Runtime Architecture
16. OSI Layer Mapping

Use all available repository findings and documentation.

Always cite source repositories/files where evidence exists.

======================================================================
SECTION 1 - SYSTEM CONTEXT DIAGRAM
======================================================================

Generate a Level-0 diagram showing:

- Users
- Applications
- External Systems
- CI/CD Systems
- Cloud Services
- Databases
- Queues
- Storage
- Monitoring Systems

Provide:

- Mermaid diagram
- PlantUML diagram
- ASCII architecture view

======================================================================
SECTION 2 - BUSINESS CAPABILITY MAP
======================================================================

Create a mapping:

Business Capability
→ Application
→ Service
→ Repository
→ Owner
→ Criticality

======================================================================
SECTION 3 - APPLICATION ARCHITECTURE
======================================================================

Generate diagrams showing:

- UI
- APIs
- Microservices
- Workers
- Jobs
- Schedulers
- Databases
- External APIs

For each component provide:

- Purpose
- Technology
- Runtime
- Dependencies
- Environment

======================================================================
SECTION 4 - END TO END REQUEST FLOW
======================================================================

Trace:

User Request
→ DNS
→ WAF
→ Load Balancer
→ Ingress
→ Service
→ Pod
→ API
→ Database
→ Queue
→ Worker
→ Response

Generate:

- Sequence diagrams
- Communication diagrams
- Dependency diagrams

Show exact protocols and ports where known.

======================================================================
SECTION 5 - CI/CD ARCHITECTURE
======================================================================

Create detailed flow:

Developer
→ Git
→ Pull Request
→ Validation
→ Build
→ Test
→ Security Scan
→ Docker Build
→ Registry
→ Deployment
→ Kubernetes
→ Monitoring

Show:

- Repositories involved
- Pipelines involved
- Build agents
- Artifacts generated
- Promotion process
- Rollback process
- Security controls

======================================================================
SECTION 6 - CONTAINER ARCHITECTURE
======================================================================

Show:

- Docker images
- Base images
- Image hierarchy
- Container startup sequence
- Entrypoints
- Ports
- Volumes
- Secrets
- Environment variables

Generate image dependency diagrams.

======================================================================
SECTION 7 - KUBERNETES ARCHITECTURE
======================================================================

Generate diagrams for:

- Namespaces
- Deployments
- StatefulSets
- Services
- Ingresses
- CronJobs
- Jobs
- HPA
- RBAC
- ConfigMaps
- Secrets
- NetworkPolicies
- Service Accounts
- Persistent Volumes

Show runtime relationships and startup order.

======================================================================
SECTION 8 - INFRASTRUCTURE ARCHITECTURE
======================================================================

Generate:

Terraform module hierarchy

Show:

- VPC
- Subnets
- Route Tables
- Security Groups
- DNS
- Load Balancers
- Clusters
- Databases
- Storage
- Queues
- IAM Roles
- Monitoring Infrastructure

Generate infrastructure dependency graph.

======================================================================
SECTION 9 - NETWORK ARCHITECTURE
======================================================================

Create Layer 3, Layer 4, and Layer 7 views.

Show:

- Client
- DNS
- WAF
- CDN
- Load Balancer
- API Gateway
- Ingress
- Service Mesh
- Pod Network
- Database Network

Generate:

- Network flow diagram
- Firewall diagram
- Trust boundary diagram

Identify ingress and egress traffic.

======================================================================
SECTION 10 - OSI MODEL MAPPING
======================================================================

Create an architecture matrix.

Map every major component to OSI layers.

Layer 7 - Application
- UI
- APIs
- Services
- Webhooks

Layer 6 - Presentation
- JSON
- REST
- gRPC
- TLS termination

Layer 5 - Session
- OAuth
- OpenID Connect
- Session handling

Layer 4 - Transport
- TCP
- UDP
- HTTP/2
- gRPC transport

Layer 3 - Network
- VPC
- Routing
- Subnets
- Network Policies

Layer 2 - Data Link
- Container networking
- Overlay networking
- CNI plugins

Layer 1 - Physical
- Cloud infrastructure
- Worker nodes
- Virtual machines
- Storage devices

Generate:

- OSI Architecture Diagram
- OSI Interaction Matrix

======================================================================
SECTION 11 - DEPENDENCY ARCHITECTURE
======================================================================

Create complete inventory:

- Open-source libraries
- Frameworks
- SDKs
- Package managers
- Runtimes

Output:

Dependency
Version
Repository
Purpose
Used By
Risk
License

Generate dependency graph.

======================================================================
SECTION 12 - SECURITY ARCHITECTURE
======================================================================

Show:

- Authentication
- Authorization
- Secrets
- Certificates
- IAM
- RBAC
- Network Policies
- Encryption
- Key Management

Generate trust boundaries.

Identify:

- Data flow boundaries
- Security zones
- External access points

======================================================================
SECTION 13 - OBSERVABILITY ARCHITECTURE
======================================================================

Show:

- Logs
- Metrics
- Tracing
- Alerts
- Dashboards

Map:

Application
→ Container
→ Kubernetes
→ Infrastructure

Show data collection flow.

======================================================================
SECTION 14 - DEPLOYMENT LIFECYCLE
======================================================================

Create sequence diagrams showing:

Commit
→ Build
→ Scan
→ Package
→ Publish
→ Deploy
→ Verify
→ Monitor
→ Rollback

Identify:

- Tools
- Repositories
- Scripts
- Pipelines

======================================================================
SECTION 15 - RUNTIME STARTUP SEQUENCE
======================================================================

Show:

Infrastructure startup
→ Cluster startup
→ Service startup
→ Dependency startup
→ Application startup

Include:

- Readiness checks
- Health checks
- Dependency ordering
- Failure scenarios

======================================================================
SECTION 16 - ARCHITECTURE RISKS
======================================================================

Generate:

- Single points of failure
- Dependency risks
- Operational risks
- Security risks
- Scalability risks
- Observability gaps
- Disaster recovery gaps

======================================================================
DELIVERABLES
======================================================================

Produce:

1. Executive Architecture Diagram
2. Enterprise Architecture Diagram
3. Application Architecture Diagram
4. Integration Architecture Diagram
5. Network Architecture Diagram
6. OSI Layer Diagram
7. Kubernetes Architecture Diagram
8. CI/CD Architecture Diagram
9. Infrastructure Diagram
10. Security Diagram
11. Dependency Graph
12. Deployment Sequence Diagram
13. Runtime Startup Diagram
14. Risk Assessment Matrix

Important:

- Use actual repository evidence.
- Cite exact file paths.
- Mark unknowns explicitly.
- Do not make assumptions.
- Generate detailed diagrams suitable for Principal Engineer onboarding.
- Make diagrams detailed enough that a new engineer can understand the entire platform without additional documentation.
