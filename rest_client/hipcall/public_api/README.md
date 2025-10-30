# Hipcall Public API - REST Client Collection

This directory contains HTTP request files for testing Hipcall Public API endpoints using REST Client extensions (VS Code, IntelliJ, etc.).

## Setup

Before running these requests, create an `http-client.env.json` file in your project root with the following structure:


## Available Endpoints

- **Account.http** - User management endpoints
- **Contact_Centre.http** - Companies, contacts, and lookup operations
- **Phone_System.http** - Calls, voicemails, teams, greetings, and extensions
- **Profile.http** - User profile information
- **Push_Tokens.http** - Push notification token management
- **Sales.http** - Deals management
- **SIP_Tokens.http** - SIP token generation
- **Tags.http** - Tag operations
- **Task.http** - Task management and comments

## Usage

1. Install a REST Client extension for your IDE
2. Open any `.http` file
3. Click "Send Request" above the request you want to execute
4. View the response in the response panel

## Authentication

All requests require a Bearer token in the Authorization header:

```
Authorization: Bearer {{token}}
```

The token variable is loaded from your environment configuration file.

