# kinga-infra

**Infrastructure as Code for the Kinga AI stack.** Terraform modules, Helm charts,
Kubernetes overlays, and environment profiles (local dev, shared staging, SaaS,
and sovereign country clusters: NG, KE, ZW).

## What’s Here
- 🏗 Terraform modules: VPC, K8s, object storage, metrics stack
- 🚢 Helm umbrella chart: kinga-core + Inzwa + Kweli + Kinga
- 🌍 Country overlays (`env/sovereign-ng`, `env/sovereign-ke`, `env/sovereign-zw`)
- 🧪 Local developer `docker-compose` accelerator
- 🔐 Secrets patterns (Vault/KMS stubs)
- 📈 Observability bundle (Prometheus, Grafana, Loki)

**License:** Apache-2.0 (code/config).  
**Contributing:** DCO required (`git commit -s`). PRs welcome for new cloud modules & country overlays.

> See the [kinga-docs](https://github.com/kinga-ai/kinga-docs) repo for architectural guides and environment runbooks.

