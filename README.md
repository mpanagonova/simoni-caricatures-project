# Simoni Caricatures Website – Manual QA Testing Project

## Project Overview
This project represents a **manual QA testing process** conducted on a real public website:
https://www.simonicaricatures.bg/

The goal of the project is to demonstrate:
- Structured test planning
- Test case design and execution
- Identification of potential issues
- Understanding of real user scenarios

---

## Test Coverage
A **mind map** was created to outline the main testing areas, including:
- Navigation and UI
- Forms (Contact & Order)
- Gallery functionality
- Responsiveness
- Accessibility
- Performance

See: `simoni-caricatures-mind-map.png`

---

## Test Cases
A set of **20 manual test cases** was designed based on the identified scenarios.

They include:
- Positive and negative scenarios
- Form validation
- UI behavior
- Functional flows

See: `simoni-caricatures-test-cases.md`

---

## Bug Reports
During the testing process, several issues and improvement areas were identified and documented.

The reported issues include:
- Functional issues (e.g. form validation)
- UI inconsistencies (e.g. image alignment)
- Usability gaps (e.g. missing filtering, limited user control)

All bug reports are documented with:
- Steps to reproduce
- Expected and actual results
- Severity and priority assessment

See: `simoni-caricatures-bug-reports.md`

---

## Test Summary Report

A Test Summary Report was created to present the overall testing results and key findings.

It includes:
- Test execution statistics (passed, failed, not executed)
- Summary of identified defects
- Observations and conclusions
- Risks and limitations of the testing process

See: `simoni-caricatures-test-summary-report.md`

---

## Testing Approach

The following testing techniques were applied:
- Functional testing
- Exploratory testing
- Boundary Value Analysis (basic)
- Negative testing

---

## Test Environment
- Browsers: Chrome, Safari
- Devices tested:
  - Desktop
  - Mobile (responsive view)

---
## Jira Test Management

The testing process was also managed using **Jira**, following a simplified Agile workflow.

The project structure in Jira includes:
- **Epics** representing major testing areas (e.g. Core Functionality, Gallery, Contact Form, Order Form)
- **Stories** representing individual test scenarios derived from the test cases
- **Bugs** representing identified defects during test execution

This approach demonstrates:
- Test planning and organization using Epics
- Traceability between test scenarios and defects
- Real-world defect tracking process
- Understanding of Agile QA workflows

All test scenarios and bugs were linked to their respective Epics to simulate a structured QA process in a real project environment.

See related screenshots:
- `jira-epics-overview.png`
- `jira-gallery-epic.png`
- `jira-bug-example.png`

## Notes
- This project focuses on **manual testing only**
- No access to backend or database
- Some scenarios are based on expected behavior (black-box testing)
