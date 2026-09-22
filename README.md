# Hey, I'm Subin George

**CI/CD & ML Infrastructure | PyTorch Contributor | Red Hat | India**

**Portfolio:** [subinz1.github.io](https://subinz1.github.io/)

I work on CI/CD infrastructure and developer tooling for machine learning frameworks. Currently building the **Cross-Repository CI Relay (CRCR)** for PyTorch — a fully automated pipeline that triggers and tracks CI across downstream repositories whenever a PR is opened on `pytorch/pytorch`, with results flowing back to the [PyTorch CI HUD](https://hud.pytorch.org/crcr).

Read what I am working on [now](now.md), browse [selected projects](projects.md),
or see my [talks](talks.md).

---

### What I'm working on

- **[Cross-Repository CI Relay (CRCR)](https://github.com/pytorch/test-infra)** — Designed and built the relay system that connects upstream PyTorch events to downstream CI across the ecosystem. Key components: Callback Lambda (OIDC verification, state machine, rate limiting), HUD integration (React dashboard pages, ClickHouse queries, API routes), on-call bot, and CI-neutral callback action (GitHub Actions + Buildkite). Co-authored [RFC-0050](https://github.com/pytorch/rfcs/blob/master/RFC-0050-Cross-Repository-CI-Relay-for-PyTorch-Out-of-Tree-Backends.md), [RFC-0054](https://github.com/pytorch/rfcs/blob/master/RFC-0054-HUD-Integration-for-Out-of-Tree-CI-Results.md), and [RFC-0056](https://github.com/pytorch/rfcs/pull/98) (Nightly & Periodic CI). 70+ PRs across 6 repositories.

- **CRCR HUD Frontend** — Built the per-repo dashboard, metrics pages, and nightly health views in React/Next.js. Includes summary cards (pass rate, timeout rate, execution time), time-range selectors, repo tenure tracking, and PR/Nightly tab navigation — all backed by ClickHouse analytical queries.

- **[RHEL CI for PyTorch](https://github.com/TorchedHat/pytorch-redhat-ci)** — Built a downstream CI pipeline that builds and tests PyTorch nightly on RHEL 9.6 using `podman` containers and self-hosted runners. Features delta-based test determination (heuristic + structural C++ call graph analysis), categorized test execution (CPU, Inductor, single-GPU, multi-GPU), Quay.io image registry, selective manual dispatch, and CRCR L2 integration for upstream HUD reporting.

- **PyTorch Core Contributions** — Bug fixes and improvements across `torch.nn`, `torch.distributed`, and test infrastructure. Notable contributions include fixing softplus numerical instability, adding convolution overflow checks, and fixing OOT backend registration. 90+ PRs in `pytorch/pytorch`.

### Organizations

<a href="https://github.com/pytorch"><img src="https://img.shields.io/badge/PyTorch-contributor-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch" /></a>
<a href="https://github.com/TorchedHat"><img src="https://img.shields.io/badge/TorchedHat-member-181717?logo=github&logoColor=white" alt="TorchedHat" /></a>

### Writing and talks

- [Introducing Cross-Repository CI Relay: Scalable CI for PyTorch's Out-of-Tree Backends](https://pytorch.org/blog/introducing-cross-repository-ci-relay-scalable-ci-for-pytorchs-out-of-tree-backends/) — Official PyTorch blog
- [Scaling PyTorch's Compatibility Promise: A Tiered Cross-Repository CI Relay for Out-of-Tree Backends](talks.md#pytorch-conference-north-america-2026) — PyTorch Conference North America 2026
- [CRCR mockups and operator documentation](https://github.com/subinz1/CRCR)
- [PyTorch CI HUD — CRCR](https://hud.pytorch.org/crcr)

### Tech

`Python` `C++` `TypeScript` `React/Next.js` `AWS Lambda` `DynamoDB` `ClickHouse` `Redis` `GitHub Actions` `Terraform` `Docker/Podman` `PyTorch`

---

<sub>Open to collaborating on PyTorch, ML infra, and open-source CI tooling.</sub>
