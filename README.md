# Hello Growth CRM – Manual Testing Project

## Project Overview

Hello Growth CRM is an Android-based Customer Relationship Management (CRM) application.

This project demonstrates my practical knowledge of Manual Software Testing, including test scenario identification, test case design, test execution, defect identification, and test documentation.

= Testing Objective

The objective of this project was to verify the application's functionality, UI, navigation, input validation, session handling, network behavior, and basic device compatibility, while identifying and documenting defects.

-Application Details

Details             -     Information 
Application         -     Hello Growth CRM 
Platform            -     Android 
App Version         -     Version 1 
Android Version     -     Android 10 
Devices Tested      -     Realme 5, Redmi 8A Dual 

= Testing Scope

The following areas were covered during testing:

- Functional Testing
- UI Testing
- Negative Testing
- Input Validation
- Session Management Testing
- Navigation Testing
- Data Persistence Testing
- Installation Testing
- Compatibility Testing
- Network Testing
- Recovery Testing
- File Export Testing

= Test Coverage

A total of **33 test cases** were designed and executed across major application modules.

### Modules Covered

- Login
- Signup
- Organization Setup
- Contact & Location
- Dashboard
- Navigation Menu
- Leads
- Tasks
- Call Logs
- AI Calling Center
- Reports
- Settings
- Installation & Reinstallation
- Screen Rotation
- Network Handling
- Back Navigation

### Test Execution Summary

Metric                     Count 

Total Test Cases            33 
Defects Identified           5 
Devices Tested               2 

= Defect Summary

During test execution, **5 defects** were identified and documented.

| Bug ID        Module                  Severity            Priority 

BUG_001    Contact & Location            High                High 
BUG_002  Authentication / Session        High                High 
BUG_003  Tasks                           High                Medium
BUG_004  Settings                        Medium              Medium
BUG_005  Navigation                      Medium              Medium

### Key Defects Identified

BUG_001 – Invalid Mobile Number Accepted

The application accepted a 15-digit mobile number and allowed the onboarding flow to continue instead of rejecting the invalid input.

BUG_002 – OTP Verification Requested Again

The application requested OTP/session verification again after the user briefly moved to another application and returned.

BUG_003 – Archived Task Not Visible

An archived task was not displayed in the Archive section after being archived.

BUG_004 – Settings Close Button Issue

The Close (X) icon on the Settings page did not dismiss the page as expected.

BUG_005 – Incorrect Back Navigation

Using the Back action from a Settings sub-page redirected the user to the Dashboard instead of the previous Settings screen.

= Tools & Technologies

- Microsoft Excel – Test case and defect documentation
- Android Devices – Application testing
- GitHub – QA portfolio and documentation

= Project Contents

This repository contains:

- Manual test cases
- Test scenarios
- Test execution results
- Defect reports
- Bug screenshots/evidence
- Testing documentation

The complete test documentation is available in the Excel workbook included in this repository.

= Tester

Md Sabi Amaan

BCA Graduate, Aspiring Manual QA / Software Tester

= Key Learning

Through this project, I gained practical experience in:

- Understanding application requirements
- Identifying test scenarios
- Designing and executing test cases
- Performing positive and negative testing
- Validating UI and application behavior
- Identifying and documenting defects
- Assigning severity and priority
- Testing applications across multiple Android devices
- Maintaining structured QA documentation

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## This project is part of my Manual QA portfolio and demonstrates my practical approach to software testing and defect reporting.
