# VICA Engineering Assessment
## Background
ABC Book is a book fan club. ABC Book allows its member to borrow books from the club. Due to increasing membershp, the club management decides to create a web console for easier management. This console will have 3 types of users: Admin, Editor and Member. 

This console should support the following functions:
- User Management
  - Only accessible to Admin and Editor
  - Only Admin can add/remove/update users
- Book Management
  - Accessible to all users
  - Each book should contain the following details
    - Title
    - Description
    - Genre
    - Author
    - Year Published
    - Status whether the book is available for borrowing
  - Only Admin and Editor can add/remove/update books
  - All users can borrow/return books

## Requirements
### Backend
### Frontend
For frontend, please build a web console that fulfills the following requirements:
- Please use React + Redux
- The app should be written in Typescript
- You are encouraged to use Create React App (CRA)
- If you are doing this as standalone frontend, please populate your app with hardcoded data; otherwise please use the data from the backend you have built
- Pages
  - A User Management page that:
    - List all the users
    - Allow Admin to add/remove/update users
    - Support sorting, pagination and filtering
    - You can use any React UI frameworks for the table
  - A Book Management page that:
    - List all the books
    - Allow Admin and Editor to add/remove/update books
    - Allow all users to borrow/return books
    - Support sorting, pagination and filtering
    - You can use any React UI frameworks for the table
  - An Analytics page that:
    - Use a suitable chart to demonstrate the breakdown of books by genre
    - Use a suitable chart to demonstrate the breakdown of books by year published
    - You can use any React chart libraries
- You will be asked to explain and justify
  - How you setup and design the Redux store
  - The project file structure
  - The implementation
  - Scalability of your project
- Bonus points for:
  - Using React routing
  - Using custom hook from React v16+
  - Mobile responsiveness


