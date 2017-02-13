# Chatr - Sprint 1 Planning Document

Team 5: Michael Bilstein (@Meegul), Kevin Dong (@kevindong), Scott Mangiapane (@scottmangiapane), Jay Patel (@patel445), and Jordan Pitlor (@piticent123).

*Note: This document is not the controlling version of the sprint 1 planning document. The submitted PDF is.*
# Sprint Overview 

For the first sprint, we are going to focus on setting up our environments, learning the essentials, and hopefully getting the structure of our website done. This includes creating a homepage/login page with logout. In addition, the user should be able to navigate the website. 

**Scrum Master:** ​ Michael Bilstein

**Meeting Schedule:** ​Fridays at 6:00pm 

**Risks/Challenges:** ​Biggest challenge faced is learning the different tools and setting up the environment for each member. We will need to coordinate well.  Also since this is our first sprint we will need to be careful and ensure we are working in a timely manner on our tasks. In addition, there will a lot of "blocking" tasks (i.e. creating web pages must wait for the web server to be set up first). This may present a lot of timing issues. 

# User Story #1
As a user, I would like to login using Facebook authentication.

<table>
  <tr>
    <td>#</td>
    <td>Description</td>
    <td>Time (hrs)</td>
    <td>Owner</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Set up the production and development database of users on Heroku.</td>
    <td>5</td>
    <td>Kevin</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Set up the Node.js API production and development server on Heroku.</td>
    <td>8</td>
    <td>Michael</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Set up the Node.js Web-production and development server on Heroku.</td>
    <td>8</td>
    <td>Michael</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Set up web client templating using Pug on the web-server.</td>
    <td>10</td>
    <td>Jay</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Implement routing on the web-server.</td>
    <td>12</td>
    <td>Scott</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Implement Facebook OAuth using Passportjs.</td>
    <td>12</td>
    <td>Kevin</td>
  </tr>
  <tr>
    <td>7</td>
    <td>Implement ability maintain a session on web client</td>
    <td>3</td>
    <td>Scott</td>
  </tr>
  <tr>
    <td>8</td>
    <td>Implement ability to logout.</td>
    <td>2</td>
    <td>Kevin</td>
  </tr>
  <tr>
    <td>9</td>
    <td>Establish and implement API endpoints for logging in and out.</td>
    <td>3</td>
    <td>Kevin</td>
  </tr>
</table>

Acceptance Criteria​:
* Given that the user has a facebook account and clicks login button, the user will be able to successfully go to the console page and will be added to our database. 
* Given that the user is logged in, The user will also be able to maintain a session and logout.

# User Story #2
As a user I would like to be greeted by a splash page.

<table>
  <tr>
    <td>#</td>
    <td>Description</td>
    <td>Time (hrs)</td>
    <td>Owner</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Create a website page that gives description.</td>
    <td>5</td>
    <td>Jay</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Make the website page fully responsive.</td>
    <td>5</td>
    <td>Jay</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Create template to maintain common theme across all web pages.</td>
    <td>10</td>
    <td>Jay</td>
  </tr>
</table>

Acceptance Criteria​:
* Given that the user is on our domain, they will be able to see a description of our services. 
* Given that the user is on the webpage, it will scale to any screen size.

# User Story #3
As a user, I would like to have a single marketplace to see all available modules.

<table>
  <tr>
    <td>#</td>
    <td>Description</td>
    <td>Time (hrs)</td>
    <td>Owner</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Setup modules production and development database.</td>
    <td>5</td>
    <td>Kevin</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Establish API endpoints for GET details about a single module.</td>
    <td>5</td>
    <td>Michael</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Extend API to get a list of all available modules.</td>
    <td>4</td>
    <td>Jordan</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Establish webpage to see modules.</td>
    <td>4</td>
    <td>Scott</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Have webpage make actual API calls to get all available modules.</td>
    <td>3</td>
    <td>Scott</td>
  </tr>
</table>
Acceptance Criteria​:
* Given that I am a logged in user, I should see all the modules available on a page.
* Given that I am a 3rd party developer, I should be able to make API calls to get a list of all module and any module details.

# User Story #4
As a developer, I would like to upload my own module(s).

<table>
  <tr>
    <td>#</td>
    <td>Description</td>
    <td>Time (hrs)</td>
    <td>Owner</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Establish and implement API for uploading a module on the backend.</td>
    <td>5</td>
    <td>Jordan</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Establish webpage for uploading module.</td>
    <td>5</td>
    <td>Jordan</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Have webpage make actual API calls to upload module.</td>
    <td>4</td>
    <td>Jordan</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Enable the API to list all modules created by a certain user.</td>
    <td>3</td>
    <td>Jordan</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Have the webpage show all modules the current user has uploaded.</td>
    <td>5</td>
    <td>Jordan</td>
  </tr>
