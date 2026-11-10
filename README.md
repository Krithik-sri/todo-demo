# Todo

A small todo app built live by two AI agents on two laptops, working in one shared repo. One agent builds the backend in `api/`, the other builds the web page in `web/`.

## Run it

- Backend: `node api/server.mjs` (port 4000)
- Frontend: `node web/serve.mjs` (port 5173)

## The API contract

The backend posts it as a decision in the Room. The frontend reads it there.
