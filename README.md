🚨 Incident Monitoring & Alert System
Python • FastAPI • SQLite • Background Worker • Docker

A production-style incident monitoring system that ingests system events (CPU, memory, packet loss, HTTP 5xx), detects anomalies, auto-creates incidents, and exposes APIs to view & resolve them.
Inspired by the internal monitoring tools used at companies like Google, AWS, and Netflix.

⭐ Features

Event ingestion API (/api/ingest)

Automatic anomaly detection

Threshold-based logic

Sliding-window logic

Incident creation pipeline

REST APIs to list & resolve incidents

Background worker scanning events every few seconds

SQLite database (lightweight + persistent)

Event simulator to generate realistic load

Containerized with Docker (deployable to EC2)
