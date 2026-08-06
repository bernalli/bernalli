# Hi 👋

I'm Samuele, based in Italy. I care about **digital ownership** and about
software that answers to the person running it: what you buy should stay
yours, what you hold should stay yours, and what you run should run on your
own machines.

Two projects carry that idea at the moment. **[attest](https://github.com/bernalli/attest)**,
an open standard for cryptographically-signed, buyer-held purchase receipts
that outlive the store which issued them. And **[glaux](https://github.com/bernalli/glaux)**,
a minimal, crypto-agile EIP-7702 smart account that keeps one address on
every EVM chain by construction.

### 📐 attest — receipts that outlive the store

| | |
| --- | --- |
| **[attest](https://github.com/bernalli/attest)** | An open standard + reference implementation for cryptographically-signed, buyer-held digital purchase receipts — verifiable **offline**, that outlive the store which issued them. No wallet, no blockchain, no server that has to stay alive. Published as IETF Internet-Draft [draft-martinalli-open-purchase-receipts-00](https://datatracker.ietf.org/doc/draft-martinalli-open-purchase-receipts/), with two independent verifier implementations (Python + TypeScript), Apache-2.0. |

### 🦉 glaux — one address, every chain

| | |
| --- | --- |
| **[glaux](https://github.com/bernalli/glaux)** | A minimal, crypto-agile **EIP-7702 smart account**: one address on every EVM chain by construction — no factories, no counterfactual deploys — with a 2-of-3 threshold on the operational path, P-256/secure-enclave signers, and sign-once/replay-many rotation. One birth blob demonstrated live on two public testnets: same account, same address, byte-identical configuration. Solidity (Foundry) + TypeScript SDK + Python tooling, MIT. Unaudited reference implementation. |

### 🧰 How I build

- **Solidity (Foundry)** — invariant testing, Slither + Aderyn gates in CI, deterministic CREATE2 deploys
- **Python 3.11+** — type-safe (`mypy --strict`), linted (`ruff`), tested (`pytest`)
- **TypeScript** — strict compiler settings, tested end to end
- **Self-hosting first** — hardened Docker, read-only rootfs, dropped capabilities
- **Auditable** — small, readable codebases; no telemetry; secrets only via env

### 📌 Interests

`digital-ownership` · `self-custody` · `cryptography` · `ethereum` ·
`account-abstraction` · `self-hosted` · `observability` · `quantitative-research`

### 📫 Contact

Reach me at `bernalli@proton.me`.

---

<sub>Everything here is built to be auditable, hardened, and run without relying on SaaS.</sub>
