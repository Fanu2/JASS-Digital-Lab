# JASS Digital Lab

A portable, provider-independent digital software laboratory for practical desktop applications, data tools, language technology, local AI and legacy-system modernization.

## v0.1 — Portable Commerce Foundation

The first release is intentionally a static storefront. Commerce infrastructure is designed as a future layer rather than a hosting dependency.

### Principles

- Hosting-independent
- Domain-independent
- Provider-independent
- Core/application logic separated from infrastructure adapters
- Lightweight first; backend only when required
- Cloudflare is a deployment target, not an architectural dependency

## Website

The `website/` directory is a self-contained static storefront and can be hosted on Cloudflare Workers Static Assets, GitHub Pages, Netlify, Vercel, an object-storage website, or a conventional web server.

## Future commerce layers

Planned interfaces include:

- DatabaseProvider
- StorageProvider
- PaymentProvider
- EmailProvider
- LicenseProvider

These should be implemented through adapters so the core remains portable.

## Initial sections

- Products
- Services
- Legacy Software Lab
- About
- Contact
- Project Athena

## Deployment

See `docs/DEPLOYMENT.md`.

## Portability

See `docs/PORTABILITY.md`.
