# Security Policy

## Supported Versions
| Version | Supported |
|---------|-----------|
| 1.x     | ✅ Yes    |

## Reporting a Vulnerability
Please do NOT open a public GitHub issue for security vulnerabilities.

Email: security@sentimentpro.ai (replace with your email)

We will respond within 48 hours and work with you to resolve the issue.

## Security Features
- Input validation on all endpoints (Pydantic v2)
- Rate limiting via middleware
- SQL injection prevention (SQLAlchemy ORM)
- No raw SQL queries
- API key authentication (production mode)
