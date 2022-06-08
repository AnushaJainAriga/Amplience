# Amplience
Scenario: Validate HTML presentation layer is correctly displaying the information 
https://github.com/6wl
 
    Given I navigate to https://github.com/6wl
    Then  I verify that the page contains the following values
name = Gregory Loscombe
location = Manchester
public repos = 7
public gists = 11
followers = 15
following = 29

PART 1
Tets Steps: Using Postman send a GET Request to the URL
Add in tests to check for the required fields

PART 2
 
Test Steps:
1. Launch the Selenium IDE
2. Start a ne project
3. Add URL https://github.com/6wl
4. URL opens up on the browser
5. Check for Name/Tile: Gregory Loscombe
6. Check that location is Manchester
7. Check Followers = 15; Following = 29; Public repos = 7 and public gists = 11

