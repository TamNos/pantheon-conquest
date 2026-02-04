# API Specification

## Endpoints

### Realms
- **GET /realms**  
  Retrieve a list of realms.

- **GET /realms/{id}**  
  Retrieve a specific realm by ID.

### Players
- **GET /players**  
  Retrieve a list of players.

- **GET /players/{id}**  
  Retrieve a specific player by ID.

### Pantheons
- **GET /pantheons**  
  Retrieve a list of pantheons.

- **GET /pantheons/{id}**  
  Retrieve a specific pantheon by ID.

### Actions
- **POST /actions**  
  Create an action.

- **GET /actions/{id}**  
  Retrieve an action by ID.

### WebSocket Events
- **events**  
  Subscriptions to various events (e.g., player updates, realm changes).

### Rate Limits
- **GET /rate-limit**  
  Retrieve current rate limit status.
  
## Error Codes

- **400 Bad Request**  
  The request was malformed or invalid.

- **401 Unauthorized**  
  Authentication failed or user does not have permissions.

- **404 Not Found**  
  The requested resource was not found.

- **500 Internal Server Error**  
  An unexpected error occurred on the server.

## Notes
- Ensure to handle rate-limiting responses accordingly.
- Keep API documentation up to date with changes in functionality.

---
*Generated on: 2026-02-04 21:31:30 UTC*