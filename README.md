# DotNet9Authentication

This project demonstrates how to implement OAuth2-based authentication using ASP.NET Core Identity with a PostgreSQL database. It configures Swagger/OpenAPI to provide API documentation and security definitions.

## Explanation

1. **Database Setup**:
   - The `DataContext` is configured with PostgreSQL using Entity Framework Core.

2. **Identity Configuration**:
   - ASP.NET Core Identity is set up to manage user authentication.
   - `IdentityApiEndpoints` are added with `IdentityUser` and connected to the `DataContext`.

3. **Swagger/OpenAPI**:
   - Swagger/OpenAPI is configured to expose API documentation.
   - OAuth2 security definition is added for API authorization.

4. **Middleware Setup**:
   - In development, Swagger UI and OpenAPI are enabled.
   - The Identity API endpoints are mapped.
   - HTTPS redirection and authorization middleware are applied.

## Security

- OAuth2-based authentication is enabled via Swagger UI.
- Security requirements are applied to API endpoints for secure access.

