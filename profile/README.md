<p align="center">
  <img src="logo.png" width="120" height="120" alt="Perch Nest">
</p>

<h1 align="center">Perch Nest</h1>

<p align="center">
  <b>Your Mac or your Windows PC, from any browser.</b><br>
  Screen, sound, mouse and keyboard, from a phone, a tablet or another computer.<br>
  Free and open source. No account, and no servers in between.
</p>

<p align="center">
  <a href="https://perch-nest.github.io">Website</a> ·
  <a href="https://github.com/Just-Rice/perch">Perch</a> ·
  <a href="https://github.com/faarisaahmed/roost">Roost</a> ·
  <a href="https://github.com/perch-nest/perch-nest.github.io/blob/main/DESIGN.md">Design</a>
</p>

---

## Two projects, one home

| | | |
|---|---|---|
| 🍏 **[Perch](https://github.com/Just-Rice/perch)** | for **macOS** | The original, created by **[Just-Rice](https://github.com/Just-Rice)**. A menu bar app in Swift, with the protocol, sign-in, security model and relays that everything here is built on. |
| 🪟 **[Roost](https://github.com/faarisaahmed/roost)** | for **Windows** | A Windows port of Perch: a native app in Rust, the same protocol and security, and its own look. |

**Perch Nest** brings them together: one site for both, your computers linked so a device paired once reaches all
of them, and one relay you deploy yourself for every computer you own.

## How it works

- **Direct.** Your browser and your computer find each other through sealed notes on public message servers, then
  connect directly over encrypted WebRTC. Nothing in between sees your screen.
- **Two-step sign-in, checked by your own computer.** A passkey (Face ID, Touch ID, Windows Hello), then a 6-digit
  code. Every proof is bound to its connection.
- **Strict networks.** An optional relay in your own free Cloudflare account carries the connection over ordinary
  HTTPS where WebRTC is blocked.

## Credit where it's due

Perch Nest exists because of **Perch** and its creator, **[Just-Rice](https://github.com/Just-Rice)**, who designed
and built its core: the sign-in and its security, the way devices find their computers, the direct connection, the
relays and the viewer. Roost and Perch Nest build on that work, under the same Apache 2.0 licence.

## Get involved

Bug reports and ideas are welcome on each project: [Perch issues](https://github.com/Just-Rice/perch/issues) ·
[Roost issues](https://github.com/faarisaahmed/roost/issues). Security problems: please follow each project's
`SECURITY.md` rather than opening a public issue.
