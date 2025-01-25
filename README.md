# Advanced To-Do Application with React

This is an advanced to-do application built with React, Redux, and API integration. It includes user authentication simulation and responsive design.

## Features
- Add, view, and delete tasks.
- Task prioritization (High, Medium, Low).
- Fetch tasks from an external API (sample placeholder data).
- User authentication simulation (login/logout).
- Responsive design for mobile, tablet, and desktop.
- State management using Redux and Redux Thunk.

## Technologies Used
- React
- Redux
- Redux Thunk
- Axios
- CSS (Flexbox, Grid)

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repository-url.git
   
The application will open at http://localhost:3000.

**Folder Structure**

advanced-todo/
├── src/
│   ├── components/
│   │   ├── TaskInput.js
│   │   ├── TaskList.js
│   ├── redux/
│   │   ├── actions/
│   │   │   ├── taskActions.js
│   │   │   ├── authActions.js
│   │   ├── reducers/
│   │   │   ├── taskReducer.js
│   │   │   ├── authReducer.js
│   │   ├── store.js
│   ├── App.js
│   ├── index.js
│   ├── styles.css

Build the app for production:
npm run build
