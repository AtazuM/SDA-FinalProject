- [Preface](#preface)
- [Assumptions](#assumptions)
- [Tasks](#tasks)
- [Scope](#scope)
  - [In Scope](#in-scope)
  - [Browsers, platforms & devices](#browsers-platforms--devices)
  - [Out of scope](#out-of-scope)
- [Testing Strategy](#testing-strategy)
  - [Exploratory QA](#exploratory-qa)
  - [Functional QA](#functional-qa)
- [Examples](#examples)
  - [Test Cases](#test-cases)
    - [Test top navigation menus page - Tours](#test-top-navigation-menus-page---tours)
    - [Booking a flight RIX - BER](#booking-a-flight-rix---ber)
  - [Tickets](#tickets)
- [Sprint summary](#sprint-summary)
  - [Sprint 1](#sprint-1)
  - [Sprint 2](#sprint-2)

# Preface
QA Exercise - creating a test plan

**Purpose:**  to solidify the knowledge obtained in the course, by applying it in a practical setting

**Instructions:** 
* Work in pairs (to simulate RL teamworking experience)
* Create a test plan, which should include steps to identify both visual and functional defects
* Document the project on Jira

# Assumptions
* Performance testing, stress testing, API testing, development QA, etc. are not considered a part of this test plan and assignment
* This test plan focuses on functional and design QA
* Test case management will be performed using Jira's free version
* **Constraints:** The entirety of this project is limited to 2 classes of 5 hours each, including the initial task explanation, Jira demonstration, team forming, etc. 
*(The creation of this Readme falls outside of said time constraints)*

# Tasks
* Determine scope
* Create test cases
* Run created test cases

# Scope
## In Scope
Testing of [PHP Travels](https://phptravels.net/) will entail:
* GUI
* Site overall navigation functionallity
* User input and product options
* Features:
  * Booking of Hotels
  * Booking of Flights
  * Booking of Tours

## Browsers, platforms & devices
As test project is managed and performed by 2 members, with a very limited timeframe, testing will be performed only on their main devices running following OS's:
* Apple MacBook Pro 2020 M1; OS: Big Sur - latest
* Windows 10 Pro 64-bit
Testing will be conducted using latest version (at the time of testing - Version 93.0.4577.82) of Google Chrome on both devices

## Out of scope
* The connection between user input and database
* Back-end functionality
* Performance testing
* Stress testing
* API testing
* Development QA
* Regression testing

# Testing Strategy
## Exploratory QA 
* Test for usability
* Check both top and footer menu navigation
* Check visual consistency 

## Functional QA
* Develop test cases to test the main functionality of the page:
  * Booking of Hotels
  * Booking of Flights
  * Booking of Tours

# Examples
## Test Cases
### Test top navigation menus page - Tours 
* **Page:** [PHP Travels](https://phptravels.net/)
* **Feature:** Top navigation menu
* **Steps:**
   * Step 1: Navigate to the top navigation menu
   * Step 2: Click on "Tours"
* **Expected result:**
  * [Tours page](https://phptravels.net/tours) should open
  * It should contain:
    * Tool for booking tours
    ![Image of Tour booking tool](https://www.screencast.com/t/aD81JjdZ)
    * Below it should be "Featured Tours" section
    ![Image of "Featured Tours" section](https://www.screencast.com/t/UDAhRrAtr)
* **Actual result:** 
  * Tours nagivation button functions as intended, the actual result matches the expected result

### Booking a flight RIX - BER
* **Page:** [PHP Travels](https://phptravels.net/)
* **Feature:** Booking of a flight
* **Steps:**
   * Step 1: Navigate to CNN Travel
   * Step 2: Click into an article
   * Step 3: Click on the Twitter share icon under the headline
   * Step 4: Share article
   * Step 5: Check Twitter account to verify article is shared
 * **Expected result:**
  * s
* **Actual result:** 
  * x 

## Tickets
* [bug-UI (global - links): inconsistent hover state on link text [Firefox]](https://github.com/LizCottrell/quality-assurance/issues/2)
* [bug-ADA (global - footer): insufficient contrast on footer text + links](https://github.com/LizCottrell/quality-assurance/issues/1)
* [bug (home page - navigation) spelling error](https://github.com/LizCottrell/quality-assurance/issues/4)
* [bug-UX (home page - search): search button too close to hamburger nav](https://github.com/LizCottrell/quality-assurance/issues/3)

# Sprint summary
## Sprint 1
s

## Sprint 2
x