# ▲ nostr-client

**A nostr client built as independent, swappable parts.** Vanilla JavaScript,
no build step, no bundler, no framework. One repo, one thing. Everything
serves its own live demo from GitHub Pages. AGPL.

**Start here → https://nostr-client.github.io/** · new to nostr?
**[join in 60 seconds](https://nostr-client.github.io/starter/)**

**Ten clients from the same parts:**
[zen](https://nostr-client.github.io/zen/) (read only) ·
[reader](https://nostr-client.github.io/reader/) (long-form) ·
[micro](https://nostr-client.github.io/micro/) (daily) ·
[monty](https://nostr-client.github.io/monty/) (everything) ·
[**btcnostr**](https://nostr-client.github.io/btcnostr/) (bitcoin meets social — built-in wallet, on-chain tips) ·
and the replica gallery: [skyline](https://nostr-client.github.io/skyline/) 🦋 ·
[birdsite](https://nostr-client.github.io/birdsite/) 𝕏 ·
[dittly](https://nostr-client.github.io/dittly/) 🐘 ·
[bookface](https://nostr-client.github.io/bookface/) 📘 ·
[jumbly](https://nostr-client.github.io/jumbly/) 🪩

| kernel | components | money |
|---|---|---|
| [pool](https://github.com/nostr-client/pool) · [nip19](https://github.com/nostr-client/nip19) · [did](https://github.com/nostr-client/did) | [feed](https://github.com/nostr-client/feed) · [note](https://github.com/nostr-client/note) · [thread](https://github.com/nostr-client/thread) · [composer](https://github.com/nostr-client/composer) | [wallet](https://github.com/nostr-client/wallet) — in-browser BTC (testnet4/mainnet) |
| [verify](https://github.com/nostr-client/verify) · [cache](https://github.com/nostr-client/cache) · [theme](https://github.com/nostr-client/theme) | [login](https://github.com/nostr-client/login) · [reactions](https://github.com/nostr-client/reactions) · [contacts](https://github.com/nostr-client/contacts) · [notifications](https://github.com/nostr-client/notifications) | [tip](https://github.com/nostr-client/tip) — QR on-chain tips |
| | [profile](https://github.com/nostr-client/profile) · [profile-editor](https://github.com/nostr-client/profile-editor) · [search](https://github.com/nostr-client/search) · [relay-manager](https://github.com/nostr-client/relay-manager) · [article](https://github.com/nostr-client/article) · [nip46](https://github.com/nostr-client/nip46) | |

Extras: [starter](https://github.com/nostr-client/starter) ·
[embed](https://github.com/nostr-client/embed) ·
[pulse](https://github.com/nostr-client/pulse)

The rules ([the contract](https://github.com/nostr-client/nostr-client.github.io/blob/gh-pages/CONTRACT.md)):
hex pubkeys are the primitive · one shared relay pool per page · NIP-07-shaped
signers · plain `nostr:*` DOM events · swap any part by changing one URL.
