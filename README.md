# Questioner
[![Coverage Status](https://coveralls.io/repos/github/openwell/questioner/badge.svg?branch=develop)](https://coveralls.io/github/openwell/questioner?branch=develop)

[![Maintainability](https://api.codeclimate.com/v1/badges/a3a966589be730bc865e/maintainability)](https://codeclimate.com/github/openwell/questioner/maintainability)

[![Test Coverage](https://api.codeclimate.com/v1/badges/a3a966589be730bc865e/test_coverage)](https://codeclimate.com/github/openwell/questioner/test_coverage)

Crowd-source questions for a meetup. Questioner helps the meetup organizer prioritize
questions to be answered. Other users can vote on asked questions and they bubble to the top
or bottom of the log..

## Getting Started

Clone the Repo.
-------------
Run npm install to install all necessary packages.

### Prerequisites

The following tools will be needed to run this application successfully:

Node v10.13.0 or above
---
Npm v6.4.1 or above
---

### ENDPOINTS

- POST **/api/v1/meetups** Create an meetup record.
- GET **/api/v1//meetups** Fetch all meetup records.
- GET **/api/v1//meetups/1/<meetup-id>** Fetch a specific meetup record.
- GET **/api/v1/meetups/upcoming/** Fetch all upcoming meetup records.
- POST **/api/v1/questions** Create a question for a specific meetup.
- PATCH **/api/v1/questions/<question-id>/upvote** Upvote (increase votes by 1) a specific question.
- PATCH **/api/v1/questions/<question-id>/downvote** Downvote (decrease votes by 1) a specific question.
- POST **/api/v1/meetups/<meetup-id>/rsvps** Respond to meetup RSVP.

### Installing

## On your Local Machine
- Pull the [develop](https://github.com/openwell/questioner) branch off this repository
- Run `npm install` to install all dependencies
- Run npm start to start the app
- App runs on port 3000
- Access endpoints on **localhost:3000**

## Running the tests

Run `npm test` in the terminal for the cloned folder.

### Break down into end to end tests

- It tests the API end-point.
- It tests the REST API functionality

## Built With

* [Node.js](http://www.nodejs.org/) - Runtime-Environment

## Authors

* **Ojo Timileyin**

## Acknowledgments
* [Web Developerment Youtuber](htttps://youtube.com)
* [StackOver-Flow](https://stackoverflow.org)
* The Andela Organisation
* [Udemy.com](https://udemy.com)
* Andela 40 Colleagues
