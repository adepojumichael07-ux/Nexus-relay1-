# Nexus Relay

Offline-first emergency desk for network blackout areas.

## Run
From this folder:

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## What it does
- Incident type dropdown
- Emergency number dropdown (Nigeria / Lagos hotlines) plus a free-text number
- Location by landmark or device GPS
- Priority dropdown
- Local queue that survives refresh
- Simulated mesh relay, then cloud sync when the browser is online
- Service worker cache so the page can reopen offline after the first visit
