# Environment Variables

## Back-End (`appsettings.json` and User Secrets)

- **ConnectionStrings:DefaultConnection:** Database connection string.
- **Jwt:Key:** Secret key for JWT token generation.
- **Jwt:Issuer:** Issuer of the JWT tokens.
- **Jwt:Audience:** Audience for the JWT tokens.
- **Stripe:SecretKey:** Stripe secret API key.
- **Stripe:PublishableKey:** Stripe publishable API key.

## Front-End (`client/.env`)

- **REACT_APP_API_BASE_URL:** Base URL for the back-end API.
- **REACT_APP_STRIPE_PUBLISHABLE_KEY:** Stripe publishable API key.
