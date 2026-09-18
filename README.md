# Cravenos Services

Static Cravenos Services website, configured for Cloudflare Workers Static Assets.

## Cloudflare Git deployment

- Build command: leave blank (or use `npx wrangler deploy`)
- Static assets directory: `public`
- The site files are in `public/`.
- `wrangler.jsonc` points Cloudflare at `./public`.

The visible website content is unchanged.
