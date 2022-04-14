# [bamboo](https://github.com/phunky-panda94/bamboo)

This is a full-stack Reddit clone project deployed using `heroku`.

## Technologies

**Front-end**

Using React and JavaScript:

- state
- props
- React Router
- useEffect and useState hooks

**Backend**

Using Node.js, Express, MongoDB and Mongoose:

- REST APIs
- Unit and integration testing of REST API endpoints using `Jest` and `supertest`
- NoSQL models and queries
- Authentication using `JWT` and `bcryptjs`
- Input validation and sanitisation using `express-validator`

## Entity Relationship Diagram

![bamboo drawio](https://user-images.githubusercontent.com/63854834/157994143-f244308d-e12e-4d99-a6c9-8a4b80cca924.svg)

## Challenges

The key challenges I had for this project were:

- implementing the ability to vote and unvote while updating the count
- implementing the post and comment age counter
- updating the user interface depending on if a user is logged in or not
- getting new posts and comments to be displayed without refreshing the page
- writing complete unit and integration tests for the controllers and REST API endpoints
- cross-origin issues when retrieving data from backend API
