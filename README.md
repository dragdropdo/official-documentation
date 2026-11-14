## D3 Business API – Mintlify docs

This repository contains the Mintlify documentation configuration and content for the **D3 Business API**.

- Config: `docs.json` (navigation, theme, logos)
- Content lives at the repository root:
  - `index.mdx`, `introduction.mdx`, `quickstart.mdx`
  - `business-api/*` – core Business API concepts and endpoints (auth, upload, operations, status, webhooks, MCP clients)
  - `sdks/*` – official client usage for Node.js, Python, PHP, Ruby, Go and Java

Pages are added by creating an `.mdx` file with `title` and `description` frontmatter and listing it under the right group in `docs.json`.

To preview or deploy these docs with Mintlify, follow the Mintlify quickstart and point it at this repository as your documentation source: [`https://www.mintlify.com/docs`](https://www.mintlify.com/docs).
