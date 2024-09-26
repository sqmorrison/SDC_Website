# SDC_Website
 A website for the Software Development Club for Tennessee Technological University
 The following document will outline the features of each page and include general ideas about the website

Homepage 
 - Conditionals based on if logged in or not (ex. can only see the projects part of the navbar if you're logged in)
 - About Us section giving a brief description of who we are
 - Top exciting projects : title, description, lead developers
 - Display announcements
 - Contact Us at the bottom

Kanban Page (project management):
 - Columns for in-progress, completed, open, open and in progress
 - Each project should have tags for what languages are needed
 - Users should have the ability to apply for leadership on the project, and also apply for membership on the project

Documentation Page:
 - Should have a search bar for files based on keywords
 - Place to store documentation for existing projects
 - Have a place for an FAQ
 - Leadership Section, New Member Section

Admin Panel
 - CRUD operations for Users, projects, Users related to projects
 - CRUD operations for club roster (roster should include last meeting attended and when they joined)

SMS Messages
 When a project is created with tags similar to what the user's preference is, a text message will be sent with project details.
 This will give users the opportunity to quickly react to projects and apply for them before a closing deadline when the project will move forward.
 Will will use the API Twilio for this feature.

General Information:
 - Users can only log in with their Tennessee Tech emails, to collect user data for personalization and disallow potential bad actors from signing up
 - Will Implement a dark mode