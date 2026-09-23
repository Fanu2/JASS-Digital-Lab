# Portability

Portability is a first-class requirement.

The application must be deployable to more than one hosting environment without redesigning the domain model or storefront.

Potential targets include:

- Cloudflare Workers Static Assets
- GitHub Pages
- Netlify
- Vercel
- object storage/static hosting
- Docker
- conventional VPS/web server

Domain names must be configuration values rather than hard-coded application assumptions.

The first Cloudflare deployment should therefore be treated as deployment target #1, not as a permanent platform dependency.
