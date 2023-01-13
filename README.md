# User management

Webapp which reads a list of users from the server and displays the same on MaterialUI table, with light and dark mode (toggle button which changes theme). You also may add new users to the database, where the inputs are validated with regex. On failure of add user, an error modal/alert popup appears stating the reason what went wrong. Contains unit testing with Jest and Testing Library.

## Features

-   Material UI
-   Light + Dark Theme
-   Input validations for add user
-   Popup modal alert for errors
-   Unit testing

## Demo

Here is a working live demo : https://github.com/hemanth-kumarv/user-management-frontend/screenshots/Ajmera-frontend-demo.mp4
<video src="/screenshots/Ajmera-frontend-demo.mp4" width=500 ></video>

### Light Mode

![](/screenshots/lightMode.png)

### Dark Mode

![](/screenshots/darkMode.png)

### Input validation (for email field)

![](/screenshots/invalidEmail.png)

### Error popup/modal

![](/screenshots/addUserFailure.png)

## Setup

Clone this repo to your desktop and run `npm install` to install all the dependencies.

To get data, or add data from/to the database, you need to install the backend server from https://github.com/hemanth-kumarv/user-management-backend and run it locally at port 3001.

## Usage

Once the dependencies are installed, you need to run `npm run start` to start the server.
You will then be able to access it at `localhost:3000`

## To-do

-   Better UX
-   Handle image uploads for add user
-   Display loading and success modals/popups
-   Better error handling
-   More functionalities
