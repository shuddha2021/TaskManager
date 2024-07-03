# TaskMaster Pro

A professional task management application to streamline your productivity. Manage tasks efficiently with features like task creation, editing, and completion tracking.

## Features
- **Task Creation**: Easily create new tasks with titles, descriptions, due dates, and completion status.
- **Task Editing**: Edit task details directly from the homepage for quick updates.
- **Task Deletion**: Remove tasks that are no longer needed.
- **Task Details**: View detailed information of each task.
- **Completion Tracking**: Mark tasks as completed to keep track of your progress.

## Technologies Used
- **ASP.NET Core**: Backend framework for building the application.
- **Entity Framework Core**: ORM for database interactions.
- **SQLite**: Database for storing task data.
- **Razor Pages**: Dynamic view generation.
- **Bootstrap**: Styling and responsive design.
- **JavaScript**: Client-side interactivity.

## Screenshot

![Task List](https://via.placeholder.com/1117x500)

## Getting Started

### Prerequisites
- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [SQLite](https://www.sqlite.org/download.html)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/taskmaster-pro.git
2. Navigate to the project directory:
   cd taskmaster-pro
3. Restore dependencies:
   dotnet restore
4. Update the database:
   dotnet ef database update
5. Run the application:
   dotnet run

### Project Structure
- Controllers/: Contains the MVC controllers.
- Models/: Contains the data models.
- Views/: Contains the Razor view templates.
- Data/: Contains the database context.
- wwwroot/: Contains static files (CSS, JavaScript, etc.).

### Usage
- Access the application at https://localhost:5001.
- Create a new task by filling out the task form on the homepage.
- Edit a task's details directly from the homepage.
- View task details or delete a task as needed.

### Why This Project Is Useful
This project serves as a practical example of building a full-stack web application with ASP.NET Core. It demonstrates effective use of MVC architecture, entity framework for data management, and bootstrap for responsive design.

### Contributing
Contributions to this project are welcome. Please fork the repository and create a pull request with your changes.

### License
This project is licensed under the MIT License.
