![Version](https://img.shields.io/badge/Version-v0.20.3-red)
# ragflow-arm64
This repository aims to solve the arm64 compatibility issue of RAGFlow on Apple M-chip Mac.

# Usage
## Step 1: Pull RAGFlow Docker image
docker pull 0xgkd/ragflow-arm64:v0.20.3

## Step 2: Set the RAGFlow Docker image to custom image
vim docker/.env
RAGFLOW_IMAGE=0xgkd/ragflow-arm64:v0.20.3

## Step 3: Run
docker compose -f docker/docker-compose.yml up -d

# Result
![image](https://github.com/0xgkd/ragflow-arm64/blob/main/success.jpg)
![image](https://github.com/0xgkd/ragflow-arm64/blob/main/system.jpg)
