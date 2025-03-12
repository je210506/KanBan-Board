# KanBan-Board


## Description
This project enhances an existing Kanban board application by implementing authentication using JSON Web Tokens (JWTs). JWT authentication ensures secure user identity verification, enabling users to log in and manage their tasks safely. The application features a login page, protected API routes, and is deployed on Render.This Social Network API is built to support a social network web application where users can share their thoughts, react to friends' thoughts, and manage a friend list. It utilizes Express.js for routing, MongoDB as the database, and Mongoose ODM for database interactions. The API supports CRUD operations for users, thoughts, reactions, and friend management.


## Badge
None.


## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Test Instructions](#testinstructions)
- [Questions](#questions)
   
## Features

- User authentication with JWTs

- Secure login page

- Protected API routes

- Task management on a Kanban board

- Deployment to Render for accessibility



## Installation 
1. Clone the Repository:
```
git clone <respository-SSH key>
cd kanban-board
```

2. Install the necessary dependencies:
```
npm install
```

3. Create a .env file and configure the following variables

```
DB_NAME=kanban_db
DB_USER=postgres
DB_PASSWORD=
JWT_SECRET_KEY=superSecretSecret
```
4. Start the development server:

```
npm run build

npm run start:dev
```


## Usage 

Open the application in your browser.

Register a new user or log in with existing credentials.

Manage tasks on the Kanban board:

Create, update, move, and delete tasks.

Enjoy a secure and efficient workflow!


## License 
This project is not licensed. 


## Contributing 
Contributions are welcome! To contribute:
1. Fork the repository.

2. Create a new branch:
```
git checkout -b feature/yourFeature
```

3. Commit your changes:
```

git commit -m "Add new feature"
```

4. Push to your branch:
```

git push origin feature/yourFeature
```

5. Open a pull request for review.


## Test Instructions 
To run tests, use the following command:

```
npm test
```

Ensure that your test database is properly configured before running tests.


## Questions 
If there's any additional questions I can answer for you, you can reach out to me at https://github.com/je210506 or [lalanne1011@gmail.com](mailto:lalanne1011@gmail.com}).
