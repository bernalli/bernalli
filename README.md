# Hi, I'm Samuele

**Privacy & ownership are the mission.** Open standards, self-hosted software,
bots: what you buy stays yours, what you hold stays yours, what you run runs on
your own machine. Everything below is open source and free of telemetry.

## Projects

- **[attest](https://github.com/bernalli/attest)** — an open standard for
  cryptographically signed, buyer-held purchase receipts that can be verified
  offline and outlive the store that issued them. Published as IETF
  Internet-Draft [draft-martinalli-open-purchase-receipts](https://datatracker.ietf.org/doc/draft-martinalli-open-purchase-receipts/),
  with independent Python and TypeScript verifiers. Apache-2.0.
- **[glaux](https://github.com/bernalli/glaux)** — a minimal, crypto-agile
  EIP-7702 smart account: one address on every EVM chain by construction,
  2-of-3 threshold, P-256 signers, sign-once/replay-many rotation. Solidity,
  TypeScript SDK, Python tooling. MIT. Unaudited reference implementation.
- **[price-tracker-bot](https://github.com/bernalli/price-tracker-bot)** — a
  self-hosted Telegram bot that tracks prices across 17 sites, with per-domain
  quarantine, notification preferences and Prometheus metrics. MIT.
- **[parcel-tracker-bot](https://github.com/bernalli/parcel-tracker-bot)** — a
  self-hosted Telegram bot that follows parcels across 30+ couriers. MIT.

## How I build

- **Solidity (Foundry)** — invariant tests, Slither and Aderyn gates in CI, deterministic deploys
- **Python 3.11+** — `mypy --strict`, `ruff`, `pytest`
- **TypeScript** — strict compiler settings, tested end to end
- **Self-hosting first** — hardened Docker: read-only rootfs, dropped capabilities, no cloud dependency

## Support

If any of this is useful to you, you can [sponsor my work](https://github.com/sponsors/bernalli).
It pays for what a solo maintainer can't cover alone: security audits, test
infrastructure, and the time to keep specs and code in step.

## Contact

`bernalli@proton.me`
