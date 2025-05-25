### Architecture

INFORMANTO is structured based on a layered model:

- **Main Core** — handles event routing, permission logic, and stable features.
- **Experimental Layer** — contains feature flags, new feature testing, and dynamic modules.
- **Xero** — a standalone utility library used across various /rezrar projects, providing foundational abstraction.

All modules are designed with the ability to expand but adhere to strict internal compatibility rules. The bot operates in an environment where interaction with external APIs and configuration states is essential.

---

### Access Policy

This bot is **not open source** and is not intended for use outside the Rezrar infrastructure. If INFORMANTO appears on a third-party server where **@rezrar** is not the owner, it is considered an **unauthorized clone** or a **fake instance**.

Use of this software is governed by the following documents:

- [Privacy Policy](https://github.com/Rezrar/Informanto-csp/blob/main/privacy-policy.md)
- [Terms of Service](https://github.com/Rezrar/Informanto-csp/blob/main/terms-of-service.md)


### Invite Policy

To invite INFORMANTO to your server, use this link:

> https://canary.discord.com/oauth2/authorize?client_id=1218289674368454657

---

This project is under continuous development. Many of its features are experimental and adapted to changes in Discord’s ecosystem. INFORMANTO serves both as a tool and a testbed — designed to improve server operations through structured control and secure experimentation.
