# LAB - 00

## Proof of Life Server

### Author: Ollie Comet

### Links and Resources
* [submission PR](https://github.com/ollie-career-track/lab-00/pull/1)
* [travis](https://travis-ci.com/ollie-career-track/lab-00)
* [front-end](https://olliecomet-lab-00.herokuapp.com/)

#### Documentation
* [jsdoc](https://olliecomet-lab-00.herokuapp.com/docs/)

### Modules
#### `pos.js`

###### `isAlive(dead) -> boolean` 
Returns true/false to indicate how the server works

### Setup
#### `.env` requirements
* `PORT` - Port Number

**or, include an `.env.example`**

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns a boolean
* Endpoint: `/docs`
  * Returns JSDoc Documentation Pages

#### Tests
* Unit Tests: `npm test`
* Lint Tests: `npm run lint`