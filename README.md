# Books & Movies Wishlist

A simple Django app deployed with Kubernetes using Google Container Engine.

This app helps you to keep track of books and movies that you plan to check out. It displays a list of books and movies that people recommended you to read / watch. Once an item no longer belongs to the wishlist, it can be simply removed (an AJAX request is sent to the Django server in the background).

# Specific Functionality

- Login with Google is provided by Auth0[https://auth0.com/].
- AJAX requests are sent to the Django server from the JavaScript Client.
- Deployed with Docker and Kubernetes.

# Demo

See the app deployed on Google Cloud Platform: http://35.188.115.96 

Log in with your Google account to see the dashboard.

# Run

## Docker

Run the image from my Docker Hub: ```jastr945/kubebooks:v1.0```

# Future plans:

- Use some public API for auto-suggesting books and movies (eg. if users don't remember full titles);
