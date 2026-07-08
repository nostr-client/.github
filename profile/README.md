# ▲ nostr-client

**A nostr client built as independent, swappable parts.** Vanilla JavaScript,
no build step, no bundler, no framework. One repo, one thing. Everything
serves its own live demo from GitHub Pages. AGPL.

**Start here → https://nostr-client.github.io/**

Try the composed clients — same parts, different grades:
**[zen](https://nostr-client.github.io/zen/)** (read only, serene) ·
**[micro](https://nostr-client.github.io/micro/)** (daily essentials) ·
**[monty](https://nostr-client.github.io/monty/)** (the full monty)

| kernel | components | composed |
|---|---|---|
| [pool](https://github.com/nostr-client/pool) | [feed](https://github.com/nostr-client/feed) · [note](https://github.com/nostr-client/note) · [thread](https://github.com/nostr-client/thread) | [zen](https://github.com/nostr-client/zen) |
| [nip19](https://github.com/nostr-client/nip19) | [login](https://github.com/nostr-client/login) · [composer](https://github.com/nostr-client/composer) · [reactions](https://github.com/nostr-client/reactions) | [micro](https://github.com/nostr-client/micro) |
| [did](https://github.com/nostr-client/did) | [contacts](https://github.com/nostr-client/contacts) · [notifications](https://github.com/nostr-client/notifications) · [search](https://github.com/nostr-client/search) | |
| [verify](https://github.com/nostr-client/verify) | [profile](https://github.com/nostr-client/profile) · [profile-editor](https://github.com/nostr-client/profile-editor) · [relay-manager](https://github.com/nostr-client/relay-manager) | |
| [theme](https://github.com/nostr-client/theme) | [nip46](https://github.com/nostr-client/nip46) | |

The rules ([the contract](https://github.com/nostr-client/nostr-client.github.io/blob/gh-pages/CONTRACT.md)):
hex pubkeys are the primitive (npub is display-only) · one shared relay pool
per page · NIP-07-shaped signers · plain `nostr:*` DOM events · swap any part
by changing one URL.
