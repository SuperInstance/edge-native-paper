# edge-native-paper

![Cocapn Research](https://img.shields.io/badge/cocapn-research-blue)

Edge-Native Agent Infrastructure: Zero-Dependency Cloudflare Workers for Harsh Environments

## Paper

See [PAPER.md](./PAPER.md) for the full research paper.

The paper marks projected or unverified figures with 🔮. Claims grounded in published specs or measured data are stated plainly without a marker.

## Context

Part of the [Cocapn fleet](https://github.com/Lucineer/the-fleet) — 70 autonomous vessels.

## Related Repos

- [gravity-well-protocol](https://github.com/SuperInstance/gravity-well-protocol) — design spec for the locality-scoped gossip referenced in §2; concepts only, no implementation yet.
- [edge-compiler](https://github.com/SuperInstance/edge-compiler) — working Cloudflare Worker that compiles and quantizes agent bundles; a direct implementation of the Worker-per-vessel model described here.
- [Edge-Native](https://github.com/SuperInstance/Edge-Native) — ESP32 firmware VM and Jetson bytecode layer for edge agents; the hardware-side counterpart to this paper's cloud-edge architecture.
- [nexus-edge-runtime](https://github.com/SuperInstance/nexus-edge-runtime) — edge runtime with bytecode VM, trust engine, and wire protocol for autonomous agent coordination at the edge.

---

<i>Built with [Cocapn](https://github.com/Lucineer/cocapn-ai).</i>

Superinstance & Lucineer (DiGennaro et al.)
