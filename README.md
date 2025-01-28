// README for Cypress Test Suite
// ====================================

/*
# Cypress Test Suite with Cucumber

## Introduction

This project demonstrates automated testing of the website https://www.demoblaze.com using Cypress with the Cucumber plugin for Gherkin-style test cases.

### Key Features
- Automates Sign Up, Log In, and Log Out processes.
- Verifies cart management (adding and deleting products).
- Covers the purchase flow from adding products to order confirmation.
- Tests written using Gherkin syntax (`Given`, `When`, `Then`) for readability and maintainability.

---

## Project Setup

### Prerequisites
1. Node.js (v16+)
2. Cypress (v12+)
3. Cucumber Plugin
4. A browser compatible with Cypress.

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
   cd <repository-folder>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Open Cypress Runner:
   ```bash
   npx cypress open
   ```

---

## Test Scenarios

### Sign Up Process
Feature: Sign Up Process  
Tests the ability to sign up, log in, and log out successfully.

### Cart Management
Feature: Product Cart Management  
Verifies adding a product to the cart and successfully deleting it.

### Purchase Process
Feature: Purchase Process  
Simulates completing a purchase transaction.

---

## Running the Tests

1. Run all tests using the Cypress UI:
   ```bash
   npx cypress open
   ```

2. Execute specific tests:
   Navigate to the `cypress/e2e` directory and select the desired feature file (e.g., `signUp.feature`).

---

## Directory Structure

```
/cypress
  /e2e
    - signUp.feature
    - cart.feature
    - purchase.feature
  /support
    - step_definitions
      - signUpSteps.js
      - cartSteps.js
      - purchaseSteps.js
cypress.config.js
package.json
README.md
```

---

## Reporting
- Test reports are automatically generated in the console.
- You can integrate `cypress-html-reporter` for more detailed HTML reports.

### Generate Reports
Install and run the HTML reporter:
```bash
npm run cypress:report
```

---

## Additional Notes

- Use stable selectors for UI elements to ensure robust tests.
- Mock external dependencies (e.g., payment gateways) during integration testing for consistent results.
- Validate asynchronous actions to handle dynamic UI changes (e.g., loading spinners).

---

*/
