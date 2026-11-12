# Book Store — MERN Stack

A full-stack book-store application organized around a JavaScript-based frontend and backend.

## Overview
This repository contains a book-store project built around the MERN ecosystem. The available source and configuration files define the implemented workflows, data model, and API behavior.

## Technology
- MongoDB
- Express.js
- React
- Node.js

## Getting Started
1. Install a supported Node.js LTS release and configure a MongoDB instance.
2. Clone the repository:
   ```bash
   git clone https://github.com/MahiTzy/Book-Store-MERN-Stack.git
   cd Book-Store-MERN-Stack
   ```
3. Inspect the repository for frontend and backend folders, then install dependencies in each folder containing a `package.json`:
   ```bash
   npm install
   ```
4. Configure the environment variables expected by the backend. Do not commit secrets.
5. Start each application using the scripts declared in its `package.json` (commonly `npm run dev` or `npm start`).

## Configuration
Use local environment files for database connection details and application configuration. Refer to the source code for the exact variable names and never publish credentials.

## Development
Run the frontend and backend according to their package scripts. Confirm the configured API base URL and database connection before testing end-to-end flows.

## License
No license terms are specified here. Refer to the repository's LICENSE file, if present, before reusing the code.