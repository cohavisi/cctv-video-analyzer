# CCTV Video Analyzer — Claude Instructions

## Architecture

This project is composed of multiple services:
- **Frontend (UI/UX):** React or another popular framework
- **Backend:** One or more services in Python or Go (choose based on best fit)

## Implementation Rules

- All services must be containerized and testable via `docker-compose`
- All services must have Kubernetes deployments as Helm charts, testable on minikube
- create src folder for service implementation.
- create deployment folder for deployment flows (creating PAAS resources, if needed).

## Technical Constraints

- Camera access is via local network: RTSP streams(example: rtsp://admin:123456@192.168.6.215:554/stream1), Synology Surveillance Station API, REOLINK interface or other suggested.
- Database: SQL or NoSQL — choose based on best practice for the use case
- Storage: NAS server, Azure Storage or other suggested.

## Available Cameras

- 192.168.6.215 - street view (Hiseeu IPCAM-100)
- 192.168.6.211 - back yard (Hiseeu IPCAM-100)
- 192.168.6.231 - entrance (Reolink RLC-811A)
- 192.168.6.233 - front yard (Reolink RLC-811A user:admin, password:C0havi$i)