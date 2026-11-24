<div align="center">

<img src="logo.svg" alt="" width="96" height="96">

# ezp2p

**Chat with no servers in the middle.**

Your chats live on your own computer. Your friends' live on theirs.<br>
Nothing sits between you that can read them.

[Website](https://www.ezp2p.org) · [Wiki](https://www.ezp2p.org/wiki/) · [Puddle Protocol](https://github.com/ezp2p/protocol)

</div>

---

### What we're building

| | | Status |
|---|---|---|
| 💧 **[Puddle](https://github.com/ezp2p/puddle)** | Your own chat, on your own computer. A desktop app, or `puddled` headless in Docker; your phone connects back to it. | Usable: chats, groups, files, calls, phone pairing |
| 🌊 **[Pond](https://github.com/ezp2p/pond)** | A community server, with channels and many members. People join from their Puddle with an invite link. | Text channels |
| 🧱 **[Levee](https://github.com/ezp2p/levee)** | A relay that gives a Puddle a steady public address and holds its messages while it's offline, without being able to read them. | Design draft |
| 📜 **[Protocol](https://github.com/ezp2p/protocol)** | What every ezp2p program says on the wire, written down once, with test vectors. | First cut |

### How it works

- **You host yourself.** A Puddle runs on your machine and talks directly to your friends' Puddles.
- **Keys prove who's who.** Your identity is a key chain from a recovery phrase. Every request is signed, and every
  answer is signed back.
- **Nothing is public.** A request that fails any check gets the same `404` as a path that doesn't exist, so a stranger
  can't even tell a Puddle is there.
- **One protocol, many programs.** Each program is built in its own code and upgraded at its own pace, and they still
  understand each other.

### Get started

- **[Install Puddle](https://www.ezp2p.org/wiki/puddle/installation/)**: on a computer at home, or on a server with
  Docker (`ghcr.io/ezp2p/puddle`).
- **[Run a Pond](https://www.ezp2p.org/wiki/pond/running-a-pond/)** for your community.

### Contributing

Work happens on each repository's `dev` branch: open pull requests against `dev`. `master` takes changes only from `dev`
(or a `hotpatch/*` branch for urgent fixes). Docs for every program live in the
[website](https://github.com/ezp2p/website) repository, under `src/wiki/`.
