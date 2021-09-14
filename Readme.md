- [Preface](#preface)
- [Assumptions](#assumptions)
- [Tasks](#tasks)
- [Scope](#scope)
  - [In Scope](#in-scope)
  - [Browsers, platforms & devices](#browsers-platforms--devices)
  - [Out of scope](#out-of-scope)
- [Testing Strategy](#testing-strategy)
  - [Exploratory QA](#exploratory-qa)
  - [Design QA](#design-qa)
  - [Functional QA](#functional-qa)
- [Examples](#examples)
  - [Test Cases](#test-cases)
    - [Searching for a topic of interest on CNN Tech](#searching-for-a-topic-of-interest-on-cnn-tech)
    - [Sharing an article on CNN Travel using Twitter](#sharing-an-article-on-cnn-travel-using-twitter)
  - [Tickets](#tickets)

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
  * Booking of hotels
  * Booking of flights
  * Booking of tours

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
* 

## Design QA
* Obtain approved designs
* 

## Functional QA
* Obtain list of requirements
* 

# Examples
## Test Cases

### Searching for a topic of interest on CNN Tech 
* **Page:** CNN Tech
* **Feature:** Search
* **Flow:** Search for a topic of interest
* **Steps:**
   * Step 1: Navigate to CNN Tech
   * Step 2: Click on the search icon
   * Step 3: Search for a topic of interest
   * Step 4: *need requirements to write expected result*
* **Edge Cases**
   * Enter nothing in the search bar and click search

### Sharing an article on CNN Travel using Twitter
* **Page:** CNN Travel
* **Feature:** Share an article
* **Flow:** Share an article using Twitter
* **Steps:**
   * Step 1: Navigate to CNN Travel
   * Step 2: Click into an article
   * Step 3: Click on the Twitter share icon under the headline
   * Step 4: Share article
   * Step 5: Check Twitter account to verify article is shared


## Tickets
* [bug-UI (global - links): inconsistent hover state on link text [Firefox]](https://github.com/LizCottrell/quality-assurance/issues/2)
* [bug-ADA (global - footer): insufficient contrast on footer text + links](https://github.com/LizCottrell/quality-assurance/issues/1)
* [bug (home page - navigation) spelling error](https://github.com/LizCottrell/quality-assurance/issues/4)
* [bug-UX (home page - search): search button too close to hamburger nav](https://github.com/LizCottrell/quality-assurance/issues/3)


Include the following information for every new issue:
* **Title:**`````<type>[optional scope]: <description>````` - clearly define *feature/location* + *issue* in the title
* **Labels:**
  * Bug type (functional, design or accessibility bug)
  * Priority
  * Environment 
  * Date
  * URL
* **Description:**
  * Device (native or simulator), OS, browser combination
  
* **Screenshots** or gif/video
* **Links:** 
  * to failed requirement
