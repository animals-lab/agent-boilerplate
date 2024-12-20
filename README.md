# Llama Agent

A modern full-stack boilerplate project featuring Next.js frontend with TypeScript and FastAPI backend, powered by LlamaIndex for building AI agent workflows. This template provides a solid foundation for building scalable AI-enabled web applications with a clean architecture.

## Tech Stack

### Frontend
- Next.js 15
- React 19
- TypeScript
- Tailwind CSS 3.4
- ESLint
- PNPM for efficient package management

### Backend
- FastAPI 0.109.1+
- Python 3.12
- Uvicorn ASGI server
- PDM for dependency management
- Llama Index 0.12.3

## Prerequisites

- Python 3.12
- PDM (Python dependency manager)
- Node.js 18+
- PNPM (Node.js package manager)

## Setup & Development

Run both frontend and backend development servers:

```bash
pdm run dev
```

This will:
- Install both backend and frontend dependencies automatically
- Start frontend server at http://localhost:3000 (Next.js development server)
- Start backend server at http://localhost:8000 (FastAPI with auto-reload)

## Production

To run in production mode:

```bash
pdm run prod
```

## Project Structure

```
llama-agent/
├── frontend/          # Next.js frontend application
│   ├── app/          # Next.js app directory (App Router)
│   ├── components/   # React components
│   ├── lib/          # Utility functions and shared code
│   └── package.json  # Frontend dependencies
│
├── api/              # FastAPI backend
│   ├── routers/     # API route handlers
│   └── server.py    # Main FastAPI application
│
├── app/              # Core Python application code
│   ├── agent.py     # Agent implementation
│   └── vercel.py    # Vercel-related functionality
│
├── run.py           # Development and production server runner
├── pyproject.toml   # Python project configuration
└── pdm.lock         # Python dependency lock file
```

## Features

- Modern frontend with Next.js 15 and React 19
- Type-safe development with TypeScript
- Fast and efficient API with FastAPI
- LlamaIndex integration for building AI agent workflows
- Development and production server configurations
- Modern UI with Tailwind CSS 3.4
- Efficient package management with PDM and PNPM
- Hot reloading for both frontend and backend in development

## License

MIT License 