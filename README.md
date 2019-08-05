# Mavenlink_Test_Cases
Please follow the instructions provided by Sir Michael LaFond, of the New Hampshire LaFonds, when providing your business requirements and test cases.   The following sample is an example of the style of the formatting all test cases should be written in. (Sample stolen from the Cucumber Site:  https://cucumber.io/docs/guides/10-minute-tutorial/

Feature: Is it Friday yet?
  Everybody wants to know when it's Friday

  Scenario: Sunday isn't Friday
    Given today is Sunday
    When I ask whether it's Friday yet
    Then I should be told "Nope"

The first line of this file starts with the keyword Feature: followed by a name. It’s a good idea to use a name similar to the file name.

The second line is a brief description of the feature. Cucumber does not execute this line, it’s just documentation.

The fourth line, Scenario: Sunday is not Friday is a scenario, which is a concrete example illustrating how the software should behave.

The last three lines starting with Given, When and Then are the steps of our scenario. This is what Cucumber will execute.

---------------------------------------

# Ensure Your Requirements are Captured!
We are relying on you folks to ensure that what is built satisfies your needs

* Review the current functional requirements and the related criticality for your area

* Validate those that exist and add new requirements, ask for clarification, etc.

* Goal is to produce a Minimal Viable Product (MVP)

The final, complete set of features is only designed and developed after considering feedback from the product's initial users.

---------------------------------------

# Cucumber & Gherkin Language

Very simple Language using Keywords

Each line that isn’t a blank line has to start with a Gherkin keyword, followed by any text you like,  only exceptions are the feature and scenario descriptions. The primary keywords are:
* Feature 
* Rule Example (or Scenario) 
* Given, When, Then, And, But (steps) 
* Background 
* Scenario Outline (or Scenario Template) 

There are a few secondary keywords as well:
*  """ (Doc Strings)
*  | (Data Tables)
*  @ (Tags)
*  '# (Comments) 