</table>
Acceptance Criteria​:
* Given the user is logged in, the user should be able to access a developer page where they can upload their own modules.
* Given the user is logged in and on the developer page, the user should be able to copy and upload source code, provide a description and name for their module, and upload the module for admin review.
* Given the user has their own modules uploaded, the developer page should show a list of their modules, their information, and their status.

# User Story #5
As an admin, I would like to review modules.

<table>
  <tr>
    <td>#</td>
    <td>Description</td>
    <td>Time (hrs)</td>
    <td>Owner</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Establish and implement an API for listing all pending modules.</td>
    <td>2</td>
    <td>Scott</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Implement ability to show all pending modules on the frontend.</td>
    <td>3</td>
    <td>Scott</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Establish and implement an API to approve a module on the backend.</td>
    <td>3</td>
    <td>Scott</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Implement ability to approve a module on the frontend.</td>
    <td>1</td>
    <td>Scott</td>
  </tr>
</table>
Acceptance Criteria​:
* Given the current user is an admin, the user should be able to see all pending modules and the appropriate details about them.
* Given the user is an admin and there are pending modules, the admin should be able to approve modules after reviewing their contents.
* Given the current user is an admin, the admin should be able to use the web interface to approve modules. 

# User Story #6
As a user, I would like to add modules to my bot at any time.

<table>
  <tr>
    <td>#</td>
    <td>Description</td>
    <td>Time (hrs)</td>
    <td>Owner</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Create User-Modules production and development database.</td>
    <td>5</td>
    <td>Kevin</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Establish and implement API endpoints for adding user-module relationships.</td>
    <td>5</td>
    <td>Michael</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Create webpages for adding modules to bot.</td>
    <td>4</td>
    <td>Jordan</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Have webpage make actual API calls for adding modules.</td>
    <td>4</td>
    <td>Michael</td>
  </tr>
</table>
Acceptance Criteria​:
* Provided the user is logged in, the user should be able to navigate to a webpage where they can add new modules to their bot.
* Provided the user is logged in, the user should be able to add new modules to their bot.

# Remaining Backlog
## Functional Requirements
1. As a user, I would like to delete my account.
2. (If time allows) As a user, I would like to have multiple platforms on which I can deploy my bot.
3. As a user, I would like to remove modules from my bot at any time.
4. As a user, I would like to be able to search for modules.
5. As a user, I would like to switch bot configurations at any time.
6. As a user, I would like to enable / disable a bot on specific chats.
7. As a user, I would like to send bug reports to developers if my selected modules aren’t working as I expect.
8. As a developer, I would like users to use my uploaded module(s).
9. As a developer, I would like to publish my module(s) to a public database.
10. As a developer, I would like to see how many users are using my module(s).
11. As a developer, I would like to remove my module(s) at any time.
12. As a developer, I would like to update my module(s) at any time.
13. As a developer, I would like to automatically be sent error logs when they occur.
14. (If time allows) As a developer, I would like to send push notifications to the users of my module(s).
15. (If time allows) As a developer, I would like to send messages to the users of my module(s) without them starting the conversation.
16. As an administrator, I would like to view analytics about different bot modules.
17. As an administrator, I would like to unpublish bots in the marketplace that are malicious.
18. As an administrator, I would like to be able to message all users at once.
19. As an administrator, I would like to ban users.
20. As an administrator, I would like to ban developers.
21. As an administrator, I would like to delete users.
22. (If time allows) As an administrator, I would like to an easy way to analyze statistics about user engagement with the bot.
23. (If time allows) As an administrator, I would like to approve or deny the modules that developers submit.

## Nonfunctional Requirements
1. As a user, I would like to add an unlimited number of modules. 
2. As a user, I would like the bot to reply within a few seconds.
3. As a user, I would like the web interface to be snappy.
4. As a user, I would like the bot to tell me if the service is down rather than the bot just not working.
5. As a developer, I would like my submitted module to be generally available to users within a short amount of time.
6. As a developer, I would like my module to support an unlimited number of users. 
7. As an administrator, I would like the platform to respond to at least 100 messages/second. 
8. As an administrator, I would like to require each module to decide on a response to a message within 5 seconds or else the evaluation of the code will automatically terminate and the user will see an error message.
9. There will be a web application for users to manage their bot and modules.
10. The web application will be responsive so that mobile users will have a good experience.
11. The web app must be easy to use.
12. There must be a secure connection between the UI, server, and database.
13. The web app must be reliable and work quickly. 