# Indian Creek Cycles – Core Functional Test Suite

## Overview

This document provides an overview of the manual functional test suite created for the Indian Creek Cycles web application.

The complete test cases, execution results, priorities, evidence references, and related bug IDs are maintained in the Excel workbook:

➡️ **Manual_Test_Cases.xlsx**

---

# Test Environment

## Application

Indian Creek Cycles

## Website

https://www.indiancreekcycles.com

## Browsers

- Google Chrome
- Safari

## Operating Systems

- macOS
- Windows 11

## Devices

- MacBook Air
- Lenovo ThinkPad
- Apple iPhone

## Test Type

- Manual Functional Testing

---

# Test Suite Summary

| Test ID | Feature | Status |
|----------|---------|--------|
| TC-001 | Homepage loads successfully | Passed |
| TC-002 | Navigation links | Passed |
| TC-003 | Company logo navigation | Passed |
| TC-004 | Bicycle listings | Passed |
| TC-005 | Bicycle details | Passed |
| TC-006 | Required reservation fields | Passed |
| TC-007 | Reservation creation | Passed |
| TC-008 | Invalid date range | Passed |
| TC-009 | Past date validation | Passed |
| TC-010 | Prevent double booking | Passed |
| TC-011 | Email validation | Passed |
| TC-012 | Prevent duplicate submission | Passed |
| TC-013 | Responsive layout | Passed |
| TC-014 | Browser zoom accessibility | Failed |
| TC-015 | Keyboard navigation | Failed |
| TC-016 | Invalid URL (404) | Passed |
| TC-017 | Image verification | Passed |
| TC-018 | Refresh after reservation | Passed |
| TC-019 | Invalid login credentials | Passed |

---

# Test Coverage

The manual test suite includes the following testing categories:

- Smoke Testing (TC-001 – TC-003)
- Functional Testing (TC-004 – TC-007, TC-019)
- Negative Testing (TC-006, TC-008 – TC-012, TC-016, TC-019)
- Responsive Testing (TC-013)
- Accessibility Testing (TC-014 – TC-015)
- Visual Testing (TC-017)
- Regression Testing (TC-018)

---

# Known Issues

The following issues were identified during testing:

| Bug | Status |
|-----|--------|
| BUG-005 – Browser Zoom Breaks Navigation | Open |
| BUG-006 – Keyboard Navigation Requires Mouse Interaction | Open |

Additional defects identified during exploratory testing are documented in the **bug-reports** directory.

---

# Supporting Documentation

- 📄 Test Plan
- 📊 Manual Test Cases
- 🐞 Bug Reports
- 🔍 Exploratory Testing Report
- 🔄 Regression Testing Report
- 📷 Test Evidence

---

# Repository Structure

```text
test-plan/
test-cases/
bug-reports/
exploratory-testing/
regression-testing/
evidence/
README.md
```

---

# Notes

The Excel workbook serves as the source of truth for detailed test execution. This document summarizes the completed functional testing and provides a high-level overview of the project for reviewers and hiring managers.