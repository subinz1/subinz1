# Talks

## PyTorch Conference North America 2026

**Scaling PyTorch's Compatibility Promise: A Tiered Cross-Repository CI Relay
for Out-of-Tree Backends**

This lightning talk presents CRCR, the system that forwards PyTorch change
events to independently maintained backend CI and brings compatibility results
back to the PyTorch CI HUD. It covers the L1–L4 trust model, authenticated
callback flow, real-time pull-request validation, and scheduled nightly
reporting for hardware backends that need a lower-risk onboarding path.

The central idea is simple: downstream maintainers should discover a PyTorch
compatibility break while the upstream change is still actionable—not days
later during a release or manual bisection.

Related material:

- [CRCR design mockups and operator docs](https://github.com/subinz1/CRCR)
- [PyTorch CI HUD CRCR view](https://hud.pytorch.org/crcr)
- [PyTorch blog: Introducing Cross-Repository CI Relay](https://pytorch.org/blog/introducing-cross-repository-ci-relay-scalable-ci-for-pytorchs-out-of-tree-backends/)
