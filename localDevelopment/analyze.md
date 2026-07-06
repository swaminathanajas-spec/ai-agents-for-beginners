I am part of **ABC** and working on onboarding/building an acquired **XYZ** source code repository inside the **ABC** engineering environment.

## Goal

Analyze the current XYZ project and create a practical build and adoption plan for the ABC engineering environment, considering that some base images, third-party libraries, runtime versions, package registries, build tools, deployment dependencies, or infrastructure components may not exist or may require governance approval within ABC.

## Available Tools

Use all available MCPs and internal search capabilities whenever additional information is required.

* GitHub MCP

  * Inspect repositories
  * Analyze GitHub Actions workflows
  * Read repository settings
  * Review dependency files
  * Inspect pull requests
  * Review package metadata

* Sourcegraph MCP

  * Search the entire codebase
  * Identify dependency usage
  * Trace imports
  * Locate Dockerfiles
  * Analyze build scripts
  * Discover environment variables
  * Identify runtime requirements

* Atlassian MCP

  * Search Confluence documentation
  * Search Jira tickets
  * Find engineering standards
  * Locate approved technology stacks
  * Identify SDLC requirements
  * Search security and governance documentation

* Internal Search

  * Search approved base images
  * Search approved package repositories
  * Search approved runtime versions
  * Search existing implementation examples
  * Search CI/CD standards
  * Search container standards
  * Search internal deployment documentation

Always prefer gathering evidence before making assumptions.

---

## Task 1 – Identify the Technology Stack

Identify and document:

* Programming languages
* Frameworks
* Runtime versions
* Package managers
* Build tools
* Base container images
* Databases
* Cache technologies
* Message queues
* External services
* Authentication providers
* Test frameworks
* Deployment model
* Infrastructure dependencies

---

## Task 2 – Discover the Build Process

Locate every build entry point including:

* README
* package.json
* pyproject.toml
* requirements.txt
* poetry.lock
* Pipfile
* pom.xml
* build.gradle
* gradle.properties
* go.mod
* Dockerfile
* docker-compose
* Makefile
* shell scripts
* CI/CD workflow files
* deployment scripts

Determine:

* Complete build sequence
* Required environment variables
* Required secrets
* Required infrastructure
* Required external services

---

## Task 3 – Dependency Assessment

For every dependency, determine:

* Name
* Version
* Purpose
* Usage location
* Runtime dependency
* Build dependency
* License
* Repository source

Compare against ABC engineering standards.

Determine whether each dependency is:

* Approved
* Available
* Not available
* Unknown

If unavailable, identify:

* Internal equivalent
* Approved replacement
* Required governance approval
* Migration effort
* Associated risk

---

## Task 4 – Build a Gap Matrix

Generate a table with:

* Dependency
* Current Version
* Purpose
* Source Location
* Availability in ABC
* Recommended Alternative
* Migration Effort
* Risk
* Required Action
* Suggested Owner
* Supporting Evidence

---

## Task 5 – Missing Component Strategy

Whenever something is unavailable, determine the best approach:

* Replace with approved alternative
* Upgrade
* Downgrade
* Mirror into internal package repository
* Request governance approval
* Refactor application
* Replace container base image
* Replace build tooling
* Replace deployment tooling

Avoid unnecessary refactoring.

---

## Task 6 – Migration Roadmap

Produce an implementation roadmap.

Phase 1
Discovery

Phase 2
Dependency Inventory

Phase 3
Environment Mapping

Phase 4
Gap Analysis

Phase 5
Dependency Remediation

Phase 6
Build Validation

Phase 7
CI/CD Integration

Phase 8
Security Review

Phase 9
Deployment Readiness

Phase 10
Documentation

---

## Task 7 – Build Guide

Produce ABC-compatible documentation including:

Prerequisites

Required Software

Required Runtime Versions

Required Environment Variables

Required Internal Registries

Build Commands

Test Commands

Container Build Commands

Deployment Steps

Known Issues

Pending Governance Approvals

Troubleshooting Guide

---

## Task 8 – Work Item Generation

Generate implementation work items for every remediation task.

Include:

* Title
* Description
* Acceptance Criteria
* Dependencies
* Priority
* Suggested Owner
* Estimated Complexity

---

## Task 9 – Evidence-Based Analysis

Never make assumptions.

Every recommendation must include supporting evidence from one or more of:

* Source code
* GitHub repository
* Sourcegraph search
* Confluence
* Jira
* Internal search
* CI/CD configuration

If evidence cannot be found, explicitly mark the item as **Unknown**.

---

## Deliverables

Produce the following deliverables:

1. Executive Summary

2. Technology Stack Assessment

3. Build Architecture

4. Dependency Inventory

5. Dependency Gap Matrix

6. Missing Component Analysis

7. Migration Strategy

8. Build Adoption Plan

9. CI/CD Recommendation

10. Security and Governance Action List

11. Risk Assessment

12. Implementation Roadmap

13. Work Item Backlog

14. Open Questions

Focus on producing an actionable, production-ready migration strategy while minimizing implementation risk and aligning with existing ABC engineering standards.
