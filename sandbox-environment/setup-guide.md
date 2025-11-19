# 🧪 Sandbox Environment Setup Guide

## Development Environment Configuration

This guide provides setup instructions for developing and testing IT discoveries.

## Quick Start

### Prerequisites
- Docker Desktop or Docker Engine
- Git
- Python 3.8+
- Node.js 14+

### Docker Setup

```bash
# Build the sandbox environment
docker build -t it-discoveries-sandbox .

# Run the sandbox
docker run -it it-discoveries-sandbox
```

### GitHub Integration

1. Clone this repository
2. Create a feature branch
3. Add your discoveries
4. Submit pull requests

## Testing

Run tests before committing:

```bash
pytest tests/
npm test
```

---

**Status:** Active
**Last Updated:** November 2025
