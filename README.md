# Hey, I'm Subin George

**CI/CD | PyTorch Contributor | India**

I work on CI/CD infrastructure and developer tooling for machine learning frameworks. Currently building the **Cross-Repository CI Relay (CRCR)** for PyTorch — a fully automated pipeline that triggers and tracks CI across downstream repositories whenever a PR is opened on `pytorch/pytorch`, with results flowing back to the [PyTorch CI HUD](https://hud.pytorch.org/crcr).

---

### What I'm working on

- **[Cross-Repository CI Relay (CRCR)](https://github.com/pytorch/test-infra)** — Designed and built the relay system that connects upstream PyTorch events to downstream CI across the ecosystem. Key components: Callback Lambda (OIDC verification, state machine, rate limiting), HUD integration (React dashboard pages, ClickHouse queries, API routes), on-call bot, and CI-neutral callback action (GitHub Actions + Buildkite). Co-authored [RFC-0050](https://github.com/pytorch/rfcs/blob/master/RFC-0050-Cross-Repository-CI-Relay-for-PyTorch-Out-of-Tree-Backends.md), [RFC-0054](https://github.com/pytorch/rfcs/blob/master/RFC-0054-HUD-Integration-for-Out-of-Tree-CI-Results.md), and [RFC-0056](https://github.com/pytorch/rfcs/pull/98) (Nightly & Periodic CI). 50+ PRs across 5 repositories.

- **[RHEL CI for PyTorch](https://github.com/TorchedHat/pytorch-redhat-ci)** — Built a downstream CI pipeline that builds and tests PyTorch nightly on RHEL 9.6 using `podman` containers and self-hosted runners. Includes delta-based test determination (heuristic + structural C++ call graph analysis), categorized test execution (CPU, Inductor, GPU), and CRCR integration for upstream reporting.

- **PyTorch Core Contributions** — Bug fixes and improvements across `torch.nn`, `torch.distributed`, and test infrastructure. Notable contributions include fixing softplus numerical instability, adding convolution overflow checks, and fixing OOT backend registration. 85+ PRs in `pytorch/pytorch`.

### Organizations

<a href="https://github.com/pytorch"><img src="https://img.shields.io/badge/PyTorch-contributor-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch" /></a>
<a href="https://github.com/TorchedHat"><img src="https://img.shields.io/badge/TorchedHat-member-181717?logo=github&logoColor=white" alt="TorchedHat" /></a>

### Tech

`Python` `C++` `TypeScript` `React/Next.js` `AWS Lambda` `DynamoDB` `ClickHouse` `Redis` `GitHub Actions` `Terraform` `Docker/Podman` `PyTorch`

---

<sub>Open to collaborating on PyTorch, ML infra, and open-source CI tooling.</sub>
