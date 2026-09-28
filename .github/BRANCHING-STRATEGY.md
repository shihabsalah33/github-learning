# Branching Strategy

## Strategy

The team follows **GitHub Flow**.

## Rules

1. `main` is the stable branch.
2. Developers do not work directly on `main`.
3. Each unit of work has its own branch.
4. The developer who owns the task creates the branch.
5. Branch names follow these conventions:

   * `feature/...` — new functionality
   * `fix/...` — bug fixes
   * `refactor/...` — code restructuring without changing behavior
6. Changes are committed to the feature branch.
7. The feature branch is pushed to GitHub.
8. A Pull Request is created to merge the branch into `main`.
9. Code Review is required before merging.
10. After the required approvals and checks pass, the Pull Request can be merged.
11. The feature branch is deleted after merging.
