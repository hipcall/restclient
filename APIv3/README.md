# Hipcall Public API - REST Client Collection

This directory contains HTTP request files for testing Hipcall Public API endpoints using REST Client extensions (VS Code, Cursor, etc.).

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

## Authentication

The token variable and the Base URL are loaded from your environment configuration file.
For accessing them in the .http files:
- Go to **Extensions** 
- Click on `Rest Client` 
- Click on ⚙️ 
- Go to Settings 
- Find `Rest-client: Environment Variables`
- Click on `Edit in settings.json`
- Copy the code below and customize for your information 
```json
{
    "rest-client.environmentVariables": {
        "$shared": {
            "base_url": "https://use.hipcall.com.tr/api/v3",
            "token": "your_token_here"
        }
    }
}
```

All requests require a Bearer token in the Authorization header:

```
Authorization: Bearer {{token}}
```

