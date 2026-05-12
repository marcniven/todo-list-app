# To-Do List Web Application

A full-stack To-Do List web application to help users manage tasks and deadlines in an organized and simple way.

## Core Features
- Create, edit, and delete tasks
- Organize tasks into multiple lists (e.g., one per course)
- View tasks by due date
- Highlight task priority

## Technologies
- HTML, CSS, JavaScript
- Node.js
- MySQL

## Setup

1. Clone the repository
  ```{bash}
  git clone https://github.com/marcniven/todo-list-app.git
  cd todo-list-app
  ```

2. Install dependencies
  ```{bash}
  cd todo-list-app
  npm install
  ```

3. Open MySQL Workbench

4. In MySQL Workbench, import and run the `create_db.sql` script located in the `database` folder to create the database and tables:
- todo_list_db
- users
- lists
- tasks

5. Create a `.env` file in the root directory and paste the following:
  ```{bash}
  DB_HOST=localhost
  DB_USER=root
  DB_PASSWORD=YOUR_PASSWORD_HERE
  ```
  Replace `YOUR_PASSWORD_HERE` with your MySQL password.

  If you have a different MySQL Host and Username, replace `localhost` and `root`.

6. Run the server
  ```{bash}
  npm start
  ```

  Open your browser and go to:  http://localhost:3000

  ## Team Members
- Suvethan Yogathasan
- Maathusan Raveendran
- Marc Niven Kumar
