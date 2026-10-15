# DevSecOps Security Lab

## Aim
To implement automated security scanning in a DevSecOps workflow using AWS CodeBuild, Semgrep, and Trivy.

## Tools and Technologies
- **AWS CodeBuild** – Automates the build and security scanning process.
- **GitHub** – Stores the project source code and build configuration.
- **Semgrep** – Detects potential security issues in source code.
- **Trivy** – Scans files and dependencies for vulnerabilities.

## Project Structure

```text
devsecops-security-lab/
├── README.md
└── buildspec.yml
```

## Workflow
1. Store the project files in GitHub.
2. Connect the repository to AWS CodeBuild.
3. Configure CodeBuild to execute the commands in `buildspec.yml`.
4. Run Semgrep to identify potential security issues.
5. Run Trivy to scan for high and critical vulnerabilities.
6. Review the build logs and resolve any detected issues.

## Expected Outcome
Automated security checks run during the build process, helping identify vulnerabilities before deployment.

## Disclaimer
This project is intended for educational purposes as part of a DevSecOps lab.
