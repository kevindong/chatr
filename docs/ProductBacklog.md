# Chatr - Product Backlog

Team 5: Michael Bilstein (@Meegul), Kevin Dong (@kevindong), Scott Mangiapane (@scottmangiapane), Jay Patel (@patel445), and Jordan Pitlor (@piticent123).

## Product Statement

Today, there are chatbots available for most online platforms. For a software engineer, setting up one of these chatbots seems trivial; however, for people without software development experience, importing packages from npm might as well be impossible. Setting up a bot should be easy, intuitive, and accessible to those without programming knowledge. Chatr will allow users to pick and choose what modules their bot should have via a web interface. Developers will be able to upload their own self-created modules for other users to add onto their bot. 


## Background Information

The main problem, and the focus of this project, is that it’s very difficult for non-developers to make a bot customized to them. For developers, computer science students, etc., making a bot is fairly trivial. Perhaps the most challenging part of making a bot is creating the boilerplate activities that is common across all bots (e.g. receiving/sending messages/information to/from the user, acquiring users, increasing the discoverability of their bot, etc.).

There is a similar service to Chatr already in existence. It’s called ‘Flow XO’. It also allows users to pick and choose modules to add onto each user’s custom chat bots. The difference between them and Chatr is that Flow XO targets business users. Flow XO also does not allow 3rd party developers to upload modules for other users to use. In contrast to that, Chatr will be primarily focused upon consumers and will allow 3rd party developers access to the platform. 

## Requirements

### Functional Requirements:
1. As a user, I would like to register for an account with an email and password.
2. As a user, I would like to change my email.
3. As a user, I would like to change my password. 
4. As a user, I would like to login using my account credentials to manage my bot.
5. As a user, I would like to logout of my account.
6. As a user, I would like to reset my password if I forget it.
7. As a user, I would like to delete my account.
8. As a user, I would like to have a single marketplace to see all available modules.
9. (If time allows) As a user, I would like to have multiple platforms on which I can deploy my bot.
10. As a user, I would like to add modules to my bot at any time.
11. As a user, I would like to remove modules from my bot at any time.
12. As a user, I would like to be able to search for modules.
13. As a user, I would like to switch bot configurations at any time.
14. As a user, I would like to enable / disable a bot on specific chats.
15. As a user, I would like to send bug reports to developers if my selected modules aren’t working as I expect.
16. (If time allows) As a user, I would like federated login (e.g. “Login with Facebook”).
17. As a developer, I would like to upload my own module(s).
18. As a developer, I would like users to use my uploaded module(s).
19. As a developer, I would like to publish my module(s) to a public database.
20. As a developer, I would like to see how many users are using my module(s).
21. As a developer, I would like to remove my module(s) at any time.
22. As a developer, I would like to update my module(s) at any time.
23. As a developer, I would like to automatically be sent error logs when they occur.
24. (If time allows) As a developer, I would like to send push notifications to the users of my module(s).
25. (If time allows) As a developer, I would like to send messages to the users of my module(s) without them starting the conversation.
26. As an administrator, I would like to see a list of users and their accounts.
27. As an administrator, I would like to view analytics about different bot modules.
28. As an administrator, I would like to send a verification email to the users .
29. As an administrator, I would like to unpublish bots in the marketplace that are malicious.
30. As an administrator, I would like to reset all users’ passwords in case of data breach.
31. As an administrator, I would like to ban users.
32. As an administrator, I would like to ban developers.
33. As an administrator, I would like to delete users.
34. (If time allows) As an administrator, I would like to an easy way to analyze statistics about user engagement with the bot.

### Non-Functional Requirements:
1. There will be a web application for services.
2. The interface must be easy to use.
3. Must have a secure and strong connection between UI, server, and database. 
4. Must be reliable and work quickly/instantly.
5. Must be responsive so mobile users can use.
