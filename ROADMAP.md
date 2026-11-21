# Portfolio Execution Roadmap

This roadmap orders the practical build-out of all 5 repositories to maximize immediate impact for **SOC Analyst, Security Engineer, and DevSecOps** roles in **Luxembourg, Germany, France, and Belgium**.

---

## Guiding Principles

1. **Quality Over Quantity:** One fully documented lab with architecture diagrams, real lab logs, Sigma rules, and MITRE ATT&CK mappings beats ten empty folders.
2. **Strict Confidentiality:** Every log, screenshot, rule, and configuration must be produced in a personal lab or on TryHackMe/HackTheBox.
3. **Leverage Core Differentiators:** Highlight banking-grade SOC experience (SIEM, SOAR, EDR, high-availability BunkerWeb WAF, Docker, Linux) combined with 5 years of full-stack & AI/RAG software engineering.

---

## Phase 1: Primary Targets (`soc-analyst-lab` & `security-engineering-lab`)

Focus here first—these two repositories directly match SOC Analyst, Security Engineer, and DevSecOps job descriptions.

### Sprint 1 — High-Impact Foundation (Weeks 1–2)

- [ ] **`soc-analyst-lab/00-lab-setup`**: Document personal SOC home lab topology, SIEM deployment, and endpoint agent telemetry collection.
- [ ] **`security-engineering-lab/02-waf-and-web-security/bunkerweb-high-availability`**: Build and document a reproducible lab replica of a High-Availability BunkerWeb WAF deployment with Docker/Linux, custom rule tuning, and attack validation tests.
- [ ] **`soc-analyst-lab/01-alert-triage`**: Add triage methodology, 2 core playbooks (Phishing, Brute Force / Impossible Travel), and 1 complete end-to-end case study with false-positive tuning.

### Sprint 2 — Detection Engineering, SIEM & DevSecOps (Weeks 3–4)

- [ ] **`soc-analyst-lab/02-detection-engineering`**: Write 5 custom Sigma rules + SIEM correlation rules mapped to MITRE ATT&CK, complete with lab attack validation logs.
- [ ] **`security-engineering-lab/01-siem-and-logging`**: Document log pipelines, parsing/normalization, retention & hardening, and operational dashboards.
- [ ] **`security-engineering-lab/03-linux-and-docker-hardening`**: Publish CIS benchmark hardening scripts, container runtime security controls, and Trivy/Grype image scanning examples.
- [ ] **`security-engineering-lab/04-devsecops-pipeline`**: Build a working GitHub Actions security pipeline covering SAST, dependency scanning, Gitleaks secret scanning, and IaC scanning.

### Sprint 3 — IR, Threat Hunting, SOAR & IaC (Weeks 5–6)

- [ ] **`soc-analyst-lab/03-incident-response` & `04-log-analysis`**: Populate IR timelines, post-incident review, and query cheatsheets across Windows, Linux, Web Server, and Firewall logs.
- [ ] **`soc-analyst-lab/05-threat-hunting` & `07-automation-soar`**: Document 2 hypothesis-driven hunts and build Python enrichment scripts + SOAR playbooks.
- [ ] **`security-engineering-lab/05-iac` through `08-cloud-security`**: Add Docker Compose / Ansible / Terraform labs, vulnerability prioritization workflows, IAM/secrets patterns, and runbooks.

---

## Phase 2: Strong Differentiator (`agentic-ai-security`)

Your 5 years of software engineering (full-stack + AI/RAG) combined with SOC experience is a rare combination. Fill this third to stand out for modern Security Engineering & SOAR roles.

- [ ] **`05-soc-automation-agents`**: Build and evaluate a sandboxed Alert Triage & Threat Intel Enrichment Agent with strict human-in-the-loop approval and audit logging.
- [ ] **`02-prompt-injection-lab` & `03-rag-security`**: Document reproducible direct/indirect prompt injection labs, tool-abuse mitigations, and RAG access-control/retrieval filtering.
- [ ] **`01-threat-modeling`, `04-secure-agent-design`, `06-evals`, `07-guardrails`**: Complete threat models, guardrails policy-as-code, and red-team eval harnesses.

---

## Phase 3: Offensive & Purple Team Depth (`red-team-lab` & Writeups)

Fill this last to demonstrate adversary understanding that sharpens your defensive detection engineering.

- [ ] **`red-team-lab/05-purple-team`**: Map lab attack executions directly to generated telemetry and the Sigma rules created in `soc-analyst-lab`.
- [ ] **`red-team-lab/03-active-directory` & `04-web-application`**: Document AD attack paths/detections and WAF bypass testing against your lab BunkerWeb instance.
- [ ] **`soc-analyst-lab/06-tryhackme-writeups` & `red-team-lab/02-writeups`**: Add selected TryHackMe (SOC Level 1 / Level 2) and HackTheBox writeups.

---

## Phase 4: Final Polish (`abdelghani-demmouche`)

- [ ] Update profile `README.md` status badges, add certification verification links, and pin the top 4 repositories on GitHub.
