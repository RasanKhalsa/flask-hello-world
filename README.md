# Flask Hello World + GitHub Actions CI

A minimal Flask app integrated with a full CI pipeline using GitHub Actions.

## Features
- Build and test on push/PR
- Code quality check via flake8
- Docker image build and push to GitHub Container Registry
- Kubernetes manifest auto-updated with latest image tag

## Quick Start

```bash
# Clone
git clone https://github.com/your-username/flask-hello-world.git
cd flask-hello-world

# Run locally
pip install -r requirements.txt
python app/main.py
# flask-hello-world
