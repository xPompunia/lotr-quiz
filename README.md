# LOTR Quiz App

A simple React quiz app about The Lord of the Rings.

## Tech

- React
- Context API + useReducer
- json-server (for quiz questions)

## Run locally

1. Install dependencies:

   npm install

2. Start API server (questions):

   npm run server

3. In a second terminal, start React app:

   npm start

4. Open:

   http://localhost:3000

## Available scripts

- npm start: starts React development server
- npm run server: starts json-server on port 9000
- npm test: runs tests
- npm run build: creates production build

## Project structure

- src: app version using Context API
- src-no-context: version without Context API
- data/questions.json: quiz data source for json-server

## Notes

- If questions do not load, make sure npm run server is running on port 9000.
