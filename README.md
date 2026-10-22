# Relay Libre — by Ocotarra, Inc. (NM nonprofit, to be formed)
**Open communications for the borderlands / Comunicaciones abiertas para la frontera**

Free, open-source (MIT) Nostr infrastructure and bilingual education for rural and
Spanish-speaking communities. No platform account. No email signup. Nobody can deplatform you.

## What's in here
- `docker-compose.yml` + `config.toml` — a public Nostr relay (nostr-rs-relay) tuned for
  low-bandwidth / rural hosting. Runs on a cheap VPS or a small local box.
- `puerta/` — Puerta, a dead-simple bilingual (EN/ES) onboarding web page: create a Nostr
  key in the browser in under 5 minutes, print a paper backup card, make a first post.
- `curriculum/` — Aprende Nostr: a free 6-lesson open workbook (EN/ES) for workshops.
- `RELAY-KIT.md` — step-by-step: run your own community relay (library, school, co-op).

## Run the relay
```bash
docker compose up -d
# relay listens on ws://localhost:8080
```

## License
MIT — Ocotarra, Inc. Use it, fork it, translate it.

## Funding target
Start Small (project grant, $250,000 ask) + OpenSats ($50,000 code grant). See ../PLAN.md.
