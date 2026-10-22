# RELAY KIT — Run Your Own Community Relay / Corre tu propio rele comunitario

Goal: a library, school, church, or co-op running its own Nostr relay in one afternoon.

1. **Hardware / hosting:** any VPS (2GB RAM is enough to start) or a spare small PC.
2. **Install Docker:** `curl -fsSL https://get.docker.com | sh`
3. **Clone this repo,** edit `config.toml`: set `relay_url`, `name`, `contact`, and your `pubkey`.
4. **Start it:** `docker compose up -d`
5. **Point a domain at it** (Caddy or nginx reverse proxy with TLS) so clients reach it at `wss://your-domain`.
6. **Test:** open Puerta (`puerta/index.html`), add your relay, post a note, confirm it appears.
7. **Rules to post publicly:** what the relay keeps (default: everything public), who to contact for abuse, uptime expectations.

Cost at workshop scale: ~$6–$20/month VPS. That's the whole point — no big platform needed.
