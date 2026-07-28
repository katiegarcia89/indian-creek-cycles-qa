# Test Plan

## Project

Indian Creek Cycles - Manual QA Testing

## Objective

Verify the quality and functionality of the Indian Creek Cycles web application through structured manual testing. This project includes identifying and documenting defects, prioritizing issues based on impact, and performing regression testing to verify fixes where applicable.

## Scope

This project includes testing of both public-facing and administrative functionality, including:

### Public Website
- Homepage
- Navigation
- Bicycle listings
- Bicycle details
- Reservation workflow
- Authentication
- Responsive design
- Accessibility
- Error handling

### Administrative Features
- Admin dashboard
- Bike management
- Reservation management
- Accessories
- Reviews
- Role-based permissions
- Form validation

## Testing Approach

Testing consisted of:

- Manual functional testing
- Exploratory testing
- Regression testing after fixes

## Test Coverage Rationale

The test cases were selected to verify the application's highest-priority functionality while demonstrating a variety of manual QA testing techniques.

The test suite includes:

- **Smoke Testing** (TC-001 – TC-003) – Verified the homepage loads successfully and navigation links function correctly.
- **Functional Testing** (TC-004 – TC-007, TC-019) – Validated bicycle listings, bicycle details, reservation creation, and user authentication.
- **Negative Testing** (TC-006, TC-008 – TC-012, TC-016, TC-019) – Tested required field validation, invalid dates, invalid email addresses, duplicate reservations, duplicate submissions, invalid URLs, and invalid login credentials.
- **Responsive Testing** (TC-013) – Verified the website remained usable on a mobile-sized screen.
- **Accessibility Testing** (TC-014 – TC-015) – Evaluated browser zoom behavior and keyboard navigation to identify accessibility issues.
- **Visual Testing** (TC-017) – Confirmed images displayed correctly throughout the website.
- **Regression Testing** (TC-018) – Verified refreshing the confirmation page did not create duplicate reservations.

This combination of test cases was designed to cover critical user workflows, input validation, usability, accessibility, and error handling while demonstrating structured manual testing practices.

## Test Environment

### Operating Systems
- macOS
- Windows 11

### Browsers
- Google Chrome
- Safari

### Devices
- Lenovo ThinkPad
- Apple iPhone

### Test Environments
- Local development environment
- Production website (for comparison when appropriate)

## Deliverables

- [Test Plan](../test-plan/Test_Plan.md)
- [Manual Test Cases](../test-cases/Manual_Test_Cases.xlsx)
- [Bug Reports](../bug-reports/)
- [Exploratory Testing Report](../exploratory-testing/Exploratory_Testing_Report.md)
- [Regression Testing Report](../regression-testing/Regression_Test_Report.md)
- [Test Evidence](../evidence/)

## Success Criteria

The project is considered successful when:

- Critical user workflows have been tested.
- Defects have been documented with sufficient evidence.
- Verified fixes have been regression tested, when applicable.
- Test results are traceable through test cases, bug reports, and supporting evidence.