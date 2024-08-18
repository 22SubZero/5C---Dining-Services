# Contributing to Dining Services App

We appreciate your interest in contributing to the Dining Services App! To ensure a smooth and efficient contribution process, please follow these guidelines:

## How to Contribute

1. **Fork the Repository**
   - Click the "Fork" button on the top right of the repository page to create a personal copy of the project.

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/DarkAzureII/5C---dining-services.git
   cd 5C---dining-services

## Branching Strategy

### Main Branches

- **`main`**: This branch contains the stable, production-ready code. All new features and fixes are merged into this branch after thorough testing.
- **`develop`**: This branch serves as the integration branch for features. All new features and bug fixes are merged into `develop` before being merged into `main`.

### Feature Branches

- **Naming Convention**: `feature/description`
  - Example: `feature/real-time-menu-update`
- **Purpose**: Used for developing new features.
- **Branching Off**: Create feature branches from `develop`.
- **Merging**: Once a feature is complete and tested, merge it into `develop` using a pull request (PR).

### Bugfix Branches

- **Naming Convention**: `bugfix/description`
  - Example: `bugfix/fix-menu-display-issue`
- **Purpose**: Used for fixing bugs in the application.
- **Branching Off**: Create bugfix branches from `develop`.
- **Merging**: Once a bug fix is complete and tested, merge it into `develop` using a pull request (PR).

### Hotfix Branches

- **Naming Convention**: `hotfix/description`
  - Example: `hotfix/urgent-issue-fix`
- **Purpose**: Used for critical fixes that need to be applied directly to `main`.
- **Branching Off**: Create hotfix branches from `main`.
- **Merging**: Once the hotfix is complete and tested, merge it into both `main` and `develop` using a pull request (PR).

## Commit Messages

- **Format**: 

- **TYPE**: Can be one of `feat` (feature), `fix` (bug fix), `docs` (documentation), `style` (formatting), `refactor` (code changes), `test` (adding tests), `chore` (maintenance).

- **Example**:
  ```
  feat: add real-time menu updates

  Added a feature to update the menu in real-time using WebSockets.
  ```

## Pull Requests (PRs)

- **Description**: Provide a clear description of the changes, why they are needed, and any other relevant information.
- **Review**: PRs should be reviewed by at least one other team member before merging.
- **Approval**: Obtain approval from reviewers before merging into `develop` or `main`