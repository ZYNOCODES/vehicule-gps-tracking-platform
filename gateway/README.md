# TCP gateway

Persistent device connections and protocol decoding. Part of [GPS Fleet Tracking System](../README.md).

> **Structure only.** The source code is private. Source files here are intentionally empty so you can see how the project is organized. Commands describe the private codebase.

## Responsibilities

- Packet framing for fragmented and joined TCP data
- iStartek protocol parser with checksum validation
- Device sessions, keep-alive and idle timeout
- Command builder and priority queue
- Forwards decoded data to the API with a shared secret

## Main dependencies

`dotenv`

## Structure

```text
src/commands/                     2 files
src/connection/                   2 files
src/protocol/                     3 files
src/                              1 file
src/services/                     1 file
src/translator/                   1 file
src/utils/                        2 files
```

## Commands

```bash
npm install
npm run dev
npm start
```
