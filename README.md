# Tiptap Realtime Collaborative Text Editor _without backend_ <3

## Objective

The objective of this project is to learn how to build a realtime collaborative text editor, understand the challenges involved, and explore using only NATS.IO as the backend.

## Technologies

- Vue 3 Composition API
- TypeScript
- NATS
- Docker

## How to run it?

TODO...

## Roadmap

- [-] Setup project
  - [x] Initialize repo
  - [x] Install dependencies (Vue, Tiptap, nats.js)
  - [x] Create NATS Docker Compose file
  - [x] Setup NATS stream
  - [ ] Setup NATS JWT Auth
- [ ] Frontend
  - [ ] Design a simple interface =D
  - [ ] Create individual streams
  - [ ] Generate unique key to use as a "session identifier"
  - [ ] Send and receive data through WebSockets
  - [ ] Connect multiple users
  - [ ] Save relevant data in local storage
  - [ ] Sync local storage data between users
