# Tech Blog

## Description

Tech Blog is an website structured in the MVC (Model View Controller) style that is a forum for web developers to post blog entries and comment on each others' posts. The site utilizes Handlebars.js for templating lanugage, Sequelize for Object-Relational Mapping (ORM), and the express-session npm package for authentication.

## User Story

As a developer who writes about tech, I want a CMS-style blog site, so that I can publish articles, blog posts, and my thoughts and opinions.

## Acceptance Criteria

Given a CMS-style blog site, the user visits the site for the first time and is presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in. When the user click on the homepage option they are taken to the homepage. When the user clicks on any other links in the navigation they are prompted to either sign up or sign in. When the user chooses to sign up they are then prompted to create a username and password. When the user clicks on the sign-up button their user credentials are saved and they are logged into the site. When the user revisits the site at a later time and chooses to sign in, they are then prompted to enter their username and password. 

When the user is signed into the site they see navigation links for the homepage, the dashboard, and the option to log out. When the user clicks on the homepage option in the navigation, they are then taken to the homepage and presented with existing blog posts that include the post title and the date created. When the user clicks on an existing blog post, they are presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment. The user can enter a comment and click on the submit button while signed in and the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created.

When the user clicks on the dashboard option in the navigation they are taken to the dashboard and presented with any blog posts they have already created and the option to add a new blog post. The user clicks on the button to add a new blog post and are prompted to enter both a title and contents for their post. They click on the button to create a new blog post and the title and contents of their post are saved and they are taken back to an updated dashboard with their new blog post. When the user clicks on one of their existing posts in the dashboard they are able to delete or update their post and taken back to an updated dashboard.

The user clicks on the logout option in the navigation and is then signed out of the site. When the user is idle on the site for more than a set time they are able to view comments but they are prompted to log in again before they can add, update, or delete comments.

## Link to Deployed App in Heroku

https://fast-garden-74894.herokuapp.com/
