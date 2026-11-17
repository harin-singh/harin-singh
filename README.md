# Harinder Singh

Cloud infrastructure, Platform Engineering & SRE leader in Denver, Colorado.

I have spent 13+ years building and operating multi-account AWS environments under SOC 2 and PCI, and I am now applying AI agents to day-to-day cloud operations.

I work at the intersection of networking, security, and platform engineering:

- **Hybrid networking**: I design and troubleshoot connectivity between data centers and AWS, including routing, segmentation, hybrid DNS, and zero-trust access. My largest design connected 3 on-premises sites to 30+ VPCs
- **Cloud security and governance**: I build multi-account guardrails, identity federation, and automated remediation, and I prepare environments for audits. I've covered 40+ accounts and six SOC 2 and PCI audits.
- **Kubernetes security**: I harden clusters with least-privilege access, network isolation, policy enforcement, and image scanning before anything reaches production.
- **Platform engineering**: I build self-service infrastructure with reusable Terraform modules and GitOps delivery, then run it against SLOs with on-call, postmortems, and disaster recovery testing.
- **AI for operations**: I build agents that investigate incidents and security findings and propose fixes; with a HITL.

## Projects

Example of systems I have designed and built in production.

| Project | Status | What it does |
|---|---|---|
| [aws-incident-copilot](https://github.com/harin-singh/aws-incident-copilot) | Public | Bedrock + Strands agent that investigates EKS and ECS incidents through MCP tools, proposes fixes, and waits for human approval. Deploys to AgentCore with Terraform. |
| [aws-network-mcp](https://github.com/harin-singh/aws-network-mcp) | Public | MCP server that walks a path hop by hop and tells an assistant why A cannot reach B: route tables, Transit Gateway routes, security groups, NACLs, VPN/BGP, DNS. |
| [aws-hybrid-network-landing-zone](https://github.com/harin-singh/aws-hybrid-network-landing-zone) | Public | Terraform hub-and-spoke with segmented Transit Gateway route tables, Network Firewall inspection, hybrid DNS, and a BGP VPN to a simulated on-prem site. |
| [eks-gitops-platform](https://github.com/harin-singh/eks-gitops-platform) | Private (PR open) | EKS with Argo CD app-of-apps, Karpenter, Kyverno, Argo Rollouts canaries, and 99.9% SLO burn-rate alerts. History starts in August 2024. |

TODO: DevSecOps pipeline reference (keyless CI/CD to AWS with IaC, container, and secret scanning mapped to SOC 2 and PCI controls).

## Certifications

AWS Solutions Architect – Professional · AWS DevOps Engineer – Professional · AWS Security – Specialty · AWS Advanced Networking – Specialty · CKA · HashiCorp Terraform Associate

AWS Certified Generative AI Developer Professional (In Progress)

## Tools & services I use often

AWS, Azure, Terraform, Kubernetes, EKS, Helm, Argo CD, Python, Bash, Amazon Bedrock, MCP, Strands Agents, OpenTelemetry, CloudWatch, Datadog, GitHub Actions, Transit Gateway, Direct Connect, Zscaler, Control Tower, Security Hub, GuardDuty, Wiz, Okta, Entra ID, Kyverno, Snyk, AgentCore.

## Contact

harinder@jabal.us
