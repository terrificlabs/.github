# Contributing

## Git workflow

Never work directly on the `main` branch.

### 1. Create a branch from `main`

Before starting any work, create a new branch from an up-to-date `main`.

Allowed branch names are:

- `feature/*`
  - Used for new software features and generic enhancements.
  - Example: `feature/ddt-generation`

- `fix/*`
  - Used for bug fixes, issues, and any kind of software problem.
  - Example: `fix/user-login`

- `chore/*`
  - Used for maintenance and generic technical work that does not fall into the previous categories.
  - Example: `chore/remove-unused-code`

- `docs/*`
  - Used exclusively for documentation changes.
  - Example: `docs/update-infrastructure-bootstrap`

### 2. Open a Pull Request

Once the work on the branch is complete, open a Pull Request targeting `main`.

Use the organization Pull Request template and request a review from the other project owner.

### 3. Merge

A Pull Request can be merged into `main` only after:

- it has been reviewed and approved by the other project owner;
- all required CI checks pass, once CI is available.

Use **Squash and merge**.

After the merge, the source branch is automatically deleted.
