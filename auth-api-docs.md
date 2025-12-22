# Authentication API Documentation

## POST /auth/login

Authenticates a user and returns an access token.

### Request Headers

### Request Body
```json
{
  "email": "user@example.com",
  "password": "string"
}
{
  "access_token": "string",
  "token_type": "Bearer",
  "expires_in": 3600
}

Commit the file.

---

## STEP 4: Update README to link the sample
Under **Writing Samples**, change one line to:

```markdown
- [Authentication API Documentation](auth-api-docs.md)
