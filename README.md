# LEX the Husky website

The LEX the Husky website. The owner's page structure, wording, project statuses
and links were synchronized with https://lexthehusky.com/ on 14 October 2026,
while keeping the existing LEX visual style and blue brand palette.

This is a static HTML website. No installation or build step is required.

## Pages

- Home: `/`
- Ecosystem: `/ecosystem/`
- DAO: `/dao/`
- Roadmap: `/roadmap/`
- Whitepaper: `/whitepaper/`
- Community: `/community/`
- Privacy policy: `/privacy-policy/`
- Terms of service: `/terms-of-service/`

All images, shared styles (`site.css`) and the read-only live burn statistics
script (`burn-stats.js`) are in `assets/`.

Swap, buying instructions, staking, NFT staking, OG Pass, HuskyWorld, Burn Center
and the whitepaper PDF link to the owner's working website. The local DAO page
contains the owner's voting rules and links to the live DAO for current proposals
and wallet voting. Proposal totals are not copied into a static snapshot.

## Preview locally

Serve this directory with a local web server. If Python is installed:

```sh
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Hosting

Deploy the repository root to a static host that supports directory index pages.
No build command is needed; the publish directory is the repository root.

Images are hosted locally. Google Fonts and the public Cronos RPC endpoints are
external dependencies. The burn statistics refresh once a minute and show an
unavailable state with a Burn Center link if both endpoints fail.

## Source

Originally exported from the LEX the Husky Sites source at commit
`aed4766e2f35f84eb9b9232b19f78a3ed6912b07`. The owner's public pages are the
reference for the current copy and ordering. The previously removed archived
ProsperaCraft project remains omitted.

This repository contains the website files and does not include Sites-specific
hosting metadata or generated duplicate output.
