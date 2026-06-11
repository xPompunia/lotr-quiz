# LOTR Quiz

Simple React quiz app about The Lord of the Rings — timed questions, scoring,
and a high-score screen. State is managed with the Context API + `useReducer`;
questions are served by json-server.

## Running

```bash
npm install
npm run server   # json-server with the questions on port 9000
npm start        # React dev server, in a second terminal
```

Open http://localhost:3000. If questions do not load, make sure
`npm run server` is running.

## Project structure

- `src/components` — quiz screens and UI
- `src/contexts/QuizContext.js` — quiz state (Context API + reducer)
- `data/questions.json` — quiz data served by json-server
