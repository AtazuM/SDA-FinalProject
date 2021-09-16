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
    - [Format for creation of future test cases](#format-for-creation-of-future-test-cases)
  - [Bugs](#bugs)
    - [Format for creation of future bug reports](#format-for-creation-of-future-bug-reports)

# Preface
QA Exercise - creating a test plan
**Purpose:**  to solidify the knowledge obtained in the course, by applying it in a practical setting
**Instructions:** 
* Work in pairs (to simulate RL teamworking experience)
* Create a test plan, which should include steps to identify both visual and functional defects
* Document the project on Jira, using Xray extenshion
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
    ![Image of Tour booking tool](https://content.screencast.com/users/ArtrsMielsons/folders/Default/media/39c88684-566c-4c5f-ade2-2f5c6a82ce26/Tour_booking_tool.JPG)
    * Below it should be "Featured Tours" section
    ![Image of "Featured Tours" section](https://content.screencast.com/users/ArtrsMielsons/folders/Default/media/61a1464c-e288-4c7c-a408-58f96d3c4d9f/Featured_tours_section.JPG)

*(Content can visually differ on later development versions, images are intended to show the structure of the required objects)*

### Booking a flight RIX - BER
* **Page:** [PHP Travels](https://phptravels.net/)
* **Feature:** Booking of a flight
* **Steps:**
   * Step 1: Click on "Flights" tab on the central booking tool
   * Step 2: In the field "Flying From" type in "RIX" and pick it from the provided search results by clicking on it
   * Step 3: In the field "To Destination" type in "BER" and pick it from the provided search results by clicking on it
   * Step 4: Click on the field displaying date, below "Departure Date"
   * Step 5: Navigate and select 1st October, 2021 by clicking on it
   * Step 6: Change the number of adult passangers to 2 by clicking on the "Passangers" selection and clicking on the "+" symbol in "Adults" line
   * Step 7: Click "Search"
   * Step 8: Click "Book now" on the topmost search result
   * Step 9: Scroll down to payment method selection, tick the checkbox for "PayPal"
   * Step 10: Click "Confirm Booking"
   * Step 11: Click "Proceed"
 * **Expected result:**
    * User should be transfered to PayPal payment page

### Format for creation of future test cases
* **Page:** *Provide link to the corresponding page*
* **Feature:** *Describe the tested function/element*
* **Steps:**
  * *Describe each step that should be taken to replicate desired path*
  * *Do so in a precise and conside manner*
  * *Do so in a manner that would allow Anyone to follow it*
* **Expected result:**
  * *Describe the conclusion the person running the test should achieve*
* **Actual result:**
  * *In case if the test run fails and the expected result is not achieved, actual result should be described here*

## Bugs
* bug: missing page for a featured tour ["6 days around Thailand"](https://github.com/AtazuM/SDA-FinalProject/issues/1#issue-996169051)
* bug: [FAQ Page text lacks formatting](https://github.com/AtazuM/SDA-FinalProject/issues/2#issue-996177729)

### Format for creation of future bug reports
* **Details**
  * **Type:** *Describe the type of bug encountered*
  * **URL:** *Provide link to the corresponding page*
  * **Device/OS/Browser:** *Describe the hardware and software used when encountered*
  * ***Environment*** *If multiple environments are available, state the one used*
  * **Date:** *State the date of the encounter*
  * **Priority:** *State the severity of said bug - high/medium/low*
* **Steps:**
  * *Describe each step that should be taken to replicate described bug*
  * *Do so in a precise and conside manner*
  * *Do so in a manner that would allow Anyone to follow it*
* **Expected result:**
  * *Describe the desired outcome*
* **Actual result:**
  * *Describe the actual outcome*