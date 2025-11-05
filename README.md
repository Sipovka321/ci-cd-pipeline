# CI/CD Pipeline Project

This project demonstrates a CI/CD pipeline using GitLab CI and Docker.

## Features
- Automated testing of Nginx container
- HTTP response code validation
- MD5 checksum verification
- Telegram notifications on failure

## Pipeline
The pipeline triggers on changes to `index.html` and:
1. Starts Nginx container
2. Tests HTTP response (200 OK)
3. Verifies content MD5 checksum
4. Sends notifications on failure

## Requirements
- Docker
- GitLab Runner
