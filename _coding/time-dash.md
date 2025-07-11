---
title: 'TimeDash'
excerpt: "A full-stack time tracking application with auto-generated API documentation and type-safe frontend"
classes: wide
sidebar:
  - text: '[Source Code](https://github.com/dirschn/hour-tracker)'
  - title: 'Skills'
    text: 'Ruby on Rails 8.0, Angular 20, TypeScript, OpenAPI, rswag, Bootstrap, SQLite'
---

TimeDash is a full-stack time tracking application that demonstrates modern development practices through auto-generated API documentation and type-safe client generation. The project showcases a sophisticated workflow where OpenAPI specifications drive both documentation and frontend code generation.

**Technology Stack:**
- **Backend:** Ruby on Rails 8.0 with rswag for OpenAPI generation
- **Frontend:** Angular 20 with TypeScript and Bootstrap
- **Database:** SQLite (development) with production migration options
- **Workflow:** Automated API client generation and interactive development tools

## Key Innovation

**Contract-First Development:** API endpoints are defined through rswag test specifications, automatically generating both OpenAPI documentation and TypeScript clients. This eliminates version mismatches and ensures documentation stays current with implementation.

**Interactive Development Environment:** Custom scripts provide seamless full-stack development:
- `./scripts/dev.sh` - Runs both servers with dashboard switching
- `./scripts/update-api.sh` - Updates specs and regenerates frontend clients

## Application Features

TimeDash provides comprehensive time management for:
- User shift tracking across multiple positions and hourly rates
- Company and group organization for complex work structures
- Detailed reporting and time analysis

## Technical Impact

This project demonstrates several advanced patterns that solve common full-stack development challenges:

**End-to-End Type Safety:** From Rails models through API responses to Angular components, eliminating runtime errors and improving developer productivity.

**Zero-Maintenance API Clients:** TypeScript interfaces and services generate automatically from OpenAPI specs, removing manual synchronization overhead.

**Living Documentation:** API documentation updates automatically with code changes through test-driven specification design.

## Future Possibilities

The type-safe architecture naturally extends to mobile applications, advanced analytics, and third-party integrations. The automated client generation approach scales to support React Native, Flutter, or any platform that consumes REST APIs.

TimeDash showcases how thoughtful tooling and architecture decisions can significantly reduce development overhead while maintaining code quality and scalability.
