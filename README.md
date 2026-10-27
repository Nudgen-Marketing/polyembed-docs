# PolyEmbed docs

Source for [docs.polyembed.io](https://docs.polyembed.io), built with [Mintlify](https://mintlify.com).

## Develop

```bash
npm i -g mint
mint dev
```

Preview at `http://localhost:3000`.

## Check

```bash
mint broken-links
mint validate
```

## Publish

Pushes to `main` deploy automatically through the Mintlify GitHub app. The custom domain
`docs.polyembed.io` is configured in the Mintlify dashboard with a `CNAME` to Mintlify.

See [AGENTS.md](AGENTS.md) for structure, terminology and style.
