# Protocol translator

First standalone decoder service. Part of [GPS Fleet Tracking System](../README.md).

> **Structure only.** The source code is private. Source files here are intentionally empty so you can see how the project is organized. Commands describe the private codebase.

## Responsibilities

- Tracker detection and session handling
- Decoder with unit tests
- Continuous integration workflow

## Main dependencies

`dotenv`, `jest`, `pg`

## Structure

```text
.github/                          1 file
src/controllers/                  1 file
src/itrack/                       5 files
src/models/                       2 files
src/                              2 files
src/utils/                        1 file
tests/                            1 file
```

## Commands

```bash
npm install
npm start
npm test
```
