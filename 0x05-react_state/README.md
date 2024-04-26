## Task 0: Adding a local state for notifications

### Description
In this task, we add local state management to handle the display of notifications in our React application. We modify the `App` component and the `Notifications` component to implement the state management.

### Files
- `task_0/dashboard/src/App/App.js`
- `task_0/dashboard/src/App/App.test.js`
- `task_0/dashboard/src/Notifications/Notifications.js`
- `task_0/dashboard/src/Notifications/Notifications.test.js`

### Steps
1. Create a local state in the `App` component to manage the display of notifications.
2. Modify the `Notifications` component to interact with the local state.
3. Implement tests to ensure the functionality of displaying and hiding notifications.

## Task 1: Controlled components and state callback

### Description
This task involves creating controlled components for a login form and managing the form's state callbacks. We modify the `Login` component to handle form submission and input changes effectively.

### Files
- `task_1/dashboard/src/Login/Login.js`
- `task_1/dashboard/src/Login/Login.test.js`

### Steps
1. Create a local state for the login form in the `Login` component.
2. Implement controlled components for email and password inputs.
3. Manage state callbacks for form submission and input changes.
4. Add tests to verify the functionality of the login form.

## Task 2: Context

### Description
In this task, we introduce context to manage user authentication across components. We create a React context, modify the `App` component to handle login and logout functions, and utilize context in other components.

### Files
- `task_2/dashboard/src/App/AppContext.js`
- `task_2/dashboard/src/App/App.js`
- `task_2/dashboard/src/Login/Login.js`
- `task_2/dashboard/src/Header/Header.js`
- `task_2/dashboard/src/Header/Header.test.js`
- `task_2/dashboard/src/App/App.test.js`

### Steps
1. Create a React context for managing user authentication.
2. Modify the `App` component to handle login and logout functions.
3. Refactor components to use context for user authentication.
4. Implement tests to verify the functionality of authentication.

## Task 3: Context consumer & advanced state

### Description
This task focuses on utilizing context consumers and managing advanced state within components. We modify the `Footer` component to subscribe to context changes and enhance state management in the `App` and `Notifications` components.

### Files
- `task_3/dashboard/src/Footer/Footer.js`
- `task_3/dashboard/src/Footer/Footer.test.js`
- `task_3/dashboard/src/App/App.js`
- `task_3/dashboard/src/App/App.test.js`
- `task_3/dashboard/src/Notifications/Notifications.js`
- `task_3/dashboard/src/Notifications/Notifications.test.js`

### Steps
1. Modify the `Footer` component to subscribe to context changes and display additional content based on user authentication.
2. Enhance state management in the `App` component by adding notifications functionality.
3. Refactor the `Notifications` component to optimize performance and utilize advanced state.
4. Implement tests to verify the functionality of the components.

## Task 4: Introduction to React Hook

### Description
In this task, we explore React Hooks by modifying the `CourseListRow` component to incorporate a checkbox functionality using hooks. We introduce a new style for checked rows and implement the checkbox behavior without converting the component to a class.

### Files
- `task_4/dashboard/src/CourseList/CourseListRow.js`

### Steps
1. Implement React Hooks to add checkbox functionality to the `CourseListRow` component.
2. Add a new style for checked rows.
3. Ensure correct behavior of checkboxes for each row.
