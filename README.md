# Hi 👋

I'm Samuele, based in Italy. I care about **digital ownership** and about
software that answers to the person running it: what you buy should stay
yours, and what you run should run on your own machines.

In practice that means two things. **[attest](https://github.com/bernalli/attest)**,
an open standard for cryptographically-signed, buyer-held purchase receipts
that outlive the store which issued them — specified down to an Internet-Draft,
with two independent verifier implementations. And a shelf of small,
**self-hosted, privacy-first** tools in Python — Telegram bots, scraping
pipelines, quantitative tooling — built to run without cloud, SaaS, or
third-party data sharing.

### 📐 Open standard

| Project | What it is |
| --- | --- |
| **[attest](https://github.com/bernalli/attest)** | An open standard + reference implementation for cryptographically-signed, buyer-held digital purchase receipts — verifiable **offline**, that outlive the store which issued them. No wallet, no blockchain, no server that has to stay alive. Python + TypeScript verifiers, Apache-2.0. |

### 🔧 Open projects

| Project | What it does |
| --- | --- |
| **[price-tracker-bot](https://github.com/bernalli/price-tracker-bot)** | Self-hosted Telegram bot for multi-site price tracking: auto-quarantine of broken scrapers, fine-grained notification preferences, Prometheus metrics, and a plugin architecture for adding new sites. |
| **[parcel-tracker-bot](https://github.com/bernalli/parcel-tracker-bot)** | Self-hosted Telegram bot tracking parcels across 24+ couriers worldwide: carrier auto-detect, offline route maps rendered without a geocoding API, and the same plugin architecture. |

### 🧰 How I build

- **Python 3.11+** — type-safe (`mypy --strict`), linted (`ruff`), tested (`pytest`)
- **Self-hosting first** — hardened Docker, read-only rootfs, dropped capabilities
- **Observability** — Prometheus metrics + structured logging by default
- **Auditable** — small, readable codebases; no telemetry; secrets only via env

### 📌 Interests

`digital-ownership` · `cryptography` · `telegram-bots` · `web-scraping` ·
`self-hosted` · `observability` · `quantitative-research` · `data-engineering`

### 📫 Contact

Reach me at `bernalli@proton.me`.

---

<sub>Everything here is built to be auditable, hardened, and run without relying on SaaS.</sub>
