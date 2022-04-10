# Intermediate Node.js

Check out the issues of this repo for the course materials.

Next steps to improve security:

Encrypt your user passwords with a library like "bcrypt" before saving them.

Add a nested collection (activities, pets, blog posts, etc... ) to your User model using the "populate" method.

Use a library like JSON web token to authenticate your users in a login route.

Use middleware for your mongoose model or express routes to check if there is a valid token that matches the user's id before saving data.