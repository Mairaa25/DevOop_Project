# DevOop_Project

## Services
- **Database Service**: PostgreSQL exposed on port 5432.
- **Cache Service**: Redis exposed on port 6379.

## Running with Docker Compose
Run `docker-compose up -d` to start both services.

## Git Branching Workflow
- `main`: Stable branch.
- `develop`: Development branch.
- Feature branches: Separate branches for each service.

## Environment Variable Management
- Sensitive information is stored in the `.env` file.
- `.env` is included in `.gitignore` to avoid committing sensitive data.
