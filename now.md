# Now

## Cross-Repository CI Relay

I am working on the next operational layer of PyTorch's
[Cross-Repository CI Relay](https://hud.pytorch.org/crcr): clearer relay-health
signals, event-specific partner participation, and observable nightly
compatibility results for out-of-tree backends.

Current areas of focus:

- ensuring a stuck timeout probe exposes a failed zombie-sweeper path instead
  of disappearing from a terminal-only metric;
- allowing a partner to be visible for scheduled nightly compatibility without
  pretending it participates in every upstream pull request;
- keeping HUD summary metrics consistent with the per-repository result matrix;
- documenting the OIDC-authenticated path used by external partner CI.

The public design work and mockups live in
[subinz1/CRCR](https://github.com/subinz1/CRCR). Implementation work lands in
[pytorch/test-infra](https://github.com/pytorch/test-infra) and
[pytorch/pytorch](https://github.com/pytorch/pytorch).
