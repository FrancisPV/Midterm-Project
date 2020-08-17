# Teacherest - like Pinterest, but for educators

Teacherest is a multi-page app with single page app features. From the main page, a user can search through all resources by category or keyword to see their search results loaded on the same page. 

Click on a resource to view it on a new page. Users can favourite the post and add it to their saved resources, or join the conversation and comment.

Users can view their saved resources on the My Resources page, and update their profile on the My Profile page.

Created with the help of Léo Mckenna and Alyssa Beaton Tanguay.


## Teacherest screenshots

![teacherest_view_resource.png](https://github.com/mckennaleo/Midterm-Project/blob/master/docs/teacherest_view_resource.png?raw=true)
![teacherest_register.png](https://github.com/mckennaleo/Midterm-Project/blob/master/docs/teacherest_register.png?raw=true)
![teacherest_my_resources.png](https://github.com/mckennaleo/Midterm-Project/blob/master/docs/teacherest_my_resources.png?raw=true)
![teacherest_main_page_menu.png](https://github.com/mckennaleo/Midterm-Project/blob/master/docs/teacherest_main_page_menu.png?raw=true)
![teacherest_favourite_post.png](https://github.com/mckennaleo/Midterm-Project/blob/master/docs/teacherest_favourite_post.png?raw=true)
![teacherest_edit_profile.png](https://github.com/mckennaleo/Midterm-Project/blob/master/docs/teacherest_edit_profile.png?raw=true)

## Dependencies

- Chalk 2.x or above
- Cookie-session 1.4 or above
- Body-parser 1.19 or above
- Bcrypt-js 2.x or above
- EJS 2.x or above
- Moment 2.x or above
- Morgan 1.9 or above
- Node 10.x or above
- NPM 5.x or above
- PG 6.x
- PG-native 3.x or above

## Getting Started

Install all dependencies using the npm install command.

## Notes about database privileges

In db/schema/00_reset.sql we've included a command to grant labber superuser to effectively access and post to the database.
