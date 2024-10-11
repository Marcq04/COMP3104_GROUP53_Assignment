# COMP3104_Group53_Assignment

## Group Members
- **Leader:** Marcus Quitiquit  (https://github.com/Marcq04) (101448926)
- **Member 2:** [Kadir Cinar](https://github.com/KadirCinar9) (101469903)

## Project Description
This repository contains the group assignment for COMP3104 DevOps course, which covers collaborative Git workflows, CI/CD integration using GitHub Actions, and branching strategies.

## Setup Instructions
1. **Clone the repository**:
    ```bash
    git clone https://github.com/group-leader-username/COMP3104_Group53_Assignment.git
    ```
2. **Switch to your branch**:
    ```bash
    git checkout STUDENTID-Name
    ```
3. **Install dependencies (if any)**:
    ```bash
    npm install
    ```
4. **Run the project (if applicable)**:
    ```bash
    npm start
    ```

## CI/CD Pipeline
The project uses **GitHub Actions** for continuous integration. The workflow is located in the `.github/workflows/ci.yml` file and automatically runs the tests on each push to ensure build success and test coverage.

## Branching Strategy
Each group member has their own branch named in the format `STUDENTID-Name` (e.g., `101469903-Kadir`). All feature branches are merged into the main branch through Pull Requests (PRs), ensuring proper review and collaboration.