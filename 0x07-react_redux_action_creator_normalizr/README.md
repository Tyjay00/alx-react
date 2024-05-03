## Task 0: Read data from a JSON

- Import data from `notifications.json`.
- Implement a function to retrieve notifications by user ID.
- Write a test to verify the function's correctness.

## Task 1: Normalize a nested JSON

- Normalize the JSON data using Normalizr.
- Define entities for users, messages, and notifications.
- Ensure the normalized data structure is correct.
- Write tests to validate the normalization process.

## Task 2: Filter a normalized Schema

- Modify the function to retrieve notifications by user ID to use the normalized data.
- Refactor to use only one loop without using `Object.keys`.
- Ensure the function still correctly filters notifications.

## Task 3: Create actions for the course list

- Define action types for selecting and unselecting courses.
- Implement action creators for these actions.
- Write tests to verify the action creators' behavior.

## Task 4: Create actions for the UI

- Define action types for login, logout, displaying, and hiding notification drawer.
- Implement action creators for these actions.
- Test the action creators' behavior.

## Task 5: Create actions for the notification list

- Define action types for marking notifications as read and setting notification filters.
- Implement action creators for these actions.
- Write tests to ensure the action creators generate the correct actions.

## Task 6: Bound the actions

- Bind the action creators to dispatch, allowing them to be directly dispatched.
- Ensure the bound action creators behave as expected.

## Task 7: Async Action Creators

- Set up Redux and Redux Thunk.
- Simulate an API for login.
- Implement async action creators for login request, success, and failure.
- Write tests to verify the behavior of the async action creators.
