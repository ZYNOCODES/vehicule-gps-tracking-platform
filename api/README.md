# API

REST, WebSocket and storage. Part of [GPS Fleet Tracking System](../README.md).

> **Structure only.** The source code is private. Source files here are intentionally empty so you can see how the project is organized. Commands describe the private codebase.

## Responsibilities

- Internal routes reserved for the gateway
- Public routes protected by JWT
- Devices, location history, events and command queue
- Socket.IO live updates
- Schema migration and movement simulator

## Main dependencies

`dotenv`, `express`, `socket.io`, `pg`, `bcryptjs`, `jsonwebtoken`, `cors`

## Structure

```text
script/                           1 file
src/                              1 file
src/db/                           2 files
src/middleware/                   3 files
src/routes/                       8 files
src/services/                     2 files
```

## Commands

```bash
npm install
npm run dev
npm start
npm run migrate
```
