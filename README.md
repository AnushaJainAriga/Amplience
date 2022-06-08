# Amplience
PART 1
Using Postman send a GET Request to the URL
Add in tests to check for the required fields

PART 2
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
 
 
Test Steps:
1. Launch the Browser
2. Navigate to https://github.com/6wl
3 .Check for Name/Tile: Gregory Loscombe
4. Check that location is Manchester
5. Check Followers = 15; Following = 29; Public repos = 7 and public gists = 11

