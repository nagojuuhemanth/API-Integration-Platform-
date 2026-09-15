# API-Integration-Platform-

A full-stack experimental web platform that integrates multiple AI models and external APIs into a unified interface. The platform allows users to submit prompts, interact with connected AI services, and view AI-generated responses through a responsive web interface.

## Features

- Integrates multiple AI models and external APIs.
- Provides a unified interface for interacting with AI tools.
- Supports prompt-based user queries.
- Displays AI-generated responses dynamically.
- REST API-based communication between frontend and backend.
- Backend routing for external AI inference services.
- Structured request handling and error management.
- Responsive frontend interface.

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- DaisyUI

### Backend
- Node.js
- Express.js
- REST APIs

### APIs
- External AI model APIs
- Third-party APIs

## System Architecture

```text
User
  |
  v
React Frontend
  |
  | HTTP Request
  v
Node.js + Express.js
  |
  | API Routing
  v
External AI / API Services
  |
  v
AI Generated Response
  |
  v
React Frontend
