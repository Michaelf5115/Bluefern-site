# Bluefern site (pre-launch preview)

Static build of the Bluefern marketing site, served by Cloudflare (Workers static assets) at
https://bluefern.io. `wrangler.jsonc` publishes the `public/` folder; there is no Worker code.

Generated files only: do not edit here. The source lives in the private Bluefern repo
(`apps/site`). Rebuild with `pnpm --filter @torque/site build:preview` and copy
`apps/site/out` into `public/`.
