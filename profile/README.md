<div align="center">

<img src="logo.svg" alt="" width="96" height="96">

# ezp2p

**A truely decentralized internet**

The internet was always meant to be peer-to-peer, so we're create apps that let
you stay connected without a man in the middle.

[Website](https://www.ezp2p.org) · [Wiki](https://www.ezp2p.org/wiki/) · [Puddle Protocol](https://github.com/ezp2p/protocol)

</div>

---

### Planned Projects

| Project | What it is                                                         |
|-|-|
| Puddle  | A peer-to-peer messaging, video calling and voice calling platform |
| Pond    | Community servers comparable to platforms such as Guilded and Discord |
| Levee   | A relay for Puddle that runs on a VPS so you don't need a static IP at home |
| Drip    | A social media feed that combines YouTube and Twitter              |

### How it works

- **No Signup Requires** just run Puddle and you're in.
- **Friendships via Handshakes** your Puddle will shake hands with your friends Puddle to form a connection.
- **Encrypted End to End** all conversations are encrypted with keypairs, then transmitted via TLS.

### For Users

You can run Puddle on your laptop, desktop, home server; whatever.

You can chat directly Puddle to Puddle provided you do the required port forwarding. If you don't want to do that, then you can hide behind a Levee on a cheap VPS.

### For Admins

You can easily provide Levees for Puddle users, paid or free. They're designed to
use minimal compute and minimal storage.

You can host a Pond and have full visbility over it's usage, so that you can 
actually protect yourself from illegal activities (unlike a certain other chat 
app).

All of our binaries are written to be as resource efficient as possible, and we 
actively encourage pull requests if you have an issue.

### Get started

- **[Install Puddle](https://www.ezp2p.org/wiki/puddle/installation/)**: on a computer at home, or on a server with
  Docker (`ghcr.io/ezp2p/puddle`).
- **[Run a Pond](https://www.ezp2p.org/wiki/pond/running-a-pond/)** for your community.

### Contributing

Work happens on each repository's `dev` branch: open pull requests against `dev`. `master` takes changes only from `dev`
(or a `hotpatch/*` branch for urgent fixes). Docs for every program live in the
[website](https://github.com/ezp2p/website) repository, under `src/wiki/`.
