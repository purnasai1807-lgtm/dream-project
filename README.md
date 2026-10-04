# Smart AI Driver Safety

Alcohol detection and vehicle start-authorization system.

## Structure
- `backend/` – REST API, services, models, DB
- `ai/alcohol/` – detection, calibration, thresholds, validation
- `edge/` – on-device controller, sensors, communication (API/MQTT)
- `vehicle/` – ignition authorization and vehicle interface
- `frontend/` – web dashboard and mobile apps
- `database/` – SQL schema and seed data
- `tests/` – unit, integration, API tests
- `docs/` – architecture, workflow, API, hardware, security, deployment

## Quick start
```bash
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
python run.py
```
