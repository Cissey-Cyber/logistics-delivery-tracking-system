# logistics-delivery-tracking-system

Design and implementation of a logistics and delivery tracking system using Python, Flask, SQLite, OSRM with coordinate-based nearest-neighbour fallback from depot, Brevo email, JWT + API key auth, rate limiting (429), and Render deployment.

## Live Links
- Main App: https://logistics-tracking-system.onrender.com
- Notify Service: https://logistics-notify-service.onrender.com
- Dashboard: https://github.com/Cissey-Cyber/logistics-delivery-tracking-system/projects

## Supervisor Corrections
- OSRM + coordinate-based nearest-neighbour fallback from depot
- Render hosting (2 services + 1GB disk, Gunicorn, HTTPS, cron 5min)
- Brevo email, UNIQUE constraint for duplicates
- Rate limiting 429 + retry with max 3 attempts
- 33 tests including load test 95%<2s, token tampering, HTTPS check

## Interview
Mr. Daniel Okoro, Wuse courier, 3 Nov 2026

## Run
pip install -r requirements.txt
flask run
