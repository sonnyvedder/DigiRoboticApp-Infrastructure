# DigiRoboticApp-Infrastructure

Infrastructure services for the DigiRoboticApp ecosystem.

## Tech Stack
- Redis
- RabbitMQ
- Kafka
- Elasticsearch
- Docker

## Development Setup

### Prerequisites
- Docker Desktop
- Git

### Setup Instructions
```bash
# Clone the repository
git clone git@github.com:sonnyvedder/DigiRoboticApp-Infrastructure.git
cd DigiRoboticApp-Infrastructure

# Create environment file
copy .env.example .env

# Start infrastructure services
docker-compose up -d