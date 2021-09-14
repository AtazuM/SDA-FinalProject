- [Preface](#preface)
- [Assumptions](#assumptions)
- [Tasks](#tasks)
- [Scope](#scope)
  - [Pages, features & flows](#pages-features--flows)
  - [Browsers, platforms & devices](#browsers-platforms--devices)
  - [Out of scope](#out-of-scope)
- [Testing Strategy](#testing-strategy)
  - [Exploratory QA](#exploratory-qa)
  - [Design QA](#design-qa)
  - [Functional QA](#functional-qa)
  - [Accessibility QA](#accessibility-qa)
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

* 


# Tasks
* 

# Scope

## Pages, features & flows
Break down CNN.com into pages, features and user flows.  

Examples:
* Pages
    * Home page (navigation, article sections, ad-space, footer, etc.)
    * Travel
    * Money
    * Video
* Features
    * Search
    * Video
    * Sharing articles
* User flows
    * Using search to find articles on topics of interest
    * Browsing news, clicking into articles and getting back to home screen
    * Using CNN.com to watch TV and videos
    * Sharing articles via Facebook, Twitter and Email

## Browsers, platforms & devices
List everything within scope.

## Out of scope
List all out-of-scope features and functionality.

Examples:
* advertisements
* cable provider log-in

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

## Accessibility QA
* Accessibility or compliance?
* 

Regression testing (make sure no other features were unintentionally broken after fixes)

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
