# FitFlow Redesign – IT3060 Lab Exercise 05

## Recommended stack
- Frontend: Flutter
- Main backend: NestJS + TypeScript
- AI service: FastAPI + Python
- Database: Amazon RDS PostgreSQL
- Cache/realtime support: Amazon ElastiCache Redis
- Authentication: Amazon Cognito
- Object storage: Amazon S3
- Security/operations: AWS WAF, KMS, Secrets Manager, CloudWatch

## Project structure
```text
fitflow-redesign/
├── frontend/
├── backend/
├── ai-service/
├── docs/
│   ├── architecture-diagram.png
│   ├── technology-comparison.md
│   └── ADR-001.md
├── .gitignore
└── README.md
```

## Core flows
1. Personalized workout generation
2. Camera/search nutrition logging
3. Private social circles and challenges
4. Progress tracking and milestones

## Security
HTTPS/TLS, JWT/OIDC, least privilege, encryption, privacy-by-default sharing,
data minimization, retention controls and secrets outside source control.
