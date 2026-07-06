# IAM Access Review Mini Project

## Overview

This project demonstrates a basic Identity and Access Management access review.

The goal is to identify stale accounts, excessive access, privileged access concerns, and least privilege improvement opportunities.

---

## Skills Demonstrated

- Identity and Access Management review process
- Least privilege analysis
- Stale account identification
- User and group review
- Privileged access review
- Evidence logging
- Risk-based findings
- Access review reporting

---

## Access Review Scope

| Area | Review Objective |
|---|---|
| Users | Confirm active, disabled, and stale accounts |
| Groups | Review group purpose and membership |
| Privileged Roles | Check elevated access |
| Licences | Identify possible licence waste |
| Access Findings | Record risks and recommendations |

---

## Review Method

```mermaid
flowchart LR
A[Collect user and group data] --> B[Review access]
B --> C[Identify stale or excessive access]
C --> D[Record findings]
D --> E[Recommend remediation]
E --> F[Produce access review report]
