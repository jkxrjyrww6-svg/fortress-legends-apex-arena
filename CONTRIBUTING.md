# Contributing to Fortress Legends Apex Arena

Thank you for considering contributing to the Fortress Legends Apex Arena project! We appreciate your help and collaboration. Please follow the guidelines below to ensure a smooth contribution process.

## Getting Started
1. **Fork the repository**  
   Navigate to the top-right corner of this repository and click the "Fork" button to create your copy of the project.

2. **Clone your forked repository**  
   Run the following command in your terminal:
   ```sh
   git clone https://github.com/your-username/fortress-legends-apex-arena.git
   ```

3. **Add the original repository as a remote**  
   This will keep your fork up to date:
   ```sh
   git remote add upstream https://github.com/jkxrjyrww6-svg/fortress-legends-apex-arena.git
   ```

## Creating Feature Branches
- Always create a new branch for your features or bugfixes from the main branch.
- Name your branch descriptively, such as `feature/your-feature-name` or `bugfix/your-bugfix-name`.  
  ```sh
  git checkout -b feature/your-feature-name
  ```

## Commit Messages
- Write informative commit messages that describe the change you made. Use the following format:  
  `type(scope): subject`  
  Examples:  
  - `feat: add new feature`  
  - `fix(auth): resolve login issue`

## Pull Request Process
1. Ensure your branch is up to date with the main branch:
   ```sh
   git checkout main
   git pull upstream main
   git checkout your-feature-branch
   git rebase main
   ```
2. Once your feature or fix is complete, push your changes:
   ```sh
   git push origin your-feature-branch
   ```
3. Go to the original repository and click on "Pull Requests". Click on "New Pull Request" and select your branch.

4. Fill out the form, providing clear details about your changes, and submit the pull request.

## Code Style Guidelines
- Follow the established coding standards for this project.
- Use consistent indentation (two spaces for JavaScript files).
- Include comments in your code where necessary to clarify complex logic.

## Issue Reporting Template
When reporting an issue, please use the following template:
```
**Title:**

**Description:**

**Steps to Reproduce:**
1. 
2. 
3. 

**Expected Result:**

**Actual Result:**

**Environment:**
- OS:
- Browser (if applicable):
``` 

Thank you for contributing! We look forward to your pull requests!