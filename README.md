# Hey, I'm Subin George

**ML Infrastructure Engineer @ Red Hat** | PyTorch Contributor | India

I work on CI/CD infrastructure and developer tooling for machine learning frameworks. Currently building the **Out-of-Tree CI integration** for PyTorch's HUD — enabling third-party accelerator backends to surface their CI results alongside PyTorch's own test dashboard.

---

### What I'm working on

- **[PyTorch OOT HUD Pipeline](https://github.com/pytorch/test-infra/pull/8110)** — ClickHouse queries, API endpoints, and React dashboard pages that display out-of-tree CI results on [hud.pytorch.org](https://hud.pytorch.org). Co-authored the [RFC](https://github.com/pytorch/rfcs/pull/96) and landed the full data pipeline (DynamoDB -> ClickHouse -> Next.js frontend).

- **[PyTorch Core Contributions](https://github.com/pytorch/pytorch/pulls?q=is%3Apr+author%3Asubinz1)** — Bug fixes and improvements across `torch.nn`, `torch.distributed`, and test infrastructure. Notable contributions include fixing softplus numerical instability, adding convolution overflow checks, and fixing OOT backend registration.

- **RHEL 9.6 CI for PyTorch** — Building a self-hosted CI/CD pipeline to run PyTorch's test suite on Red Hat Enterprise Linux.

### Recent merged PRs

| Repository | PR | Description |
|---|---|---|
| `pytorch/test-infra` | [#8110](https://github.com/pytorch/test-infra/pull/8110) | OOT HUD: ClickHouse queries, utility library, and unit tests |
| `pytorch/test-infra` | [#8105](https://github.com/pytorch/test-infra/pull/8105) | ClickHouse schema for OOT workflow job table |
| `pytorch/pytorch` | [#174653](https://github.com/pytorch/pytorch/pull/174653) | Output size overflow check for convolution operations |
| `pytorch/pytorch` | [#173894](https://github.com/pytorch/pytorch/pull/173894) | Fix softplus numerical instability with large beta |
| `pytorch/pytorch` | [#173888](https://github.com/pytorch/pytorch/pull/173888) | Fix RNN example to support backward pass |
| `pytorch/pytorch` | [#171959](https://github.com/pytorch/pytorch/pull/171959) | Add `run_tests()` to elastic rendezvous test files |

### Tech

`Python` `C++` `TypeScript` `React/Next.js` `ClickHouse` `DynamoDB` `AWS Lambda` `GitHub Actions` `Terraform` `PyTorch`

### Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=subinz1&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=subinz1&layout=compact&theme=default&hide_border=true" />
</p>

---

<sub>Open to collaborating on PyTorch, ML infra, and open-source CI tooling.</sub>
