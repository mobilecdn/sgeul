# SGEUL (Story AI) on TwelveLabs

Deployment archive for sgeul.com: a Vionlabs-class media intelligence suite built on TwelveLabs Marengo and Pegasus
(Editorial, Creative, Operations and Discovery Labs, REST API, MCP server with 29 tools, ad-creative fit, stitched previews).

`twelve-studio-v8.tgz` contains the source, prebuilt bundles and `deploy/` (install script, nginx, systemd, env template).
`cloud-init.yaml` bootstraps an Ubuntu 24.04 server from this repository in one boot.

Run locally: unpack, `npm ci --omit=dev --ignore-scripts`, `node apps/api/dist/server.js`, open http://localhost:8787.
