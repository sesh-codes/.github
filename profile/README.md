<p align="center">
  <a href="https://sesh.codes"><img src="sesh-icon.png" width="112" height="112" alt="Sesh"></a>
</p>

<h1 align="center">Sesh</h1>

<p align="center">
  <b>Remote control for every coding agent.</b><br>
  Your agents run on your own computers. Sesh lets you start them, answer them and ship what they made from any device, wherever you are.
</p>

<p align="center">
  <a href="https://sesh.codes">Website</a> ·
  <a href="https://sesh.codes/docs/">Docs</a> ·
  <a href="https://testflight.apple.com/join/VtsK8NNX">Mac, iPhone and iPad beta</a> ·
  <a href="https://sesh.codes/#linux">Linux and Android</a> ·
  <a href="https://sesh.codes/changelog/">What's new</a>
</p>

---

**Claude Code, Codex, Cursor, Gemini CLI, OpenCode** and any [Agent Client Protocol](https://agentclientprotocol.com) agent run on a Mac, a Linux box, a cloud server or a Docker container. Sesh shows every session from every machine in one native app, on Mac, iPad, iPhone, Apple Watch, Android and Linux.

- **See which agent needs you.** Questions and permission requests come to whichever device is closest.
- **Run agents on the computer under your desk.** Reach it from any network, end-to-end encrypted, with no VPN and no ports to open.
- **A real workspace for every agent.** Each session gets its own branch and worktree, terminals, dev servers and a review of its changes.
- **Your code stays on your computers.** There's no Sesh account, and your code is never stored on a Sesh server.

### Get started

```sh
curl -fsSL https://sesh.codes/install.sh | sh                                         # on the machine the agents run on
docker run -d -v sesh-home:/home/sesh --name sesh ghcr.io/sesh-codes/sesh:claude      # or in Docker
```

Then pair it from the Sesh app. The [Getting started guide](https://sesh.codes/docs/getting-started/) walks through it.

### Here

- [**docker**](https://github.com/sesh-codes/docker): Sesh's Docker images, `ghcr.io/sesh-codes/sesh`, one per agent.

Ideas and bug reports: the [Sesh feedback board](https://userinput.app/s/did:plc:hi34a5c6rackxgvemkdbdrjy/3mwytwlmv2p2t).
