# PSF System Testing

Quality Assurance project for the **PSF System** — a web-based platform for tracking student probation and off-plan graduation at Burapha University.

## Overview

This repository contains all QA artifacts and automation testing scripts produced during the testing lifecycle of the PSF System, including Test Plan, Test Script, Test Cases, Integration Testing, UAT, Defect Reports, and Cypress automation scripts.

## Repository Structure

```
PSF-System-Testing/
├── Automation/        # Cypress automation test scripts
├── Test Plan.xlsx     # Full QA documentation (Test Plan, Test Script, Test Cases,
│                      # Integration Test, UAT Plan & Script, Defect Report, Summary Reports)
└── README.md
```

## Testing Scope

| Type | Details |
|---|---|
| Manual Testing | Functional testing across core modules (Login, User Management, Add/Edit/Delete User) |
| Integration Testing | Cross-browser testing on Chrome, Edge, and Firefox |
| UAT | Validated with end users across 10 functions, 296 test cases |
| Automation Testing | Cypress scripts covering core user flows |

## Testing Summary

- 818 test cases executed across 24 functions
- 44 defects reported (24 High, 17 Medium, 3 Low) in Sprint 1
- 76 integration test cases across 3 browsers (Chrome, Edge, Firefox)
- UAT: 292/296 test cases passed (98.6% pass rate)
- Full documentation: Test Plan, Test Script, Test Case Summary, Integration Test, UAT Plan & Script, Defect Report

## Tools & Technologies

- **Cypress** — End-to-end automation testing
- **Google Sheets / Excel** — Test documentation
- **GitHub** — Version control and artifact storage

## Author

**Narenthon Saetio** — QA Tester  
Burapha University, Faculty of Informatics
