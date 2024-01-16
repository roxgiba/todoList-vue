# Vue3 Todo List

A simple ToDo list application built with Vue 3. This application allows users to create, organize, and manage their todos. Each todo can be associated with a category, and the list is stored locally in the browser's localStorage.


## Getting Started

1. Clone the repository:
```
git clone <repository-url>
cd <repository-folder>
```
2. Install dependencies:
```
npm install
```
3. Run the application:
```
npm run serve
```
The application should now be running on http://localhost:8080/ or another available port. Open your browser and navigate to the specified URL.


## Usage

1. **Hello Section**
- Start by entering your name in the input field to personalize the greeting.
2. **Create a Todo**
- Enter a task in the "What's on your todo list?" input field.
- Choose a category by selecting either "Business" or "Personal" using the radio buttons.
- Click the "Add todo" button to add the todo to the list.
3. **Todo List**
- The todos are displayed in descending order of their creation time.
- Each todo item includes a checkbox to mark the task as done, a category indicator, and the task content.
- Edit the task content directly by typing in the corresponding input field.
- Click the checkbox to mark a todo as done.
- Click the "Delete" button to remove a todo from the list.
  

## Local Storage

The application uses localStorage to persist your name and todo list even if you close or refresh the page.


## Deployment
This application is deployed with Netlify. The live version can be accessed at (https://vue-todolist-roxgiba.netlify.app/)https://vue-todolist-roxgiba.netlify.app/.
