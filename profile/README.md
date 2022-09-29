# TKhom3 Repositories

## Setup new repo

### Branch Protections

- Require status checks to pass before merging
  - Require branches to be up to date before merging
  - Status checks that are required
    - scan-with-trivy
    - check-for-label
    - cloudformation-linter (if CFT)
- Allow force pushes
