# Sportz

Sportz is a comprehensive backend service designed for live sports coverage, utilizing REST endpoints for match and commentary management alongside WebSockets for real-time data broadcasting. The platform allows clients to monitor match lists and receive instantaneous score and play-by-play commentary updates through a robust streaming architecture that features heartbeats, rate limiting, and backpressure protection. By enforcing live-only updates and utilizing Zod schemas for strict input validation, Sportz ensures a reliable and structured flow of information; additionally, the service includes dedicated seeding tools to simulate live game environments and facilitate development.

## Tech Stack

- React
- Arcjet
- PostgreSQL
- Drizzle ORM
- Drizzle Kit
- Node.js
- Express.js
- CORS Middleware
- Dotenv
- WebSockets
- WS Library
- Zod

## Features

- Match management
- Commentary management
- Real-Time Broadcasts
- WebSocket Protocol
- Robust WS Behavior
- Input Validation
- Seed Tooling
