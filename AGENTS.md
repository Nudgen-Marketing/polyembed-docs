# PolyEmbed docs — agent instructions

Mintlify site published at https://docs.polyembed.io. Source of truth for product behavior is the
`polyembed` app repo; verify claims against its code before changing them.

## About this project

- Pages are MDX files with YAML frontmatter; configuration lives in `docs.json`.
- Two tabs: **Guides** (`get-started/`, `publishers/`, `install/`, `readers/`) and **Reference** (`reference/`, `policies/`).
- Every new page must be added to `docs.json` navigation.
- Preview with `mint dev`; check with `mint broken-links` and `mint validate`.

## Terminology

- "Publisher" (not customer/partner), "reader" (not user/trader) for people reading articles.
- "Widget" for the embed; "snippet" or "embed code" for the HTML; "shortcode" for WordPress.
- "Deposit wallet" for the reader's Polymarket wallet; "owner signer" or "wallet" for what they sign with.
- "pUSD", "builder code", "builder fees" as Polymarket uses them.
- Hosts: `polyembed.io` (app), `iframe.polyembed.io` (widget), `docs.polyembed.io` (docs), `demo.polyembed.io` (demo).

## Style preferences

- Active voice, second person, sentence-case headings.
- Bold for UI labels, matching the dashboard's exact text: click **Check verification**.
- Code formatting for file names, parameters, events and paths.
- No marketing language; no promises about returns. Trading pages must keep their risk callouts.

## Content boundaries

- Don't document admin-only features, internal env vars, builder secrets or self-hosting.
- Don't document the authenticated publisher REST API; it isn't a public API yet.
- Policy summaries must link to the binding documents on polyembed.io.
