Act as a Principal Engineer, Platform Architect, DevOps Engineer, and Migration Analyst.

Context:

I have two source code repositories from 123 that need to be onboarded onto the ABC platform.

Both repositories are opened in my VS Code workspace.

I have access to:
- Source code
- Local coding agent
- Repository search tools
- Documentation search skills
- Internal platform documentation if available

My objective is to understand the applications completely and create a plan to successfully build, run, support, and onboard them into the ABC platform.

Important:
- Do not make assumptions.
- Always cite evidence using file paths, scripts, configuration files, or documentation references.
- If information cannot be found, mark it as UNKNOWN and identify what needs confirmation.

====================================================
PHASE 1 – APPLICATION DISCOVERY
====================================================

Analyze both repositories and determine:

1. Business purpose
2. Relationship between repositories
3. Major application components
4. UI applications
5. APIs/services
6. Background workers
7. Shared libraries
8. Runtime architecture
9. Startup sequence
10. Data flow between components

Provide:
- High-level summary
- Component inventory
- Runtime flow diagram

====================================================
PHASE 2 – TECHNOLOGY STACK INVENTORY
====================================================

Identify all technologies used:

- Languages
- Frameworks
- Databases
- Messaging systems
- Search engines
- Cloud services
- Containers
- Infrastructure as code
- CI/CD tooling
- Security tooling
- Monitoring tooling

Output:

Technology | Version | Evidence | Purpose

====================================================
PHASE 3 – BUILD READINESS ANALYSIS
====================================================

Determine:

- Required runtimes
- SDKs
- Toolchains
- Build tools
- Package managers
- Environment variables
- Configuration files
- Certificates
- Local services
- Secrets dependencies

For each repository provide:

Prerequisites
Build commands
Run commands
Test commands
Debug commands

====================================================
PHASE 4 – DEPENDENCY INVENTORY
====================================================

Inspect:

- package.json
- package-lock.json
- yarn.lock
- requirements.txt
- pyproject.toml
- Pipfile
- *.csproj
- *.sln
- pom.xml
- build.gradle
- Gemfile
- Dockerfile
- docker-compose
- Helm
- Terraform
- CloudFormation
- CDK
- Shell scripts

Generate:

Dependency | Version | File | Purpose | Risk | Action

====================================================
PHASE 5 – CI/CD ANALYSIS
====================================================

Identify:

- Build pipeline
- Test pipeline
- Packaging
- Artifact creation
- Container build
- Deployment process
- Promotion process
- Rollback process
- Security scanning
- Approval gates

Explain:

Current process
Target ABC process
Gap analysis

====================================================
PHASE 6 – PLATFORM COMPATIBILITY
====================================================

Search available documentation and identify ABC platform requirements.

Determine:

- Approved runtime versions
- Approved package registries
- Approved container platform
- Approved artifact repositories
- Network restrictions
- Certificate requirements
- Security controls
- Deployment standards
- SDLC standards

Compare repository requirements against platform standards.

Output:

Requirement | Repository State | Platform State | Gap | Action

====================================================
PHASE 7 – INFRASTRUCTURE & INTEGRATIONS
====================================================

Identify:

- Databases
- Queues
- APIs
- Storage
- Authentication providers
- Authorization providers
- Webhooks
- External systems
- Internal systems

Generate:

Component | Dependency | Protocol | Config Source | Environment | Risk

====================================================
PHASE 8 – CONTAINERIZATION
====================================================

Analyze:

- Dockerfiles
- Compose files
- Container startup
- Image creation
- Base images
- Ports
- Environment variables
- Registry assumptions
- Kubernetes references
- Helm references

Determine changes needed for ABC compatibility.

====================================================
PHASE 9 – SECURITY REVIEW
====================================================

Identify:

- Hardcoded secrets
- Deprecated libraries
- Unsupported runtimes
- Vulnerable packages
- External endpoints
- Missing controls
- Sensitive logging
- Compliance concerns

Classify:

Blocker
High
Medium
Low

====================================================
PHASE 10 – REMEDIATION PLAN
====================================================

Create:

Issue
Evidence
Impact
Root Cause
Recommended Fix
Priority
Complexity
Owner

====================================================
DELIVERABLES
====================================================

Produce:

1. Executive Summary
2. Repository Overview
3. Build Guide
4. Runtime Architecture
5. Dependency Inventory
6. Infrastructure Map
7. CI/CD Analysis
8. Platform Compatibility Report
9. Security Findings
10. Remediation Roadmap
11. Open Questions
12. Mermaid Architecture Diagram
13. Day-1 Setup Plan
14. Week-1 Execution Plan
15. Week-2 Migration Plan

Goal:
Successfully build, run, support, and onboard both 123 repositories into the ABC platform with minimal risk and complete understanding of dependencies and architecture.
