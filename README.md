# Harinder Singh

Cloud infrastructure, Platform Engineering & SRE leader in Denver, Colorado.
I have spent 13+ years building and operating multi-account AWS environments under SOC 2 and PCI, and I am now applying AI agents to day-to-day cloud operations.

I work at the intersection of networking, security, and platform engineering:

- Hybrid networking: Transit Gateway, Direct Connect, BGP, Route 53 Resolver, and zero-trust with Zscaler
- Security and compliance: identity federation (Okta, Entra ID) and security architecture across 40+ AWS accounts
- Platform engineering: EKS, Terraform, GitOps with Argo CD, OpenTelemetry, SLOs and SLIs
- AI for operations: Amazon Bedrock, Strands Agents, MCP, and AgentCore, with human approval before any change runs

## Projects

Clean-room reference implementations of systems I have designed in production. Nothing here is employer code.

| Project | Status | What it does |
|---|---|---|
| [aws-incident-copilot](https://github.com/harin-singh/aws-incident-copilot) | Public | Bedrock + Strands agent that investigates EKS and ECS incidents through MCP tools, proposes fixes, and waits for human approval. Deploys to AgentCore with Terraform. |
| [aws-network-mcp](https://github.com/harin-singh/aws-network-mcp) | Public | MCP server that walks a path hop by hop and tells an assistant why A cannot reach B: route tables, Transit Gateway routes, security groups, NACLs, VPN/BGP, DNS. |
| [aws-hybrid-network-landing-zone](https://github.com/harin-singh/aws-hybrid-network-landing-zone) | Public | Terraform hub-and-spoke with segmented Transit Gateway route tables, Network Firewall inspection, hybrid DNS, and a BGP VPN to a simulated on-prem site. |
| [eks-gitops-platform](https://github.com/harin-singh/eks-gitops-platform) | Private (PR open) | EKS with Argo CD app-of-apps, Karpenter, Kyverno, Argo Rollouts canaries, and 99.9% SLO burn-rate alerts. History starts in August 2024. |

TODO: DevSecOps pipeline reference (keyless CI/CD to AWS with IaC, container, and secret scanning mapped to SOC 2 and PCI controls).

## Certifications

AWS Solutions Architect – Professional · AWS DevOps Engineer – Professional · AWS Security – Specialty · AWS Advanced Networking – Specialty · CKA · HashiCorp Terraform Associate

## Tools I use often

AWS, Terraform, Kubernetes, EKS, Helm, Argo CD, Python, Bash, Amazon Bedrock, MCP, Strands Agents, OpenTelemetry, CloudWatch, Datadog, GitHub Actions

## Contact

harinder@jabal.us
