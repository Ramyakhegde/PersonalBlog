# PersonalBlog — Responsive Blog Website

A PHP-based responsive blog website with dynamic blog content, category navigation, search functionality, and an administrative interface for managing blog content.

## 📌 Project Overview

PersonalBlog provides a platform for displaying and organizing blog articles. It uses PHP to retrieve content dynamically from a MySQL-compatible database and presents it through a structured website interface.

The project also includes an administration system and database scripts to support blog content management.

## ✨ Features

- **Dynamic Homepage:** Displays blog posts in a grid layout.
- **Blog Categories:** Organizes articles by category.
- **Individual Blog Posts:** Provides separate pages for viewing articles.
- **Search Page:** Includes a dedicated page for searching blog content.
- **Featured Content:** Displays banner posts, older posts, and editor-selected articles.
- **Social Media Links:** Supports links to social media platforms.
- **Content Management:** Includes administrative files for managing blog content.
- **Website Information Pages:** Includes About and Contact pages.
- **Responsive Layout:** Uses Bootstrap and CSS styling for the website interface.

## 🛠️ Technologies Used

- **PHP** — Server-side development and dynamic content rendering.
- **MySQL/MariaDB** — Database for storing blog content and related information.
- **HTML5** — Website structure.
- **CSS3** — Styling and layout.
- **Bootstrap** — Responsive layout and interface components.
- **JavaScript and jQuery** — Front-end interactions and interface functionality.

## 📂 Project Structure

```text
PersonalBlog/
└── resblog/
    ├── index.php
    ├── about.php
    ├── banner.php
    ├── category.php
    ├── contact.php
    ├── counter.php
    ├── footer.php
    ├── header.php
    ├── search.php
    ├── single.php
    ├── adminstats/
    ├── blogadmin/
    ├── css/
    ├── js/
    ├── libs/
    │   └── fetch_data.php
    ├── database/
    └── databasefile/
        └── blog_admin_db.sql
```

*This is a simplified representation of the project structure.*

## ⚙️ Installation and Setup

### Prerequisites

Install the following software:

- XAMPP or another local PHP development environment.
- PHP.
- MySQL or MariaDB.
- A web browser.

### Step 1: Download the Project

Clone the repository:

```bash
git clone https://github.com/Ramyakhegde/PersonalBlog.git
```

Alternatively, download the repository as a ZIP file and extract it.

### Step 2: Configure the Local Server

1. Copy the `resblog` folder into your XAMPP `htdocs` directory.
2. Start Apache and MySQL from the XAMPP Control Panel.

### Step 3: Create the Database

1. Open phpMyAdmin in your browser.
2. Create a database named `blog_admin_db`.
3. Select the database.
4. Import the SQL file located at:

   `resblog/databasefile/blog_admin_db.sql`

The SQL file contains the database schema and sample blog records.

### Step 4: Configure Database Connectivity

Check the database connection settings in the project's PHP configuration files. Update the database host, username, password, and database name to match your local environment.

### Step 5: Run the Website

Open the following address in your browser:

```text
http://localhost/resblog/
```

## 🗄️ Database

The project includes a MySQL-compatible SQL dump named `blog_admin_db.sql`.

The database contains a `blogs` table with fields for:

- Blog title
- Tags
- Content
- Image filename
- Publication status
- Publication date
- Author
- Category

Additional tables support other parts of the blog application.

## 🎯 Learning Objectives

This project demonstrates the use of PHP for server-side web development, database integration, dynamic content rendering, and organizing a website into reusable components.

## 👩‍💻 Author

**Ramya Hegde**

GitHub: https://github.com/Ramyakhegde
