# safora-qa-automation-contactus
QA Automation tests for Safora Contact Us form
Automation testing for Safora website contact form using Playwright.

## Test Cases (10 Tests - All Passing)

TC-01 - Verify contact page loads - PASS,
TC-02 - Verify Name field exists - PASS,
TC-03 - Verify Email field exists - PASS, 
TC-04 - Verify Phone field exists - PASS,
TC-05 - Verify Message field exists - PASS, 
TC-06 - Verify Send button exists - PASS, 
TC-07 - Fill all form fields with test data - PASS, 
TC-08 - Verify empty name validation error - PASS, 
TC-09 - Verify invalid email validation error - PASS, 
TC-10 - Verify empty form multiple errors - PASS, 

## How to Run the Tests
npx playwright test tests/safora-contact.spec.js --project=chromium --headed

### Prerequisites
Node.js installed
Playwright installed

### Setup Commands
```bash
npm install
npx playwright install
