# peer_review
ISSUES WITH SCENARIO                                              HOW TO IMPROVE
Feature: Ssearching	                                               Spelt incorectly- should be Searching
I want to be able to search the site	                             I will write "As a user of the site"
So that I can find information I am looking for	                   I will break it down "I want to be able to search, so that I can find the                                                                    information I am looking for
Given http://www.clearchannelinterntional.com/	                   I will write " Given I navigate" to indicate what I want to do.
When I go to the header	                                           Not necesaary bacause header is displayed on navaigation
And I click on the icon on the right which will let me search	     Too Long
And I enter test	                                                 Spelt incorectly- should be text
And I click the search button on the right of the search field	   Too Long,
And the search executes	                                           I will use "Then" for assertion




CHANGES IMPLEMENTED
Feature-Searching
As a user of the site
I want to be able to search
So that I can find the information I am looking for


Scenario outline 2- Search
Given I navigate to https://www.clearchannelinternational.com
When I click the search icon
And I enter text in the search field
And I click on the search button
Then the information is displayed

