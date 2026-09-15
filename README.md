## Steven M. Cohn

Senior SRE / Platform Engineer in Niwot, Colorado. I keep production systems up — currently on AWS with Kubernetes, Terraform, and a preference for infrastructure that explains itself.

### Start here: [cohns-net-infra](https://github.com/steve-cohn-personal/cohns-net-infra)

The live infrastructure behind cohns.net, public by design. An AWS Organization with isolated dev/stage/prod accounts, human access through IAM Identity Center, CI through GitHub OIDC, CloudFront-fronted static sites, and a FastAPI comments service on ECS Fargate backed by Aurora Serverless v2.

There are no credentials in that repository and there never will be. Humans authenticate with short-lived SSO credentials; CI holds no secret at all.

Worth reading if you are evaluating me:

- [docs/observability.md](https://github.com/steve-cohn-personal/cohns-net-infra/blob/main/docs/observability.md) — how the platform watches itself, and what that costs
- [docs/access-strategy.md](https://github.com/steve-cohn-personal/cohns-net-infra/blob/main/docs/access-strategy.md) — the identity model
- [docs/promotion.md](https://github.com/steve-cohn-personal/cohns-net-infra/blob/main/docs/promotion.md) — how code moves dev to stage to prod

### What I work on

- **Cloud & IaC:** AWS, Terraform, Terragrunt, CloudFormation
- **Containers:** Kubernetes, EKS, Helm, Docker, ECS
- **CI/CD:** GitHub Actions, CircleCI, Jenkins
- **Observability:** Datadog, Splunk, Prometheus, Grafana
- **Regulated environments:** SOC 2, ISO 27001, FDA 21 CFR Part 11

### Elsewhere

[steve.cohns.net](https://steve.cohns.net) · [LinkedIn](https://www.linkedin.com/in/stevemcohn/)
