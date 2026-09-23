# Deployment

## Cloudflare Workers Static Assets

The first deployment target is Cloudflare.

Recommended configuration:

- Root directory: `/`
- Build command: `exit 0`
- Deploy command: `npx wrangler deploy`
- Static asset directory: `./website`

If the repository contains Python or other unrelated dependency files, automatic dependency installation can be disabled in the Workers Build settings with `SKIP_DEPENDENCY_INSTALL=1`.

## Other hosts

The `website/` directory is self-contained and can be deployed to another static hosting provider without changing the site content.
