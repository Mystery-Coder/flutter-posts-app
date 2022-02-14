# Main Goal
To make a Flutter app where users can post text to be viewed by others.
The users can view all their old posts.

## Features
- Special type of user authentication where the passwords are not stored.

## User Authentication
For authentication, when a new user is registered a random string of 12-14 characters is encrypted with their password.
The encrypted string and original string is stored for that user
To verify the user, the original string is encrypted with the password entered and tested against the
encrypted string stored. The user is authenticated if they match.\
\
**Illustration For User Authorization:**\
![User Auth](screenshot.png)
