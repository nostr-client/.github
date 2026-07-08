# ▲ nostr-client

**A nostr client built as independent, swappable parts.** Vanilla JavaScript,
no build step, no bundler, no framework. One repo, one thing. Everything
serves its own live demo from GitHub Pages. AGPL.

**Start here → https://nostr-client.github.io/** · try
[micro](https://nostr-client.github.io/micro/), a whole client composed from
the parts · read [the contract](https://github.com/nostr-client/nostr-client.github.io/blob/gh-pages/CONTRACT.md)

| kernel | components | composed |
|---|---|---|
| [pool](https://github.com/nostr-client/pool) | [login](https://github.com/nostr-client/login) | [micro](https://github.com/nostr-client/micro) |
| [nip19](https://github.com/nostr-client/nip19) | [profile-editor](https://github.com/nostr-client/profile-editor) | |
| [did](https://github.com/nostr-client/did) | [feed](https://github.com/nostr-client/feed) | |
| | [composer](https://github.com/nostr-client/composer) | |

The rules: hex pubkeys are the primitive (npub is display-only) · one shared
relay pool per page · NIP-07-shaped signers · plain `nostr:*` DOM events ·
swap any part by changing one URL.
