# DEX Course Intermediate

A data extraction and transformation project.

## Project Structure

- **docker/**: Docker configuration files
- **src/api/**: API endpoints and services
- **src/ingestion/**: Data ingestion modules
- **src/transformations/**: Data transformation logic

## Getting Started

### Prerequisites
- Python 3.x
- Docker and Docker Compose

### Installation

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment variables in `.env`

### Running with Docker

```bash
docker-compose up
```

## License

MIT
