# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with this repository.

## Project Overview

WhatsAppApi - A WhatsApp API implementation.

## Development Commands

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Run tests
npm test

# Build for production
npm run build

# Lint code
npm run lint
```

## Project Structure

```
/src           - Source code
/tests         - Test files
/docs          - Documentation
```

## Code Style Guidelines

- Use TypeScript for type safety
- Follow ESLint configuration for code style
- Write unit tests for new functionality
- Use meaningful variable and function names
- Add JSDoc comments for public APIs

## API Design Principles

- RESTful endpoints where applicable
- Proper error handling with meaningful error messages
- Input validation on all endpoints
- Rate limiting for external API calls

## Git Workflow

- Create feature branches from main
- Write descriptive commit messages
- Keep commits atomic and focused
