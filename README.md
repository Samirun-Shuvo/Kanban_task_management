# Kanban task management web app solution

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Create, read, update, and delete boards and tasks
- Receive form validations when trying to create/edit boards and tasks
- Mark subtasks as complete and move tasks between columns
- Hide/show the board sidebar

Expected Behaviour:

- Boards
  - Clicking different boards in the sidebar will change to the selected board.
  - Clicking "Create New Board" in the sidebar opens the "Add New Board" modal.
  - Clicking in the dropdown menu "Edit Board" opens up the "Edit Board" modal where details can be changed.
  - Columns are added and removed for the Add/Edit Board modals.
  - Deleting a board deletes all columns and tasks and requires confirmation.
- Columns
  - A board needs at least one column before tasks can be added. If no columns exist, the "Add New Task" button in the header is disabled.
  - Clicking "Add New Column" opens the "Edit Board" modal where columns are added.
- Tasks
  - Adding a new task adds it to the bottom of the relevant column.
  - Updating a task's status will move the task to the relevant column.



- The tasks can be dragged and dropped to a new column.



### Built with

- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- Drag and Drop API
- [React](https://reactjs.org/) - JS library
- [Redux](https://redux.js.org/) - State management tool

**How to Run a React Application Locally**
**Prerequisites**
Ensure you have Node.js and npm (Node Package Manager) installed on your machine.
If not, download and install from the Node.js official website.
**Steps to Run the Application**
**Clone the Repository:**
Open your terminal (Command Prompt, PowerShell, or Terminal).
Use the git clone command to clone the repository. Replace [repository link] with the actual URL of the repository:
git clone [repository link]

**Navigate to the Project Directory:**
Change your current directory to the project directory:
cd [project-directory]

**Install Dependencies:**
Ensure you are in the project directory and run the following command to install all necessary dependencies:
npm install

**After installing the dependencies, start the application using:**
npm start

This command will start the development server and automatically open the application in your default web browser. The application is typically accessible at http://localhost:3000.
