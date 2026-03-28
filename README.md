# CCTV Video Analyzer

A system to monitor CCTV streams and record human and vehicle details for home surveillance purposes.

## Features

- **Human detection:** faces, height, velocity, and sound
- **Vehicle detection:** license plate, color, and model

## System Overview

The system connects to local network cameras via:
- RTSP streams
- Synology Surveillance Station API
- REOLINK camera interface (where available)

Detected data is stored in a database (SQL or NoSQL) and media can be stored on a NAS server or Azure Storage.
