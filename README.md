# IQX documentation

Source for [docs.iqx.dev](https://docs.iqx.dev/introduction), published with Mintlify.

## Preview and check

Use Node.js 24 LTS (see `.nvmrc`). Mintlify does not support Node.js 25.

```sh
npm ci
npm run dev
npm run check
```

The preview runs on port 3100. `npm run check` validates the Mintlify build and checks internal links.

## Editing

- Each navigable guide is an MDX file registered in `docs.json`.
- Give every page a unique title and useful description. Link related workflows.
- Confirm product instructions against current behavior before publishing. A marketing label or a visible setup panel alone does not establish an implemented end-to-end feature.
- Check model access and prices against the current catalog. The model picker, account configuration and checkout determine effective availability, rates and tax.
- Keep secrets, customer data and private implementation details out of this public repository.
- Use Mintlify components and verify light, dark and mobile rendering when changing layout.

The September 11, 2026 content review covers 25 guides. It distinguishes documentation MCP from project integrations, Figma account connections from import-tool configuration, and mobile publishing setup from completed store submission.

## Branding

The logos and favicon in `images/` are official IQX brand assets copied from the platform. `social-card.png` is the IQX branded 1200 × 630 sharing card. These assets do not claim to be product screenshots.

## Publishing

Open a pull request with the intended content changes and validation results. Review the Mintlify preview when available. The connected production branch is `main`; verify the live page and documentation index after a merge rather than assuming a successful Git update means publication is complete.
