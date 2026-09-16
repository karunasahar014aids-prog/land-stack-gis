# LAND STACK — Integrated GIS-based Digital Public Infrastructure for Land Governance

SIH 2026 prototype for a parcel-centric, interoperable Land Stack.

## Core idea
**One Parcel → One ULPIN → Every Land Record → One Integrated View**

The prototype demonstrates how cadastral maps, RoR, registration, property tax, zoning and restrictions can be connected through a common parcel identity and State Adapter architecture.

## Features
- Interactive GIS parcel map
- Survey-number parcel search
- Land 360° parcel view
- RoR / registration / tax / zoning tabs
- AI-assisted area mismatch detection
- Human-in-the-loop officer verification workflow
- Tamil Nadu / Bihar State Adapter concept
- Responsive UI
- GitHub Pages deployment

## Demo data
All records shown in this prototype are **synthetic demonstration data**. No real government land records are exposed.

## Suggested production stack
Frontend: Next.js / React, Tailwind, MapLibre or Leaflet  
Backend: FastAPI / Node.js  
Database: PostgreSQL + PostGIS  
Security: RBAC, API gateway, audit trail  
AI: Python, OCR, anomaly detection, satellite change analysis

## Run locally
Open `index.html` in a browser, or serve the folder with any static web server.

## Architecture
State systems → State Adapter → Common Land Schema / ULPIN → GIS + APIs → Citizen / Officer / Admin dashboards.
