# Nuntia for Obsidian – beta

Beta builds of **Nuntia**: real-time sync for Obsidian vaults across macOS and iOS, with an optional AI connection (MCP) to your notes. [nuntia.app](https://nuntia.app)

This repository holds only the built plugin (releases). The source code lives in a separate repository and will be published later.

> **Beta, by invitation only.** Back up your vault before you connect it – copy the whole vault folder somewhere else.

## Install with BRAT

1. In Obsidian, install **BRAT** from Community plugins and enable it.
2. BRAT → **Add beta plugin** → enter `msigut/nuntia-beta` → Add plugin.
3. Enable **Nuntia** in Community plugins and follow its connect steps.

BRAT keeps the plugin up to date with new releases here.

## Disclosures

- **Account required.** Nuntia is a sync service; the beta needs an invitation and an account at nuntia.app.
- **Network use.** The plugin connects to the Nuntia service (Cloudflare Workers, Durable Objects and R2 in the EU) to sync your notes and attachments between your devices.
- **Diagnostics in the beta version.** Every few minutes the beta build sends the Nuntia server how long saving changes took, the ping round trip, catching up after connecting and the plugin's own error codes (for example "writing to disk failed") – never note contents or file names; kept 30 days. Turn it off under Settings → Nuntia → Diagnostics → "Send diagnostics (beta)". "Report a problem" sends a report only when you press Send.
- **Payments.** Free during the beta.
- **Privacy policy:** [nuntia.app/privacy](https://nuntia.app/privacy).

## License

MIT – see [LICENSE](LICENSE).
