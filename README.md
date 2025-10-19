# REAK-Score
This repository contains the REAK-Score frontend and a minimal optional backend example that demonstrates how to connect to MongoDB.

## Files added for backend

- `server.js` - minimal Express server that connects to MongoDB using the `MONGO_URI` environment variable.
- `package.json` - dependencies and start script.
- `.env.example` - example environment variables.
- `.gitignore` - ignores node_modules and .env.

## Backend (optional)

Quick start:

1. Copy `.env.example` to `.env` and fill in `MONGO_URI` with your connection string.

2. Install dependencies:

	npm install

3. Start the server:

	npm start

4. Check health:

	open http://localhost:3001/health

Notes:

- The server expects `MONGO_URI` to be set. If it is missing the server will exit with an error to make the problem explicit in development.
- The provided backend is intentionally minimal. If you want, I can add authentication, models, routes, or integrate it with the existing frontend files like `index.html`.
# REAK-Score