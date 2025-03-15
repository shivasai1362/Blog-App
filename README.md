# Blog App

This is a blog application built using Vite, React, and Tailwind CSS. The app allows users to read and comment on articles, while authors can create, edit, and soft-delete their own posts. Admins have the ability to manage users and ensure the platform remains appropriate for all.

## Features

### User Roles:

- **User:** Can read articles and comment.
- **Author:** Can post, read, comment, and soft-delete their own posts.
- **Admin:** Can read all articles, comment, and disable inappropriate users.

### Core Functionalities:

- User authentication and role-based access control.
- Authors can create and manage their own posts.
- Soft-delete functionality for authors (posts remain hidden but not permanently deleted).
- Users can comment on articles.
- Admins can disable inappropriate users.

## Technologies Used

- **Frontend:** Vite, React, Tailwind CSS
- **State Management:** React Context API 
- **Backend:** MongoDB, Clerk for authentication
- **Database:** MongoDB

## Installation & Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/shivasai1362/Blog-App.git
   cd blog-app
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the development server:

   ```sh
   npm run dev
   ```

## Contribution

Feel free to fork this repository and submit pull requests to improve the project.


