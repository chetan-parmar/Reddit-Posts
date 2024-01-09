# Reddit Post Django Project

This Django project, "Reddit Post," provides functionality for user registration, login, and the ability to create posts, comments, and replies.

## Features

1. **User Authentication:**
   - Users can register and log in using a simple JWT token-based authentication system.

2. **Models:**
   - The project includes the following models:
     - `Post`: Represents a post with a title, text, image, likes, user, and creation timestamp.
     - `Comment`: Represents a comment with text, user, associated post, and creation timestamp.
     - `Reply`: Represents a reply with text, user, associated comment, and creation timestamp.

3. **Post Functionality:**
   - Users can create posts with a title, text, and an optional image.
   - Posts have a list of likes from other users.
   - Each post is associated with the user who created it.

4. **Commenting System:**
   - Users can give comments on posts.
   - Each comment is associated with the user who posted it and the post it belongs to.
   - Comments have creation timestamps.

5. **Reply System:**
   - Users can provide replies to comments.
   - Each reply is associated with the user who posted it, the parent comment, and has a creation timestamp.

