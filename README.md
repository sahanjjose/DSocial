# DSocial

## Overview

This Django project, named "DSocial," includes a single app called "network." It is designed to implement a social network allowing users to make posts, follow other users, and like posts. The application uses Python for the backend, JavaScript for dynamic interactions, and HTML/CSS for the frontend.

## Features

### New Post

- Users can create new text-based posts.
- A text area and a submit button are provided for users to input and submit their posts.

### All Posts

- The "All Posts" link displays all posts from all users.
- Posts are shown in reverse chronological order.
- Each post includes the username of the poster, post content, post timestamp, and the number of likes.

### Profile Page

- Clicking on a username leads to the user's profile page.
- The profile page displays the number of followers and following for the user.
- All posts by the user are displayed in reverse chronological order.
- For other users, a "Follow" or "Unfollow" button allows toggling whether the current user is following their posts.

### Following

- The "Following" link displays posts from users that the current user follows.
- Similar to the "All Posts" page but limited to followed users.

### Pagination

- Each page displays a maximum of 10 posts.
- "Next" and "Previous" buttons allow navigation between pages.

### Edit Post

- Users can edit their own posts by clicking an "Edit" button.
- Content is replaced with a textarea for editing.
- Changes can be saved without reloading the entire page.

### Like and Unlike

- Users can like or unlike a post by clicking a button.
- Asynchronously updates the like count on the server and the post's like count on the page without a full page reload.

## Setup

1. Run `python manage.py migrate` to apply migrations.
2. Run `python manage.py runserver` to start the Django web server.
3. Visit the website in your browser.

