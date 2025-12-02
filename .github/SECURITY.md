# Security Policy for ContentFetch-AI-Content-Downloader-MCP-Server

## Our Commitment

The project maintainers take the security of `ContentFetch-AI-Content-Downloader-MCP-Server` seriously. We are committed to a secure development lifecycle and to rapidly addressing vulnerabilities when they are discovered. The integrity and safety of our users and their data are our highest priorities.

## Supported Versions

Only the latest version of the software is actively supported with security patches. We encourage all users to stay updated to ensure they are running the most secure and stable release.

| Version | Supported          |
| ------- | ------------------ |
| `1.x.x`   | :white_check_mark: |
| `< 1.0`   | :x:                |

## Reporting a Vulnerability

We appreciate responsible disclosure from the security community. If you discover a security vulnerability, please report it to us privately to protect the project and its users.

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please use the **private vulnerability reporting feature** provided by GitHub.

[**Report a Vulnerability Here**](https://github.com/chirag127/ContentFetch-AI-Content-Downloader-MCP-Server/security/advisories/new)

### What to Include

To help us address the issue quickly, please provide a detailed report including:

- A clear description of the vulnerability and its potential impact.
- Step-by-step instructions to reproduce the issue.
- Proof-of-concept (PoC) code, screenshots, or videos.
- Any potential mitigations you have identified.

### Our Process

1.  **Acknowledgment:** We will acknowledge receipt of your report within 48 hours.
2.  **Triage & Investigation:** We will investigate the report to confirm the vulnerability and determine its severity.
3.  **Communication:** We will provide an update on our progress within 7 business days.
4.  **Resolution:** We will work to develop and release a patch as quickly as possible, coordinated with you.
5.  **Disclosure:** Once the vulnerability is patched, we will issue a security advisory and credit you for your discovery, unless you prefer to remain anonymous.

## Security Best Practices

We adhere to the following security practices to maintain the integrity of our codebase:

- **Dependency Scanning:** We use GitHub's Dependabot to automatically scan our dependencies for known vulnerabilities and create pull requests to update them.
- **Static Code Analysis:** We employ GitHub CodeQL for Static Analysis Security Testing (SAST) to identify potential vulnerabilities in our code during the development process.
- **Principle of Least Privilege:** The application is designed to run with the minimum necessary permissions.
- **Secure Defaults:** We strive to provide secure default configurations out of the box.
