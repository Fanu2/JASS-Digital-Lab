# Architecture

JASS Digital Lab is designed around a simple separation:

Core → Interfaces → Adapters → Deployment

The core should not depend directly on Cloudflare, a payment vendor, a database vendor or a storage vendor.

## Current phase

v0.1 is static. The storefront contains no customer accounts, payment processing or private downloads.

## Future phase

When commerce is introduced, the application should expose provider interfaces for:

- database
- storage
- payments
- email
- licensing

Provider-specific implementations belong under `adapters/`.
