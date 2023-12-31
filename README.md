# 18socialplatform
>### Module 18 Coding Bootcamp Challenge - A NoSQL social networking API <br><br>
>  social platform is an API aimed for use in social networking applications, allowing developers to store and retrieve data typical of social media networks including user data, posts, reactions, and friends lists. The API utilizes a MongoDB database and the Mongoose ODM, as well as the Express.js package for routing. <br><br>

![JavaScript][js-url]
![Node][node-url]
![Mongo][mongo-url]
![Express][express-url]

## Installation

Clone the repository:

```sh
git clone https://github.com/sschrimmer/18socialplatform
```

Install the required dependencies:

```sh
npm install
```

Run the project in your local browser:

```sh
npm start
```


## Usage

Use your browser or an app like [Insomnia](https://insomnia.rest/) to test the REST API.

## Endpoints

**User**
- Get all users:        `GET /api/users`
- Create a user:        `POST /api/users`
- Get user by ID:       `GET /api/users/:userId'
- Update a user:        `PUT /api/users/:userId'
- Delete a user:        `DELETE /api/users/:userId'
- Add a friend:         `PUT /api/users/:userId/friends/:friendId`
- Delete a friend:      `DELETE /api/users/:userId/friends/:friendId`

**Thought**
- Get all thoughts:     `GET /api/thoughts`
- Create a thought:     `POST /api/thoughts`
- Get thought by ID:    `GET /api/thoughts/:thoughtId'
- Update a thought:     `PUT /api/thoughts/:thoughtId'
- Delete a thought:     `DELETE /api/thoughts/:thoughtId'

**Reaction**
- Add a reaction:       `PUT /api/thoughts/:id/reactions`
- Delete a reaction:    `DELETE /api/thoughts/:id/reactions`

## Meta

View my profile – [GitHub] https://github.com/sschrimmer

Distributed under the MIT license. See ``LICENSE`` for more information.
