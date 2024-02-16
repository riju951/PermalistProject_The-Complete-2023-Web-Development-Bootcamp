# PermaList: Permanent To-Do List Application

## Overview

PermaList is a to-do list application designed to provide a persistent, user-friendly interface for managing tasks. Developed as part of the 2024 Web Development Bootcamp by Angela Yu, it leverages a robust backend built with Express and Node.js, dynamic templating with EJS, and stylized with responsive HTML and CSS. PermaList allows users to add, view, edit, and delete tasks in a permanent list, ensuring that your tasks are saved and retrievable anytime, anywhere.

![1](https://github.com/riju951/PermalistProject_The-Complete-2023-Web-Development-Bootcamp/assets/82694741/e993880c-cec2-47e9-bae8-447dcad5b6ea)

![2](https://github.com/riju951/PermalistProject_The-Complete-2023-Web-Development-Bootcamp/assets/82694741/1aa538dc-c99d-4367-b0ff-3d8884a41b67)

![3](https://github.com/riju951/PermalistProject_The-Complete-2023-Web-Development-Bootcamp/assets/82694741/c9367074-ff5d-4d03-8b50-49ac78b1a2b8)

## Features

- **CRUD Operations**: Create new tasks, read/display them, update existing tasks, and delete tasks as needed.
- **Persistence**: Tasks are stored in a database, ensuring they are not lost between sessions.
- **Responsive Design**: A mobile-friendly interface that adapts seamlessly across devices.
- **Easy to Use**: A minimalist design focusing on usability and efficiency.

## Tech Stack

- **Frontend**: HTML, CSS, EJS
- **Backend**: Node.js, Express
- **Database**: MongoDB (suggested for integration, can be replaced as per requirement)
- **Deployment**: This project is suitable for deployment on platforms like Heroku, Vercel, or AWS.

## Getting Started

### Prerequisites

- Node.js installed on your machine
- Basic understanding of JavaScript and web development

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/permalist.git
cd permalist
```

2. **Install dependencies**

```bash
npm install
```

3. **Configure your database**

- The project is configured to use MongoDB. Ensure you have MongoDB set up either locally or through a cloud provider.
- Create a `.env` file in the root directory and specify your database connection string:

```env
DATABASE_URL=mongodb://localhost:27017/permalist
```

4. **Start the application**

```bash
npm start
```

The server will start, typically on port 3000. Navigate to `http://localhost:3000` to view the application.

## Usage

- **Adding a Task**: Click on the 'Add New Task' button and fill in the task details.
- **Viewing Tasks**: All tasks are displayed on the homepage.
- **Editing a Task**: Click the 'Edit' button next to any task to modify its content.
- **Deleting a Task**: Click the 'Delete' button to remove a task from the list.

## Contributing

We welcome contributions! Please feel free to fork the repository and submit pull requests.
