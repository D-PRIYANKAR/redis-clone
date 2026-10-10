
# Redis Clone — Initial Architecture

## 1. Objective

Build a small Redis-like in-memory key-value server in
C++20 to understand systems programming.

## 2. Initial Scope

The first version will focus on:
- String key-value storage
- Basic commands such as PING, SET, GET, and DEL
- TCP-based client communication
- A simple command parser
- Automated tests

## 3. Planned Components

### Server
Accepts client connections.

### Protocol Parser
Converts incoming client data into commands.

### Command Handler
Validates and executes supported commands.

### In-Memory Store
Stores keys and values and handles expiration.

### Persistence
A later component for saving and recovering data.

## 4. Design Principles

- Use RAII for resource management.
- Prefer clear interfaces and small components.
- Separate networking from storage logic.
- Test behavior with automated tests.
- Document important design decisions.

## 5. Current Limitations

No networking, command parser, persistence, or
key-value storage has been implemented yet.

## 6. Future Decisions

Evaluate the event loop, concurrency model,
protocol handling, and persistence format as
the implementation progresses.