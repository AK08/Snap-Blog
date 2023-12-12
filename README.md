# Blogs

## Objective

SnapBlog is a Web-based blogging platform where users can create, publish, and manage their blog posts. The platform allows users to register, log in, create blog posts, view and edit their posts, and display the published posts to the public.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Features

1. **User Registration and Authentication**
   - Users can register with the platform using their email and password.
   - Secure authentication mechanism for registered users.

2. **Create and Manage Blog Posts**
   - Users can create new blog posts with a title, content (max 300 words), and optional tags.
   - View and edit their own posts.
   - Feature to delete posts.

3. **Public Blog Display**
   - Visitors can view all published blog posts on the platform.
   - Search functionality based on tags or keywords.

4. **User Interface and Design**
   - User-friendly and responsive interface.
   - Visually appealing design adhering to the requirements.

5. **Security**
   - Implementation of necessary security measures to protect user data.


## Tech Stack

- Frontend: [React.js](https://reactjs.org/) with [Material-UI](https://material-ui.com/) and [Bootstrap](https://getbootstrap.com/)
- Backend: [Node.js](https://nodejs.org/) with [Express](https://expressjs.com/)
- Database: [MySQL](https://www.mysql.com/)
- Styling: [Material-UI](https://material-ui.com/) and [Bootstrap](https://getbootstrap.com/)
- Hosting: [000WebHost](https://in.000webhost.com)

## Getting Started

1. Clone the repository:
- Make sure to have installed node and npm
   ```bash
   git clone https://github.com/AK08/blogs.git
   cd blogs

3. Install Dependencies
   ```bash
   #Instal Client
   cd client
   npm install

   #Install Server
   cd ../server
   npm install

4. Add in .env for client
   ```bash
   VITE_SERVER=http://localhost:3000

5. Add in .env for server
   ```bash
   DATABASE_HOST=[Your Host]
   DATABASE_USER=[Your MySQL Username]
   DATABASE_PASS=[Your MYSQL Pass]
   DATABASE_NAME=blogs  #databasename

6. Create a database
   ```bash
   CREATE Database blogs

7. Run client and server
- client
   ```bash
   cd client
   npm run dev

- server
   ```bash
   cd ../server
   npm run dev

## Usage
- Copy & paste the below url
```bash
   http://localhost:5173/
   
"# Snap-Blog" 
"# Snap-Blog" 
"# Snap-Blog" 
"# Snap-Blog" 
"# Snap-Blog" 
