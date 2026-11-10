# SauceDemo – E-commerce Website QA Testing

## Project Overview

This project demonstrates a practical manual Software Quality Assurance (QA) testing process using the SauceDemo e-commerce web application.

The project focuses on testing important e-commerce functionalities, designing test cases, executing tests, recording actual results, identifying potential defects and preparing test documentation.

**Application Under Test:** https://www.saucedemo.com/

## Project Objectives

- Understand the application's functional requirements.
- Design and document manual test cases.
- Execute test cases using appropriate test data.
- Verify actual results against expected results.
- Identify and document potential software defects.
- Prepare professional QA testing documentation.
- Build practical experience in manual software testing.

## Testing Scope

| Module | Testing Activities |
|---|---|
| Login | Valid login, invalid credentials, empty fields and locked-out user |
| Product Listing | Product names, descriptions, prices, images and buttons |
| Product Sorting | Alphabetical and price-based sorting |
| Product Navigation | Product details and page navigation |
| Shopping Cart | Adding and removing products |

## Tools and Technologies

- **Application:** SauceDemo
- **Test Management:** Google Sheets / Microsoft Excel
- **Documentation:** Google Docs
- **Defect Reporting:** Excel / Google Sheets
- **Version Control:** GitHub
- **Testing Approach:** Manual Testing

## Project Structure

```text
SauceDemo-Ecommerce-Testing/
│
├── 01_Requirement_Analysis/
│
├── 02_Test_Plan/
│
├── 03_Test_Cases/
│
├── 04_Test_Execution/
│
├── 05_Bug_Reports/
│
├── 06_Test_Summary/
│
├── 07_Screenshots/
│
├── 08_Automation/
│
└── README.md
```

## Test Case Coverage

A total of 28 test cases have been prepared across five functional areas.

| Module | Test Cases |
|---|---:|
| Login | 10 |
| Product Visibility and Information | 6 |
| Product Sorting | 5 |
| Product Navigation | 4 |
| Add to Cart | 3 |
| **Total** | **28** |

## Test Execution

Test execution results are recorded in the test case management spreadsheet.

Each test case includes:

- Test Case ID
- Test Scenario
- Preconditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Execution Status
- Priority

Execution statuses include Pass, Fail, Retest and Not Run.

## Defect Reporting

Potential issues identified during testing are documented with their related test case IDs.

Defect reports include:

- Bug ID
- Bug Title
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Status
- Screenshot Evidence

Potential defects are subject to retesting and verification before being treated as confirmed defects.

## Current Project Status

- [x] Requirement analysis prepared
- [x] Test plan prepared
- [x] Test cases designed
- [x] Initial test execution recorded
- [x] Draft defect reports prepared
- [ ] Final defect verification
- [ ] Final test summary
- [ ] Playwright automation

## Future Improvements

- Learn and implement defect tracking using Jira.
- Develop automated test scripts using Playwright.
- Expand test coverage.
- Improve test reporting and documentation.

## Conclusion

This project provides practical experience in manual software testing and demonstrates the QA process from requirement analysis and test case preparation to test execution and defect reporting.

It is an ongoing learning portfolio project, and its documentation will be updated as further testing activities are completed.
