
# Basic Express Server: Dynamic API Phase 1
**Author:** Amanda Marquez  
**Version:** 1.0.0  
https://basic-express-server-cjd1.onrender.com

## Project Overview
This Express server application sets the stage for efficient web service development with its robust and well-organized structure. It introduces a dedicated `/person` endpoint tailored to process requests containing a `name` property in the query string.

## Key Components
### /person Route:
- Expects a query string with the `name` property.
- Responds with a JSON object encapsulating the provided name.
- Ensures user-friendly API interactions by issuing informative error messages for absent parameters.

### Server Initialization:
- Seamlessly managed within the index file for quick setup and configuration.

### Middleware Modules:
1. **Logging:** Captures and logs request data for effective debugging and server operation monitoring.
2. **Input Validation:** Validates incoming requests to maintain security and data integrity.

### Error Handling Modules:
- **404 Responses:** Handles requests to non-existent routes to provide users with appropriate feedback.
- **500 Responses:** Manages internal server errors to prevent downtimes and maintain server reliability.

## Design Philosophy:
The architecture prioritizes clean structure and separation of concerns, enabling easy management and scalability of each component. This modular design facilitates maintenance and promotes code reuse across different parts of the application and projects.

## UML:
![UML](/uml.png)
