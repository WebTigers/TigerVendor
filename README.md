# WebTigers/TigerVendor

The **vendor trust anchor** for WebTigers as a paid-module seller (see tiger-core `MARKETPLACE.md` §3).
A buyer's Module Manager reads `tigervendor.json` to pin the Ed25519 **public key** that WebTigers signs
its released artifacts + license verdicts with, and the `api_base` (license authority) where verify +
download happen. Distinct from **WebTigers/TigerVendors** (plural) — that's the free *Directory* catalog.

> **Bring-up note:** `api_base` currently points at the **dev-com** authority (the WebTigers dev *seller*
> instance) while the paid single-buy loop is being brought up. Repoint to the production
> `webtigers.com` authority once that store is live. The `public_key` is dev-com's authority signing key.
