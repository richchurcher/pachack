# Stories and tasks

## Migrations and dummy data
 - users: question... what information do we absolutely have to have about users in order to deliver MVP?
 - posts: plain text to begin with. Title?
 - what other entities do we _have_ to have to deliver MVP?
 - threaded posts?
 - add timestamps for everything

## Server: deliver dummy data to front end without db
 - do one route first, commit. Coordinate with rest of team.

## Client: sketch out screens and build with simple routes
 - Show text label only for each screen

## User stories and subtasks

Each story has 'boxes to tick' which could be considered subtasks:

 - [ ] route (permissions check, respond with data or errors)
 - [ ] db (retrieve or store)
 - [ ] async action (send the request, actions for data or error)
 - [ ] reducer (process the data)
 - [ ] container (feed the data to the component)
 - [ ] component (display the data, handle user actions)

Most stories will need all of these steps.

### As a user I would like to sign up

### As a user I would like to sign in
 - JWT must be saved in a cookie or LocalStorage

### As a user I would like to sign out
 - JWT must be cleared (invalidated?)

### As a user I would like to view a feed of posts

### As a user I would like to create a post

### As a user I would like to edit a post

### As a user I would like to delete a post


## Stretch

### As a user I would like to put a video in a post

### As a user I would like to receive a notification when there are new posts

### As a user I would like my feed to scroll infinitely

### As a user I would like to view posts by category

### As a user I would like to sort posts by date

### As a user I would like to view posts from a particular user

### As a user I would like to delete my account (possibly removing all of my data)

### As a moderator I would like to remove offensive posts

### As a moderator I would like to remove users who repeatedly break the rules

### As an administrator I would like to reduce the XSS risk
 - input fields are validated server-side
 - safer if HTTPOnly cookie, but then CSRF protection required

