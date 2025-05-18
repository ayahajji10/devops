# DevOps Learning Project

This project demonstrates DevOps practices and tools integration including CI/CD, containerization, and monitoring.

## Project Components

- Frontend: React.js application
- Backend: Node.js REST API
- Database: MongoDB
- Containerization: Docker
- CI/CD: GitHub Actions
- Monitoring: Prometheus & Grafana
- Infrastructure as Code: Terraform
- Configuration Management: Ansible

## Project Structure

```
.
├── frontend/           # React.js frontend application
├── backend/           # Node.js backend API
├── docker/           # Docker configuration files
├── terraform/        # Infrastructure as Code
├── ansible/          # Configuration management
├── .github/          # GitHub Actions CI/CD workflows
└── monitoring/       # Prometheus & Grafana configs
```

## Getting Started

1. Clone the repository
2. Install dependencies:
   - Node.js 18+
   - Docker
   - Docker Compose
   - Terraform
   - Ansible

3. Run development environment:
```bash
docker-compose up -d
```

## Development

- Frontend runs on port 3000
- Backend API runs on port 5000
- MongoDB runs on port 27017

## CI/CD Pipeline

The project uses GitHub Actions for CI/CD with the following stages:
1. Build
2. Test
3. Docker image creation
4. Deployment to cloud

## Monitoring

- Prometheus metrics available at `/metrics`
- Grafana dashboards for visualization
- Basic alerting configuration included

## Contributing

1. Create a feature branch
2. Make your changes
3. Submit a pull request

## License

MIT 