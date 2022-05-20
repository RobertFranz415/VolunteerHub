---
layout: default
title: Usability Testing
parent: Prototyping
nav_order: 5
---

## Usability Testing

### Usability Testing Tasks

You are interested in volunteering and all the apps that you have seen you don’t like. You find one app, VOLUNTEER HUB, that you like and decide to search for a volunteer opportunity near you.
You find a volunteer opportunity you are interested in. Register for the volunteer opportunity.
You want to volunteer for a specific opportunity but you also don’t want it to conflict with your existing schedule. Make sure that you only schedule volunteer opportunities during times that don’t conflict with your schedule.
You recently found out your brother is getting married! You are now unexpectedly tasked with helping with the preparations for the wedding. In the chaos of preparing, you remember that you previously signed up for a volunteer opportunity during a time when your brother is getting his suit fitted which you need to be present for. As a result, you want to make sure that the organization you signed up with does not plan for your attendance.
You moved to a new place and you would like to continue receiving the periodic pamphlets that your favorite organization mails out quarterly. Make an adjustment to ensure you receive this pamphlet.

### Notes of how Tasks were completed

Usability tests 3 and 5 were not completed because of a lack of implementation of those features at the time of testing.
For usability test 1, the user did not have something they wanted to search for right off the bat, so they scrolled down on the home page to see what was on offer there. They clicked a category that sparked their interest and then were taken to the search page. The user then tried to refine their search to a specific geographic region using the “Filter By” sidebar, but discovered that these components were static. They did, however, express that they felt it was simple to find this functionality.
For usability test 2, they simply built off of the steps they performed in test 1. After landing at the Opportunity page, they expressed some confusion about what the difference between a “job” and an “event” were and why there were different buttons for them. However, they did manage to hit the volunteer button for the “event” and schedule themselves and were pleased to see the confirmation pop-up. Despite them being able to successfully schedule themselves for this opportunity, they were never directed to create an account (which was , but this is simply due to the lack of logged-in state being captured in our prototype.
For usability test 4, the user was able to find where they could reschedule an event they had signed up for, but there was no UI implemented to actually make this change happen.
Noticed some parts of the theme weren’t consistent.
Assumed they could cancel or reschedule from the schedule page.  Hadn’t attempted to schedule a job yet, however, and was quick to figure it out once they went to the organization page.
When prompted to go to the home page they automatically clicked on the logo rather than the home button on the taskbar.
When asked to change their address they went to the account page.
Overall did not have any trouble navigating the site

### UI Usability Evaluation Questions and Responses from Users 
See Usability Test Evaluation Google Form: https://forms.gle/Y8hQrG23MBPJSFp6A

Although some of the user’s were not able to complete the tasks they did find the UI to be easy to navigate. The users were also satisfied with how quickly they were able to complete the tasks that they did finish. Some of the features that they mentioned were missing was that they were not able to edit the schedule from the schedule page. Additionally, the users mentioned that they were not able to edit their profile and that they were not able to schedule their unavailable times in the prototype. The users also felt that there was a lot of redundancy when navigating through the UI. They mentioned that a lot of the time they were being redirected to the same search page.     

![Prototype UT 1](https://user-images.githubusercontent.com/6775270/169418190-5952b32b-f438-46ea-9d85-89c22d0de3f6.jpg)

### Prototype Iteration based on Usability Testing Evaluation

Added ability to reschedule or cancel directly from the opportunity page instead of requiring the user to go to their user Schedule page

![Prototype UT 2](https://user-images.githubusercontent.com/6775270/169418225-a14eeeec-6a2b-4472-b404-a39a4b95be15.png)

Added ability to interact with search filters on the search page
![Prototype UT 3](https://user-images.githubusercontent.com/6775270/169418256-5def6c2f-cd77-4033-b4e1-aaa5de85131e.jpg)

Added ability to edit info fields on the user account page
![Prototype UT 4](https://user-images.githubusercontent.com/6775270/169418278-b5042582-e805-4d93-9d4a-b9f5987e944a.jpg)

Added ability to edit schedule and availability from the schedule page in the user profile
![Prototype UT 5](https://user-images.githubusercontent.com/6775270/169418301-75cbe2b4-b75f-42f2-aa2a-34b2ec1fcfb8.jpg)
