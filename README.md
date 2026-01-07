# CareerMate API

AI-Powered Job Companion backend service.

## 🚀 Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Run API server
python app.py

# Run tests
pytest test_app.py -v
```

## 📡 API Endpoints

- `GET /` - Welcome message
- `GET /health` - Health check

## 🐳 Docker Deployment

```bash
# Build image
docker build -t careermate .

# Run container
docker run -p 5000:5000 careermate
```

## 🔄 CI/CD Pipeline

- **Test Job**: Runs unit tests with coverage
- **Build Job**: Creates Docker image artifact
- **Triggers**: Push to main/develop branches

## 📊 Project Structure

```
careermate/
├── app.py              # Flask API
├── test_app.py          # Unit tests
├── requirements.txt     # Dependencies
├── Dockerfile          # Container config
└── .github/workflows/ # CI/CD pipeline
```
