# Github-Actions-InfoSec-Templates

## Workflows

This repository contains GitHub Actions workflow templates for enhancing the security of your codebase by scanning for secrets and vulnerabilities using popular tools in the field of information security.

### 1. Scan Secrets using Gitleaks

Gitleaks is a tool that scans Git repositories for sensitive information like API keys, credentials, and other secrets. This workflow uses Gitleaks to perform a secrets scan on your repository.

### 2. Scan Secrets using Trufflehog

Trufflehog is another tool for scanning Git repositories for secrets and high entropy strings. This workflow uses Trufflehog to perform a secrets scan on your repository.

### 3. Snyk Workflow for Python using Snyk

Snyk is a vulnerability management tool that helps identify and fix vulnerabilities in your code and dependencies. This workflow is specifically designed for Python projects and uses Snyk to scan for vulnerabilities.

## Running the Workflows

These workflows are configured to run manually using `[workflow_dispatch]`. This means that you can trigger them manually when needed, rather than them running automatically on specific events like pushes to the `main` branch.


**Modifying Trigger Conditions:**

If you wish to change when these workflows run automatically (e.g., on pushes to specific branches), you can modify the triggering conditions in the workflow files according to your requirements.
