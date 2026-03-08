# Project Description
This project demonstrates basic QA testing of [Truffle Security](https://github.com/trufflesecurity), a cybersecurity tool used to detect exposed secrets such as API keys, tokens, and credentials in source code and git history.
The repository includes simple test scenarios designed to verify that the tool correctly detects hardcoded secrets, avoids false positives, and can be used in a system that performs regular security scans across multiple repositories.

# Files
This repository contains controlled test files with intentionally hardcoded example secrets (AWS keys, API tokens, high-entropy strings) used to validate TruffleHog secret detection functionality. No real credentials are included.
