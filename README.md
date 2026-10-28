# Trello SaaS — Manual QA Testing

## Project Overview

This project demonstrates a structured manual QA testing approach for a Trello-like SaaS application. It focuses on validating core user workflows, functional behavior, and role-based access control (RBAC) through detailed test planning, test case design, and defect reporting.

The project showcases practical QA skills in analyzing application behavior, identifying potential issues, validating user permissions, and documenting defects with clear reproduction steps and supporting evidence.

## Objectives

- Validate core application workflows and business rules.
- Verify authentication and role-based access control.
- Test board and task management functionality.
- Identify functional defects, edge cases, and usability issues.
- Design positive, negative, and boundary test scenarios.
- Document reproducible defects with expected and actual results.
- Provide clear test execution results and quality insights.

## Scope of Testing

### Authentication and RBAC
- Login validation and error handling.
- Role-specific access for Admin, Member, and Observer.
- Verification of restricted actions and permissions.
- Session behavior, where supported.

### Board Management
- Board creation, editing, and deletion.
- Board member management and role assignments.
- Validation of permission restrictions.

### Task Management
- Task creation and editing.
- Task assignment and status transitions.
- Labels, due dates, and comments, where supported.
- Validation of unauthorized task modifications.

### Additional Testing
- Negative and boundary scenarios.
- Form validation and error messages.
- Exploratory testing of relevant workflows.
- Regression testing of previously verified functionality.

## Testing Deliverables

| Deliverable | Description |
|---|---|
| Test Plan | Testing objectives, scope, approach, risks, and exit criteria |
| Test Cases | Detailed steps, preconditions, test data, and expected results |
| Bug Reports | Reproduction steps, expected vs. actual results, severity, priority, and supporting evidence |

## Test Design Approach

Test scenarios are designed to cover:

- **Positive testing:** Verify valid workflows and expected behavior.
- **Negative testing:** Validate invalid inputs and unauthorized actions.
- **RBAC testing:** Verify permissions for each supported user role.
- **Boundary testing:** Check relevant limits and edge cases.
- **Exploratory testing:** Investigate unexpected behavior beyond predefined scenarios.
- **Regression testing:** Revalidate functionality after fixes or changes.

## Defect Reporting

Each bug report is structured to help developers reproduce and investigate issues efficiently.

Defect documentation includes:

- Bug ID and title
- Affected module
- Preconditions and environment
- Steps to reproduce
- Expected result
- Actual result
- Severity and priority
- Screenshots or supporting evidence
- Defect status

## Repository Structure

```text
Trello-SaaS-Manual-Testing/
├── README.md
├── Test-Plan/
│   └── Manual-Test-Plan.md
├── Test-Cases/
│   ├── Authentication-RBAC-Test-Cases.md
│   ├── Board-Management-Test-Cases.md
│   └── Task-Management-Test-Cases.md
├── Bug-Reports/
│   └──
