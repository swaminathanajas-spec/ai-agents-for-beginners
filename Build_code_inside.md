Act as a Principal Engineer and DevOps onboarding analyst.

I have two 123 repositories opened in this VS Code workspace. I need to build and run them inside the abc network. Study both repositories deeply and create a complete technical onboarding/build document.

Analyze and collect the following details:

1. Repository purpose
- What each repo does
- Main business capability
- Relationship between the two repos
- Which repo is UI, API, worker, service, shared library, infrastructure, etc.

2. Technology stack
- Programming languages
- Frontend framework
- Backend framework
- Background service framework
- Database technology
- Messaging/queue technology
- Cloud/AWS services
- Docker/Kubernetes/ECS usage
- Build tools and package managers

3. Local build/run process
For each repo, identify:
- Prerequisites
- Required SDK/runtime versions
- Required tools
- Required environment variables
- Required config files
- Package install command
- Build command
- Test command
- Run/start command
- Debugging steps in VS Code
- Ports used
- Startup entry point

4. Dependency details
Identify:
- Internal project/module dependencies
- External libraries/packages
- Package files used, such as package.json, requirements.txt, pyproject.toml, csproj, pom.xml, build.gradle, Gemfile, Dockerfile
- Version constraints
- Deprecated or risky dependencies
- Any private package feeds or registries

5. Configuration and secrets
Find:
- .env files
- appsettings files
- config YAML/JSON
- AWS config
- Secrets Manager / Parameter Store references
- Local development configuration
- Environment-specific configuration for dev/qa/stage/prod
- Any placeholder values I need to request from the team

6. Build and CI/CD process
Search for:
- GitHub Actions
- Jenkinsfile
- TeamCity
- Docker build scripts
- Makefile
- shell scripts
- Terraform/CloudFormation/CDK
- Helm charts
- deployment YAML files

Explain:
- How code is built
- How tests are executed
- How artifacts are generated
- How Docker images are created
- Where images/packages are published
- How deployment is triggered
- Approval gates
- Rollback approach
- Promotion between environments

7. Runtime architecture
Explain:
- What starts first
- Runtime components
- UI-to-API flow
- API-to-database flow
- Background job flow
- Queue/event flow
- File/S3 flow
- External system integrations
- Authentication/authorization flow

8. AWS and infrastructure
Identify AWS services used:
- EC2, ECS, EKS, Lambda
- S3, CloudFront, Route53
- ALB/NLB/API Gateway
- RDS/Aurora/DynamoDB
- SQS/SNS/EventBridge
- IAM
- Secrets Manager/Parameter Store
- CloudWatch
- ECR

For each AWS service, explain:
- Where it is referenced
- Why it is used
- Which repo/module depends on it
- Required permissions
- Environment differences

9. Testing and validation
Identify:
- Unit tests
- Integration tests
- UI tests
- Mock/stub services
- Test data
- How to validate local build success
- How to validate service health
- Health check endpoints

10. abc network readiness
Identify what I need to confirm for building inside abc network:
- Private registry access
- GitHub access
- Package feed access
- Docker registry access
- AWS access
- Proxy settings
- Certificate requirements
- VPN/network dependency
- Firewall/allowlist needs
- Secrets/config values needed

Output format:

A. Executive summary  
B. Repo-by-repo build guide  
C. Dependency inventory table  
D. Runtime architecture explanation  
E. CI/CD flow  
F. AWS/infrastructure map  
G. Local setup checklist  
H. abc network dependency checklist  
I. Open questions to ask 123/abc team  
J. Mermaid architecture diagram  
K. Confidence level with file references

Important instructions:
- Do not guess.
- Always mention exact files where evidence is found.
- If something is unknown, mark it as UNKNOWN and list what file/person/team needs confirmation.
- Prefer actual commands from repository files over assumptions.
- Include both high-level summary and detailed technical steps.
