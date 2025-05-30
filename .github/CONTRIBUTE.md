# Contribution Guidelines
Welcome, and thank you for your interest in contributing to this project! Please follow the guidelines below for bug reports, feature suggestions, documentation improvements, and more.

# Branching Strategy

- `main` branch: The stable production-ready branch.
- `dev` branch: The active development integration branch. All feature or bugfix branches should be created from `dev` and merged back into `dev`.
- Use the following branch naming conventions:
  - Feature: `feat/featureName`</br>
    If you want to implement a new feature, create a `feat` branch.
  - Bugfix: `fix/bugDescription`</br>
    If you want to fix a bug, create a `fix` branch.
  - Sandbox: `sandbox/commitId-userName`</br>
    If you want to test a new feature or do a proof of concept, create a `sandbox` branch.

# Pull Request Workflow
1. Create your working branch from `dev`.
1. Commit your changes with meaningful messages.
1. Open a pull request targeting `dev`, not `main`.
1. Respond to any feedback during the review.
1. Maintainers will merge `dev` into `main` as needed.
