<!-- omit in toc -->
# **Coder Academy - Assignment T3A2 Part A - Full Stack MERN App Documentation: Submitted by Mario Lisbona and Callum Rowston**

<!-- omit in toc -->
## Table of Contents
- [**R1 - Description of your website**](#r1---description-of-your-website)
  - [Purpose](#purpose)
  - [Functionality / Features](#functionality--features)
  - [Target Audience](#target-audience)
  - [Tech Stack](#tech-stack)
- [**R2 - Dataflow Diagrams**](#r2---dataflow-diagrams)
- [**R3 - Application Architecture Diagram**](#r3---application-architecture-diagram)
- [**R4 - User Stories**](#r4---user-stories)
- [**R5 - Wireframes for Desktop, Mobile and Tablet**](#r5---wireframes-for-desktop-mobile-and-tablet)
- [**R6 - Screenshots of your Trello board**](#r6---screenshots-of-your-trello-board)
  - [Planning Methodology](#planning-methodology)
- [Links](#links)
- [**Part B Documentation**](#part-b-documentation)
- [**Manual User Testing**](#manual-user-testing)
  - [Website Displays as expected](#website-displays-as-expected)
  - [Member Registration Functions as expected](#member-registration-functions-as-expected)
  - [Member Login Functions as expected](#member-login-functions-as-expected)
  - [Member Logged-in State Changes Page Display as expected](#member-logged-in-state-changes-page-display-as-expected)
  - [Posts Create, Edit and Delete as expected](#posts-create-edit-and-delete-as-expected)
  - [Comments Create, Edit and Delete as expected](#comments-create-edit-and-delete-as-expected)
- [**Postman Testing**](#postman-testing)

## **R1 - Description of your website**

### Purpose

This project aims to provide an online forum to allow people to share their travel stories, with the hope of creating social connections and a sense of community through users' shared love of travel. By having members share their travel stories, they are providing valuable information through a personal lens that other users can use to help plan their next adventure.

### Functionality / Features

- Read the latest travel stories
- Find travel stories from your favourite continent
- Site Navigation
- Member Account Creation
- Post your travel story
- Comment on posts

Additional features to be added if time allows:

- Allow members to rate posts
- Allow members to add posts to their 'favourites'

### Target Audience

This application is aimed at people wishing to read travel stories written by others about their adventures around the world. It is also for people wishing to share their own travel stories and have discussions about these stories with an online community.

### Tech Stack

**Front-end**

- HTML
- CSS
- JavaScript
- [React.js](https://reactjs.org/)
- [Bootstrap](https://getbootstrap.com/)

**Back-end**

- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)

**Database**

- [MongoDB](https://www.mongodb.com/atlas/database)

**Deployment**

- [Netlify](https://www.netlify.com/)
- [Railway](https://railway.app/)

**Testing**

- [Vitest](https://vitest.dev/)
- [Jest](https://railway.app/)

**Project Management**

- [Trello](https://trello.com)
- [Google Drive](https://www.google.com/intl/en_au/drive/)
- [Discord](https://discord.com/)

**DevOps Tools**

- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)
- [VS Code](https://code.visualstudio.com/)

**Design Tools**

- [Lucidchart](https://www.lucidchart.com/pages/)
- [Draw.io](https://app.diagrams.net/)

## **R2 - Dataflow Diagrams**

![DFDGuest](docs/DataFlowDiagram-GuestCR.png)
![DFDMemberR](docs/DataFlowDiagram-MemberR.png)
![DFDMemberCUD](docs/DataFlowDiagram-MemberCUD.png)

## **R3 - Application Architecture Diagram**

![AAD](docs/ApplicationArchitectureDiagram.png)

## **R4 - User Stories**

Initial user stories were created to outline desired features that reflect the projects intended audience and purpose.

<details>

<summary>Stage One - User - All / Guest</summary>

<br>

- As a user I want a navigation bar to show me what is on the site.
- As a user I want to read travel stories posted on the forum.
- As a user I want to see a post preview before viewing the entire post
- As a user I want to see the latest forum posts.
- As a user I want to see posts about a particular continent .
- As a user I want to read other users' comments on travel posts.
- As a user I want to be able to view an about page with information about the websites intended purpose and other background information.
- As a user I want to be able to view a contact page so I can message the creators about any issues with the website.
- As a user I want to be able to sign up to the forum.

</details>

<details>

<summary>Stage One - User - Member</summary>

<br>

- As a member I want to write and post my own travel stories.
- As a member I want to comment on other members' posts .
- As a member I want to view a list of all the posts I have made
- As a member I want to comment on my own posts.
- As a member I want to be able to edit posts I have already made.
- As a member I want to be able to delete a post I made.

</details>

<br>

User stories were then revised to reflect any changes to features and to provide context for why specific features will be developed.

<details>

<summary>Stage Two - User - All / Guest</summary>

<br>

- As a user I want a navigation bar to show me what is on the site so I can navigate to my desired content.
- As a user I want to read travel stories posted on the forum so I can learn about other people's trips.
- As a user I want to see a post preview before viewing the entire post so I can decide if it will interest me.
- As a user I want to see the latest forum posts so I can keep up with current trends in travel and the forum community.
- As a user I want to see posts about a particular continent  so I can find out more about that region and if I want to travel there.
- As a user I want to read other users' comments on travel posts so I can see what others think to help me decide if I want to travel there.
- As a user I want to be able to view an about page with information about the websites intended purpose and other background information so I can get a better understanding of the creators intent
- As a user I want to be able to view a contact page so I can message the creators about any issues with the website
- As a user I want to be able to sign up to the forum so I can engage with and contribute to the forum community and use all the site features.

</details>

<details>

<summary>Stage Two - User - Member</summary>

<br>

- As a member I want to write and post my own travel stories so I can tell the forum community about my trips.
- As a member I want to comment on other members posts so I can ask them questions about their trip and tell them what I loved about their post.
- As a member I want to view a list of all the posts I have made so I can look back on my posts and easily navigate to them
- As a member I want to comment on my own posts so I can answer any questions and engage with the community interested in my travel story.
- As a member I want to be able to edit posts I have already made so I can fix any mistakes and keep my story up-to-date if I think of something I should have added..
- As a member I want to be able to delete a post I made so I can remove posts that I’ve decided I don’t like anymore.

</details>

<br>

## **R5 - Wireframes for Desktop, Mobile and Tablet**

![Register](./docs/Register.png)

![Login](./docs/Login.png)

<details>

<summary>Guest Wireframes</summary>

<br>

![Landing Page](./docs/Navbar-Guest.png)
![Landing Page](./docs/LandingPage-Guest.png)
![Landing Page](./docs/BrowseAll-Guest.png)
![Landing Page](./docs/BrowseByContinent-Guest.png)
![Landing Page](./docs/FullPagePost-Guest.png)
![Landing Page](./docs/Contact-Guest.png)
![Landing Page](./docs/About-Guest.png)

</details>

<details>

<summary>Member Wireframes</summary>

<br>

![member-navbar](./docs/Navbar-Member.png)
![member-navbar](./docs/Homepage-Member.png)
![member-navbar](./docs/BrowseAll-Member.png)
![member-navbar](./docs/BrowseByContinent-Member.png)
![member-navbar](./docs/FullPagePost-Member.png)
![member-navbar](./docs/Contact-Member.png)
![member-navbar](./docs/About-Member.png)
![member-navbar](./docs/MyPosts-Member.png)
![member-navbar](./docs/CreatePost-Member.png)

</details>

<details>

<summary>Color Pallet and Hero Image themes</summary>

<br>

![Color Pallet and Hero Image](./docs/ColorPalleteImageThemes-3.png)
![Color Pallet and Hero Image](./docs/ColorPalleteImageThemes-2.png)
![Color Pallet and Hero Image](./docs/ColorPalleteImageThemes-1.png)
![Color Pallet and Hero Image](./docs/ColorPalleteImageThemes.png)

</details>

## **R6 - Screenshots of your Trello board**


Screenshots were taken at least daily and are dated in the file name.

<details>

<summary>Trello Screenshots Part A</summary>

<br>

![17-1-23-1](docs/Screenshots-PartA/Trello-A-17-1-23-1.png)
![17-1-23-2](docs/Screenshots-PartA/Trello-A-17-1-23-2.png)
![18-1-23-1](docs/Screenshots-PartA/Trello-A-18-1-23-1.png)
![18-1-23-2](docs/Screenshots-PartA/Trello-A-18-1-23-2.png)
![20-1-23-1](docs/Screenshots-PartA/Trello-A-20-1-23-1.png)
![20-1-23-2](docs/Screenshots-PartA/Trello-A-20-1-23-2.png)

</details>

<br>

### Planning Methodology

We have chosen to implement an Agile workflow centered around the Kanban framework, by using Trello to delegate and manage tasks. This approach was chosen as it allows for flexibility and transparency throughout development and allows us to easily see the progress and workflow of each team member. We discussed who would take on each requirement and used the Kanban board to assign those tasks as agreed upon. A GitHub repository was set up for documentation that both group members had collaborator access to, allowing us to each work on separate tasks in our own branch and then merge them into the same document.

We also discussed our strengths and weaknesses and decided to split up responsibilities for the application development as so:

- Mario - Client / front-end
- Callum - Server / back-end

Cards were created in Trello and labelled as 'client' or 'server' and assigned to the appropriate member to help separate concerns.

We each set up a corresponding GitHub repository for our assigned sections and added the other as a collaborator. We agreed on a branching approach whereby each member works in a local branch and when finished, submits a pull request to merge it into the main branch once approved.

CI/CD will be utilised by linking the corresponding repository to our chosen deployment; Netlify for the client and Railway for the server. This will allow us to easily test the application during development.

## Links

- [Client GitHub Repository](https://github.com/MarioLisbona/CA-T3A2-B-travelers-forum-client)
- [Server GitHub Repository](https://github.com/CallumRowston/CA-T3A2-B-travelers-forum-server)
- [Trello Workspace](https://trello.com/invite/b/LD1ZUwnS/ATTIa1a5b199a938633ae2b66720915b02c4F4F552AD/t3a2-part-a-b)

## **Part B Documentation**

## **Manual User Testing**

### Website Displays as expected

|Test  |Expected Outcome   |Test Outcome   |
|----|----|----|
|When app first loads, home page displays navbar correctly|Navbar displays with logo/home button, Browse all destinations, Browse by continent dropdown, About, Login & register|✅    |
|Browse by continent dropdown is displays continent options for all continents|Dropdown menu displays all continents (7 options)|✅    |
|When app first loads, home page displays hero image|Hero image displays in full width|✅    |
|When app first loads, home page displays CTA element|CTA element displays with welcome message and register & login buttons|✅    |
|When app first loads, home page displays 8 latest preview cards|The 8 latest posts are dispalyed as preview cards, ordered by most recently posted|✅    |
|Preview cards display all elements|Preview cards display title, author, continent, time since posted, preview of content and 'Read more' button|✅    |
|'Browse by all Destinations' displays a page with preview cards for all posts|All posts on the site are represented by a preview card with the most recently posted at the top of the page|✅    |
|Selecting a continent from the continent dropdown navigates to the correct page|Selecting a continent navigates to its corresponding page|✅    |
|Continent page displays correct hero image for that continent|Hero image relating to the selected continent is displayed|✅    |
|Continent page displays a relevant welcome message and blurb|Welcome message and blurb relating to the selected continent is displayed|✅    |
|Continent page displays preview cards|All posts in the selected continent are displayed as preview cards with the latest posts displayed first|✅    |
|About navbar link navigates to About page|The about page is correctly displayed with Lorum Ipsum text|✅    |
|'Register' button navigates to Register page|The registration page is displayed when clicking a 'Register' button from any other page or navbar|✅    |
|'Login' button navigates to Login page|The login page is displayed when clicking a 'Login' button from any other page or navbar|✅    |
|Register page displays form and button elements correctly|Register page displays form with username, password, confirm password, 'Sign Up' button and 'Login' button for already registered members|✅    |
|Login page displays form and button elements correctly|Login page displays form with username, password and 'Login' button |✅    |
|Terms of Service footer link|Terms of Service page displays with title 'Terms of use and Conditions' |✅    |
|Privacy Policy footer link|Privacy Policy page displays with title 'View our privacy policies' |✅    |
|Contact Us footer link|Contact Us page displays with title 'Connect with us at the links below' and blurb and social media links |✅    |

---

### Member Registration Functions as expected

|Test  |Expected Outcome   |Test Outcome   |
|----|----|----|
|1 or more empty fields in Register form|'Sign Up' button is greyed out and cannot be clicked|✅    |
|All fields do not have green cheque mark in Register form|'Sign Up' button is greyed out and cannot be clicked|✅    |
|Enter 'Tes' in 'Username' field|Error message displays: '4 to 24 characters, Must begin with a letter, Letters, numbers, underscores, hyphens allowed'|✅    |
|Enter 'TestTestTestTestTestTest1' (25 characters) in 'Username' field|Error message displays: '4 to 24 characters, Must begin with a letter, Letters, numbers, underscores, hyphens allowed'|✅    |
|Enter '1Test' in 'Username' field|Error message displays: '4 to 24 characters, Must begin with a letter, Letters, numbers, underscores, hyphens allowed'|✅    |
|Enter 'TestTest!' in 'Username' field|Error message displays: '4 to 24 characters; Must begin with a letter; Letters, numbers, underscores, hyphens allowed'|✅    |
|Enter 'Test-Test' in 'Username' field|Success green cheque mark displays|✅    |
|Enter 'Test_Test' in 'Username' field|Success green cheque mark displays|✅    |
|Enter 'TestTest1' in 'Username' field|Success green cheque mark displays|✅    |
|Enter 'Pass' in 'Password' field|Error message displays: '8 to 24 characters; Must include uppercase and lowercase letters, a number and a special character; Allowed special characters !@#$%'|✅    |
|Enter 'PasswordPassword12345!@#%' (25 characters) in 'Password' field|Error message displays: '8 to 24 characters; Must include uppercase and lowercase letters, a number and a special character; Allowed special characters !@#$%'|✅    |
|Enter 'Password' in 'Password' field|Error message displays: '8 to 24 characters; Must include uppercase and lowercase letters, a number and a special character; Allowed special characters !@#$%'|✅    |
|Enter 'Password1' in 'Password' field|Error message displays: '8 to 24 characters; Must include uppercase and lowercase letters, a number and a special character; Allowed special characters !@#$%'|✅    |
|Enter 'Password@' in 'Password' field|Error message displays: '8 to 24 characters; Must include uppercase and lowercase letters, a number and a special character; Allowed special characters !@#$%'|✅    |
|Enter 'Password1^' in 'Password' field|Error message displays: '8 to 24 characters; Must include uppercase and lowercase letters, a number and a special character; Allowed special characters !@#$%'|✅    |
|Enter 'Password123@' in 'Password' field|Success green cheque mark displays|✅    |
|Enter '@123Password' in 'Password' field|Success green cheque mark displays|✅    |
|Enter 'Password' in 'Password' field and in 'Confirm Password Field'|Error red cross displays on 'Password' field and success green cheque mark displays on 'Confirm Password' field.|✅    |
|Enter 'Password' in 'Password' field and enter 'Password123@' in 'Confirm Password Field'|Error red cross displays on 'Password' field and on 'Confirm Password' field.|✅    |
|Enter 'Password123@' in 'Password' field and in 'Confirm Password Field'|Success green cheque mark displays on 'Password' field and 'Confirm Password' field and 'Sign Up' button can be clicked.|✅    |
|Enter username already in database with valid 'Password' and 'Confirm Password' fields and click 'Sign Up' button|Error popup window with message 'Registration failed - Username taken'|✅    |
|Enter valid username and password in all fields and click 'Sign Up' button|'Registration Successfful' popup message is displayed and then Login page is displayed with username field populated|✅    |

---

### Member Login Functions as expected

|Test  |Expected Outcome   |Test Outcome   |
|----|----|----|
|1 or more empty fields in Login form|Clicking 'Login' button prompts error message 'Please fill out this form'|✅    |
|Enter 'Tes' (invalid username) in 'Username' field and 'Password1' (invalid/wrong password) in 'Password' field and click 'Login button'|Error popup window with message 'Login failed - Incorrect username or password'|✅    |
|Enter 'Callum1' (valid username) in 'Username' field and 'Password123@' (wrong password) in 'Password' field and click 'Login button'|Error popup window with message 'Login failed - Incorrect username or password'|✅    |
|Enter 'Test' (valid username) in 'Username' field and 'Callum123!' (correct password for different user) in 'Password' field and click 'Login button'|Error popup window with message 'Login failed - Incorrect username or password'|✅    |
|Enter 'Callum1' (valid username) in 'Username' field and 'Callum123!' (correct password for user) in 'Password' field and click 'Login button'|App navigates to home page with welcome message: 'Hi Callum1, welcome to the forum'|✅    |

---

### Member Logged-in State Changes Page Display as expected

|Test  |Expected Outcome   |Test Outcome   |
|----|----|----|
|Logging in as 'TestUser99' changes navbar correctly|'Login' and 'Register' buttons replaced by dropdown menu with 'TestUser99' as title|✅    |
|Logging in as 'TestUser99' changes navbar correctly|Displays dropdown menu with 'TestUser99' as title includes 'My Posts', 'Create A Post', 'About' and 'Logout' options|✅    |
|As 'TestUser99', select 'My Posts' from dropdown navigates to correct page|As 'TestUser99' displays message about creating a post with buttons for 'My Posts' and 'Create A Post'|✅    |
|As 'TestUser99', select 'My Posts' from dropdown navigates to correct page and populates cards|Displays preview cards for posts where the author is 'TestUser99'|✅    |
|As 'TestUser100', select 'My Posts' from dropdown does not populate cards|Display message 'You havn't made any posts yet.' with no preview cards displayed |✅    |
|As 'TestUser99', select 'Create A Post' from dropdown or from 'My Posts' page|Displays post creation page with 'Create a post' message and post creation form|✅    |
|As 'TestUser99', clicking 'Read more' on a preview card displays the post with comment form|Post and comment form display with submit button |✅    |
|As 'TestUser99', clicking 'Log out' from dropdown logs the user out|App redirects to home page with normal non-member functionality and display |✅    |

---

### Posts Create, Edit and Delete as expected

|Test  |Expected Outcome   |Test Outcome   |
|----|----|----|
|As 'TestUser99', click 'Submit' on post creation form with 1 or more empty fields|Message popup asking 'Please fill out this field'|✅    |
|As 'TestUser99', enter 'Test Post' in 'Post Title' field, select 'Asia' from the dropdown, enter 'A test post about asia' in the 'Tell us your story' field and click 'Submit'|The full page post is displayed with matching content with and 'Edit Post' and 'Delete Post' buttons|✅    |
|As 'TestUser100', view the post made by TestUser99 in the previosu test|The full page post is displayed with matching content. No buttons for 'Edit Post' or 'Delete Post' are present|✅    |
|As 'TestUser99', clcik 'Edit Post' on the post made by TestUser99 in the previosu test|Form pops up with fields pre-populated by current post details and 'Save changes' button|✅    |
|As 'TestUser99', enter 'EDIT Test Post' in 'Post Title' field, select 'Africa' from the dropdown, enter 'EDIT A test post about asia' in the 'Tell us your story' field and click 'Save changes'|Full post page changes to reflect changes submitted in the form|✅    |
|As 'TestUser99', clcik 'Delete Post' on the post made by TestUser99 in the previosu test|Message popup asking to confirm deletion|✅    |
|As 'TestUser99', clcik 'Confirm Delete' on message popup form previous test|Post and any comments are deleted and navigates to 'My Posts' page|✅    |
|As 'TestUser99', clcik 'Save changes' on message popup from previous edit post test after session has expired|Popup message 'Whoops! Looks like you were logged out. Please log in and try again.' and redirected to login page|✅    |
|As 'TestUser99', clcik 'Confirm Delete' on message popup from previous delete post test after session has expired|Popup message 'Whoops! Looks like you were logged out. Please log in and try again.' and redirected to login page|✅    |

---

### Comments Create, Edit and Delete as expected

|Test  |Expected Outcome   |Test Outcome   |
|----|----|----|
|As 'TestUser99', click 'Submit' on comment creation form with an empty field|Message popup asking 'Please fill out this field'|✅    |
|As 'TestUser99', enter 'Test Comment' in 'Coimment' field and click 'Submit'|The full page post is displayed with the comment below it with 'Edit Comment' and 'Delete COmment' buttons|✅    |
|As 'TestUser100', view the post made by TestUser99 in the previosu test and view comment made by TestUser99 below the post|The full page post is displayed with comment below it. No buttons for 'Edit Comment' or 'Delete Comment' are present|✅    |
|As 'TestUser99', clcik 'Edit Comment' on the comment made by TestUser99 in the previosu test|Form pops up with comment field pre-populated by current comment details and 'Save changes' button|✅    |
|As 'TestUser99', enter 'EDIT Test Comment' in edit comment popup field and click 'Save changes'|Full post page changes to reflect changes to the comment|✅    |
|As 'TestUser99', clcik 'Delete Comment' on the comment made by TestUser99 in the previosu test|Message popup asking to confirm deletion|✅    |
|As 'TestUser99', clcik 'Confirm Delete' on message popup from previous test|Comments is deleted from the full post page|✅    |
|As 'TestUser99', clcik 'Save changes' on message popup from previous edit comment test after session has expired|Popup message 'Whoops! Looks like you were logged out. Please log in and try again.' and redirected to login page|✅    |
|As 'TestUser99', clcik 'Confirm Delete' on message popup from previous delete comment test after session has expired|Popup message 'Whoops! Looks like you were logged out. Please log in and try again.' and redirected to login page|✅    |

---

## **Postman Testing**

Postman was used for extensive testing of server routing throughout development. Important routes and their responses are outlined below.

<details>

<summary>GET /posts</summary>

<br>

Expected Outcome: Return array of all posts

Test Outcome: ✅

Response

```json
[
    {
        "_id": "63dcb429fce9476f6ce7599b",
        "title": "Backpacking across Europe",
        "author": {
            "_id": "63dcb428fce9476f6ce7596e",
            "username": "Chuck Norris"
        },
        "category": "Europe",
        "content": "Chuck Norris was an only child...eventually Chuck Norris is the only man to ever defeat a brick wall in a game of tennis. Chuck Norris invented Kentucky Fried Chicken's famous secret recipe, with eleven herbs and spices. But nobody ever mentions the twelfth ingredient: Fear Chuck Norris has two speeds. Walk, and Kill. Chuck Norris doesn't read books. He stares them down until he gets the information he wants. Chuck Norris does not sleep. He waits. Police label anyone attacking Chuck Norris as a Code 45-11... a suicide Someone once videotaped Chuck Norris getting pissed off. It was called Walker: Texas Chain Saw Massacre. Chuck Norris does not get frostbite. Chuck Norris bites frost. Police label anyone attacking Chuck Norris as a Code 45-11... a suicide.",
        "comments": [],
        "date_posted": "2023-02-03T07:13:45.016Z",
        "__v": 0
    },
    {
        "_id": "63dcb429fce9476f6ce7599c",
        "title": "Looting Europe",
        "author": {
            "_id": "63dcb428fce9476f6ce7596f",
            "username": "Jack Sparrow"
        },
        "category": "Europe",
        "content": "Yar Pirate Ipsum. Reef sails strike colors code of conduct parley sloop yardarm square-rigged mizzen loaded to the gunwalls keel. Bilge rat scuttle gangway heave down piracy nipper pirate mizzen topmast deadlights. Aft case shot lugsail Gold Road scourge of the seven seas mutiny skysail reef bowsprit Admiral of the Black. Man-of-war yardarm plunder Gold Road case shot capstan poop deck grog blossom clap of thunder topsail. Jack Tar coffer weigh anchor lateen sail warp crimp wench square-rigged careen pirate. Ye hearties interloper cable schooner ho avast tackle booty heave down. Prow reef sails Davy Jones' Locker spike red ensign boom scurvy ahoy belay Sea Legs. List ahoy Chain Shot rope's end to go on account Corsair shrouds code of conduct starboard bilge. Jack Ketch crow's nest topmast run a rig stern Pieces of Eight Jolly Roger Sail ho cog grog blossom.",
        "comments": [],
        "date_posted": "2023-02-03T07:13:45.016Z",
        "__v": 0
    },
    ...
]
```

</details>

<details>

<summary>GET /posts/:id</summary>

Param: `63dcb429fce9476f6ce7599f`

Expected Outcome: Return 1 post matching id: `63dcb429fce9476f6ce7599f`

Test Outcome: ✅

Response:

```json
{
    "_id": "63dcb429fce9476f6ce7599f",
    "title": "A week in Melbourne during the Aus Open",
    "author": {
        "_id": "63dcb428fce9476f6ce7596c",
        "username": "Callum"
    },
    "category": "Australia",
    "content": "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum",
    "comments": [],
    "date_posted": "2023-02-03T07:13:45.016Z",
    "__v": 0
}
```

</details>

<details>

<summary>GET /posts/category/:category</summary>

Param: `Asia`

Expected Outcome: Return all posts from 'Asia' category

Test Outcome: ✅

Response:

```json
[
    {
        "_id": "63dcb429fce9476f6ce7597d",
        "title": "They built the Great Wall of China to keep me out... but it didn't work",
        "author": {
            "_id": "63dcb428fce9476f6ce7596e",
            "username": "Chuck Norris"
        },
        "category": "Asia",
        "content": "Chuck Norris was an only child...eventually Chuck Norris is the only man to ever defeat a brick wall in a game of tennis. Chuck Norris invented Kentucky Fried Chicken's famous secret recipe, with eleven herbs and spices. But nobody ever mentions the twelfth ingredient: Fear Chuck Norris has two speeds. Walk, and Kill. Chuck Norris doesn't read books. He stares them down until he gets the information he wants. Chuck Norris does not sleep. He waits. Police label anyone attacking Chuck Norris as a Code 45-11... a suicide Someone once videotaped Chuck Norris getting pissed off. It was called Walker: Texas Chain Saw Massacre. Chuck Norris does not get frostbite. Chuck Norris bites frost. Police label anyone attacking Chuck Norris as a Code 45-11... a suicide.",
        "comments": [],
        "date_posted": "2023-02-03T07:13:45.013Z",
        "__v": 0
    },
    {
        "_id": "63dcb429fce9476f6ce7597e",
        "title": "Shipwrecked in Beijing",
        "author": {
            "_id": "63dcb428fce9476f6ce7596f",
            "username": "Jack Sparrow"
        },
        "category": "Asia",
        "content": "Yar Pirate Ipsum. Reef sails strike colors code of conduct parley sloop yardarm square-rigged mizzen loaded to the gunwalls keel. Bilge rat scuttle gangway heave down piracy nipper pirate mizzen topmast deadlights. Aft case shot lugsail Gold Road scourge of the seven seas mutiny skysail reef bowsprit Admiral of the Black. Man-of-war yardarm plunder Gold Road case shot capstan poop deck grog blossom clap of thunder topsail. Jack Tar coffer weigh anchor lateen sail warp crimp wench square-rigged careen pirate. Ye hearties interloper cable schooner ho avast tackle booty heave down. Prow reef sails Davy Jones' Locker spike red ensign boom scurvy ahoy belay Sea Legs. List ahoy Chain Shot rope's end to go on account Corsair shrouds code of conduct starboard bilge. Jack Ketch crow's nest topmast run a rig stern Pieces of Eight Jolly Roger Sail ho cog grog blossom.",
        "comments": [],
        "date_posted": "2023-02-03T07:13:45.013Z",
        "__v": 0
    },
    ...
]
```

</details>

<details>

<summary>POST /auth/register</summary>

**Test 1**

Expected Outcome: Register a user in the DB and return their id and username

Test Outcome: ✅

Request:

```json
{
    "username": "PostmanTest",
    "password": "Postman123!"
}
```

Response:

```json
{
    "id": "63dd7dd514ca26d2655eae23",
    "username": "PostmanTest"
}
```

**Test 2**

Expected Outcome: Fail registration by providing an invalid password (no number, no symbol)

Test Outcome: ✅

Request:

```json
{
    "username": "PostmanTest2",
    "password": "Postman"
}
```

Response:

```json
{
    "errors": [
        {
            "value": "Postman",
            "msg": "Password must be atleast 8 characters; 1 uppercase, 1 lowercase, 1 number and 1 symbol",
            "param": "password",
            "location": "body"
        }
    ]
}
```

</details>

<details>

<summary>POST /auth/login</summary>

**Test 1**

Expected Outcome: Login a user by returning their id, username and jwt token

Test Outcome: ✅

Request:

```json
{
    "username": "PostmanTest",
    "password": "Postman123!"
}
```

Response:

```json
{
    "id": "63dd7dd514ca26d2655eae23",
    "username": "PostmanTest",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZGQ3ZGQ1MTRjYTI2ZDI2NTVlYWUyMyIsImlhdCI6MTY3NTQ2MDE2MCwiZXhwIjoxNjc1NDYwMjgwfQ.Pu6XE7k-S3jfcL_JkgLTGVwKMNK2HXqnMJ2lYuWA3gI"
}
```

**Test 2**

Expected Outcome: Fail login by providing an incorrect password

Test Outcome: ✅

Request:

```json
{
    "username": "PostmanTest",
    "password": "WrongPassword"
}
```

Response:

```json
{
    "error": "Incorrect username or password"
}
```

</details>

<details>

<summary>POST /posts/new</summary>

**Test 1**

Expected Outcome: Enter a new Post into the DB as a logged in user

Test Outcome: ✅

Request:

```json
{
    "title": "Postman testing",
    "category": "North America",
    "content": "A post about using Postman to test stuff."
}
```

Response:

```json
{
    "title": "Postman testing",
    "author": {
        "_id": "63dd7dd514ca26d2655eae23",
        "username": "PostmanTest"
    },
    "category": "North America",
    "content": "A post about using Postman to test stuff.",
    "comments": [],
    "_id": "63dd805d14ca26d2655eae29",
    "date_posted": "2023-02-03T21:45:01.199Z",
    "__v": 0
}
```

**Test 2**

Expected Outcome: Error message when passing invalid category for a new Post

Test Outcome: ✅

Request:

```json
{
    "title": "Postman testing",
    "category": "America",
    "content": "A post about using Postman to test stuff."
}
```

Response:

```json
{
    "errors": [
        {
            "value": "America",
            "msg": "Invalid category",
            "param": "category",
            "location": "body"
        }
    ]
}
```

**Test 3**

Expected Outcome: Error message when token not provided in authorization header

Test Outcome: ✅

Request:

```json
{
    "title": "Postman testing",
    "category": "North America",
    "content": "A post about using Postman to test stuff."
}
```

Response:

```json
{
    "error": "Access denied."
}
```

</details>

<details>

<summary>PUT /posts/:id</summary>

**Test 1**

Params: `63dd805d14ca26d2655eae29`

Expected Outcome: Edit post title, category and content

Test Outcome: ✅

Request:

```json
{
    "title": "Postman testing - EDIT",
    "category": "Africa",
    "content": "A post about using Postman to test stuff - EDIT"
}
```

Response:

```json
{
    "_id": "63dd805d14ca26d2655eae29",
    "title": "Postman testing - EDIT",
    "author": {
        "_id": "63dd7dd514ca26d2655eae23",
        "username": "PostmanTest"
    },
    "category": "Africa",
    "content": "A post about using Postman to test stuff - EDIT",
    "comments": [],
    "date_posted": "2023-02-03T21:45:01.199Z",
    "__v": 0
}
```

**Test 2**

Params: `63dd805d14ca26d2655eae29`

Expected Outcome: Error message when not providing title in request body

Test Outcome: ✅

Request:

```json
{
    "category": "Africa",
    "content": "A post about using Postman to test stuff - EDIT"
}
```

Response:

```json
{
    "errors": [
        {
            "msg": "Title is required",
            "param": "title",
            "location": "body"
        }
    ]
}
```

**Test 3**

Params: `63dd805d14ca26d2655eae29`

Expected Outcome: Error message when token in authorization header member id does not match author id

Test Outcome: ✅

Request:

```json
{
    "title": "Postman testing - EDIT",
    "category": "Africa",
    "content": "A post about using Postman to test stuff - EDIT"
}
```

Response:

```json
{
    "error": "Access Denied. You are not the owner of this post"
}
```

</details>

<details>

<summary>DELETE /posts/:id</summary>

**Test 1**

Params: `63dd805d14ca26d2655eae29`

Expected Outcome: Delete post matching id passed as param

Test Outcome: ✅

Response: Status Code 204 No Content

**Test 2**

Params: `63dd805d14ca26d2655eae29`

Expected Outcome: Error message when token in authorization header member id does not match author id

Test Outcome: ✅

Response:

```json
{
    "error": "Access Denied. You are not the owner of this post"
}
```

</details>

<details>

<summary>POST /comments/new</summary>

**Test 1**

Expected Outcome: Comment is added to post in DB with author as logged in user

Test Outcome: ✅

Request:

```json
{
    "post": "63dd870614ca26d2655eae43",
    "content": "A comment for Postman testing"
}
```

Response:

```json
{
    "post": "63dd870614ca26d2655eae43",
    "author": {
        "_id": "63dd7dd514ca26d2655eae23",
        "username": "PostmanTest"
    },
    "content": "A comment for Postman testing",
    "_id": "63dd872714ca26d2655eae49",
    "date_posted": "2023-02-03T22:13:59.329Z",
    "__v": 0
}
```

**Test 2**

Expected Outcome: Error message when no post id is given in request body

Test Outcome: ✅

Request:

```json
{
    "content": "A comment for Postman testing"
}
```

Response:

```json
{
    "errors": [
        {
            "msg": "Post id required",
            "param": "post",
            "location": "body"
        },
        {
            "msg": "Invalid Mongo id",
            "param": "post",
            "location": "body"
        }
    ]
}
```

**Test 3**

Expected Outcome: Error message when trying to create a comment with expired JWT

Test Outcome: ✅

Request:

```json
{
    "post": "63dd870614ca26d2655eae43",
    "content": "A comment for Postman testing"
}
```

Response:

```json
{
    "error": "jwt expired"
}
```

</details>

<details>

<summary>PUT /comments/:id</summary>

**Test 1**

Params: `63dd872714ca26d2655eae49`

Expected Outcome: Edit a comment content

Test Outcome: ✅

Request:

```json
{
    "content": "EDIT - A comment for Postman testing"
}
```

Response:

```json
{
    "_id": "63dd872714ca26d2655eae49",
    "post": "63dd870614ca26d2655eae43",
    "author": {
        "_id": "63dd7dd514ca26d2655eae23",
        "username": "PostmanTest"
    },
    "content": "EDIT - A comment for Postman testing",
    "date_posted": "2023-02-03T22:13:59.329Z",
    "__v": 0
}
```

**Test 2**

Params: `63dd872714ca26d2655eae49`

Expected Outcome: Error message when sending no content in request body

Test Outcome: ✅

Request:

```json
{

}
```

Response:

```json
{
    "errors": [
        {
            "msg": "Content required",
            "param": "content",
            "location": "body"
        },
    ]
}
```

**Test 3**

Params: `63dd872714ca26d2655eae49`

Expected Outcome: Error message when trying to edit a comment that you are not the owner of

Test Outcome: ✅

Request:

```json
{
    "content": "EDIT - A comment for Postman testing"
}
```

Response:

```json
{
    "error": "Access Denied. You are not the owner of this comment"
}
```

</details>

<details>

<summary>DELETE /comments/:id</summary>

**Test 1**

Params: `63dd872714ca26d2655eae49`

Expected Outcome: Edit a comment content

Test Outcome: ✅

Response: Status Code 204 No Content

**Test 2**

Params: `63dd872714ca26d2655eae49`

Expected Outcome: Error message when trying to delete a comment that you are not the owner of

Test Outcome: ✅

Response:

```json
{
    "error": "Access Denied. You are not the owner of this comment"
}
```

</details>
