# Regulate

Regulate is a local-first Progressive Web App for tracking activation, observable reactions, recovery, sleep, and regulation attempts.

Its signature feature is **Kill Switch**: a deliberately low-cognitive-load regulation interface designed for moments when a normally capable person may be temporarily flooded, angry, crying, visually blurred, exhausted, overstimulated, or otherwise unable to comfortably use a conventional app UI.

## Product principles

- **Regulate now. Analyze later.**
- **Touch > reading.**
- **Self-report stays authoritative.**
- **No shame language.**
- **Privacy by default.**
- **Accessibility includes temporary impairment.**

## Current prototype

- Activation gauge using a blue → violet → blood-red continuum
- Kill Switch hold-to-regulate interaction
- 4-second inhale / 6-second exhale cadence
- Vibration cues when supported
- Pause on finger release; resume on touch
- Structured reaction logging
- Sleep tracking
- History and summary metrics
- CSV export and JSON backup/import
- Offline PWA support

## Run locally

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Status

Early prototype / active design exploration.
