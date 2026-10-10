
# Redis Clone

A Redis-like in-memory data store implemented from scratch
in C++20 for learning systems programming and networking.

## Goals

- Build a working server in C++.
- Understand TCP networking and client-server communication.
- Implement an in-memory key-value store.
- Learn data structures, memory management, and concurrency.
- Practice software testing, debugging, and documentation.

## Planned Features

- Key-value operations
- TCP client connections
- RESP-compatible command protocol
- Expiration and TTL
- Persistence
- Basic concurrent client handling

## Technology Stack

- C++20
- Clang
- CMake
- Git and GitHub
- VS Code

## Build Instructions

```bash
cmake -S . -B build
cmake --build build
./build/redis_clone
```

## Current Status

Week 1: Project foundation and build setup.

## Learning Project

This project is for educational purposes. It is not
intended to replace production Redis.