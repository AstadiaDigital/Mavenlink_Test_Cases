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
