# Philips Rhoguns

I build cloud platforms and delivery pipelines, data pipelines, security detections, and the Linux, database and network infrastructure underneath them. Based in Toronto. My background includes leading a York University campus physical security control-room shift, where I handled alarm triage, emergency escalation and operator training.

[Portfolio and case studies](https://rhoguns.orhogun.workers.dev/) · [LinkedIn](https://www.linkedin.com/in/philips-rhoguns-266748180/) · [Email](mailto:orhogun@gmail.com)

## Start with these projects

| Project | What I built | Proof |
|---|---|---|
| [DevSecOps Supply Chain](https://github.com/prhoguns/devsecops-supply-chain) | Five security gates (Gitleaks, Semgrep, Trivy, Checkov, tests), then keyless cosign signing, an SBOM and SLSA provenance, and promotion by digest to the GitOps repo. | [Gates proven by blocked PRs](https://github.com/prhoguns/devsecops-supply-chain#the-gates-proven-by-pull-requests) · [OpenSSF Scorecard](https://scorecard.dev/viewer/?uri=github.com/prhoguns/devsecops-supply-chain) |
| [Kubernetes GitOps Platform](https://github.com/prhoguns/kubernetes-gitops-platform) | Argo CD runs the cluster from Git: Kyverno admits only pipeline-signed images, canary releases roll back on Prometheus alerts, Terraform modules for EKS and AKS. | [35/35 end-to-end checks](https://github.com/prhoguns/kubernetes-gitops-platform#what-it-proves) |
| [Toronto Crime SQL Analytics](https://github.com/prhoguns/toronto-crime-sql-analytics) | Twenty SQL questions, generated results and a [live dashboard](https://prhoguns.github.io/toronto-crime-sql-analytics/) from City open data. | [Findings](https://github.com/prhoguns/toronto-crime-sql-analytics/blob/main/FINDINGS.md) · [Case study](https://rhoguns.orhogun.workers.dev/case-studies/toronto-crime-sql-analytics.html) |
| [Toronto Open Data Pipeline](https://github.com/prhoguns/toronto-open-data-pipeline) | CKAN extraction → PostgreSQL → 11 dbt models → Airflow, with a prototype TTC delay model. | [Run results and limitations](https://github.com/prhoguns/toronto-open-data-pipeline#results-run-of-2026-09-22) · [Case study](https://rhoguns.orhogun.workers.dev/case-studies/toronto-open-data-pipeline.html) |
| [PostgreSQL DBA Toolkit](https://github.com/prhoguns/postgres-dba-toolkit) | Primary, replica, WAL archive, diagnostics and repeatable recovery and failover drills. | [Drill output](https://github.com/prhoguns/postgres-dba-toolkit#the-two-drills) · [Case study](https://rhoguns.orhogun.workers.dev/case-studies/postgres-dba-toolkit.html) |
| [Sigma Detection Pack](https://github.com/prhoguns/sigma-detection-pack) | Eleven detection rules tested against planted positives and near-misses. | [Tests](https://github.com/prhoguns/sigma-detection-pack/blob/main/tests/test_rules_fire.py) · [Case study](https://rhoguns.orhogun.workers.dev/case-studies/sigma-detection-pack.html) |

The project READMEs include setup steps, design decisions and limitations. These are independent portfolio projects and lab builds; their results are reported with the test conditions that produced them.

## More by area

- **Cloud & platform:** [AWS Security Auto-Remediation](https://github.com/prhoguns/aws-security-auto-remediation), [Azure Toronto Data Platform](https://github.com/prhoguns/azure-toronto-data-platform)
- **Data:** [TTC Real-Time Pipeline](https://github.com/prhoguns/ttc-realtime-pipeline), [Credit Risk with MLflow](https://github.com/prhoguns/databricks-credit-risk-mlflow)
- **Security:** [SOC Alert Analytics](https://github.com/prhoguns/soc-alert-analytics), [PCAP Threat Hunting](https://github.com/prhoguns/pcap-threat-hunting), [Vulnerability Prioritization](https://github.com/prhoguns/vuln-prioritization)
- **AI tooling:** [Toronto Data MCP Server](https://github.com/prhoguns/toronto-data-mcp) (read-only MCP server with a SQL guard, least-privilege role and end-to-end protocol tests), [LLM SOC Triage](https://github.com/prhoguns/llm-soc-triage) (a planted instruction in a username closed every real intrusion; only a deterministic guard held), [Text-to-SQL Evaluation](https://github.com/prhoguns/text-to-sql-eval) (local models on 92 real questions: SQL that runs 92% of the time and is right 2%)
- **IT administration:** [Microsoft 365 Identity and Device Lab](https://github.com/prhoguns/m365-identity-lab) (PowerShell and Microsoft Graph: onboarding, offboarding, Conditional Access and Intune as code, help desk runbooks)
- **Infrastructure:** [Ansible Server Baseline](https://github.com/prhoguns/ansible-server-baseline), [Network Automation Lab](https://github.com/prhoguns/network-automation-lab), [Directory Services Lab](https://github.com/prhoguns/directory-services-lab)

CompTIA Security+ · AWS Certified DevOps Engineer – Professional · Microsoft Power Platform Developer Associate
