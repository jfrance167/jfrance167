# Learning index

A route through my public projects, organized by subject. Start with the featured projects on my profile, then explore individual concepts below. Offline models, synthetic demonstrations and coursework have explicit limitations in their repository documentation; this index does not imply production readiness or verified deployments.

**Start here:** [Featured projects](README.md#start-with-these-projects) · [GitHub profile](https://github.com/jfrance167)

## Browse by subject

- [Networking and protocols](#networking-and-protocols)
- [Detection, forensics and incident response](#detection-forensics-and-incident-response)
- [Cloud and container security](#cloud-and-container-security)
- [Vulnerability management and governance](#vulnerability-management-and-governance)
- [Web, application and AI security](#web-application-and-ai-security)
- [Data formats, parsing and integrity](#data-formats-parsing-and-integrity)
- [Linux permissions and filesystem models](#linux-permissions-and-filesystem-models)
- [Distributed systems and dependency models](#distributed-systems-and-dependency-models)
- [Coursework and historical records](#coursework-and-historical-records)
- [Portfolio navigation](#portfolio-navigation)

## Networking and protocols

- [firewall-hardening-lab](https://github.com/jfrance167/firewall-hardening-lab) — Isolated Linux firewall-hardening lab with real before/after scans, nftables policy, scoped rollback, evidence validation, and CI.
- [python-tcp-port-scanner](https://github.com/jfrance167/python-tcp-port-scanner) — Educational Python TCP connect scanner for authorized practice labs with concurrent scanning, service labels, passive banners, randomized order, JSON output, timestamps, and tests.
- [network-forensics-pcap-lab](https://github.com/jfrance167/network-forensics-pcap-lab) — Synthetic PCAP generation, network intrusion detection, and DFIR investigation lab.
- [wireshark-traffic-analysis-lab](https://github.com/jfrance167/wireshark-traffic-analysis-lab) — Hands-on Wireshark lab covering DNS, TCP handshakes, TLS 1.3, ports, filters, and evidence handling.
- [fwrule](https://github.com/jfrance167/fwrule) — Firewall rule-analysis learning tool with explicit modeling limits and evidence for shadowed rules.
- [dns-cache-semantics-lab](https://github.com/jfrance167/dns-cache-semantics-lab) — Offline DNS teaching model of reusable cached answers, cached denials and fresh-query decisions.
- [firewall-counter-window-lab](https://github.com/jfrance167/firewall-counter-window-lab) — Offline model comparing synthetic firewall counter snapshots without collecting or changing rules.
- [byte-stream-framing-lab](https://github.com/jfrance167/byte-stream-framing-lab) — Offline Python lab for bounded records across split headers, payloads and coalesced byte streams.
- [internet-checksum-lab](https://github.com/jfrance167/internet-checksum-lab) — Offline Python teaching lab for Internet checksum arithmetic, residuals and guarded aligned-word updates over synthetic bytes.
- [packet-size-budget-lab](https://github.com/jfrance167/packet-size-budget-lab) — Offline Python lab explaining synthetic IP and encapsulation size budgets against a supplied MTU; no packets are sent.
- [route-selection-lab](https://github.com/jfrance167/route-selection-lab) — Offline Python model explaining longest-prefix route lookup, equal-best ambiguity and declared ECMP candidates.
- [serial-number-arithmetic-lab](https://github.com/jfrance167/serial-number-arithmetic-lab) — Offline Python RFC 1982 serial-arithmetic lab preserving undefined half-range comparisons and additions.

## Detection, forensics and incident response

- [automated-phishing-triage-toolkit](https://github.com/jfrance167/automated-phishing-triage-toolkit) — Python email parser with VirusTotal enrichment, explainable scoring, and SOC triage playbook.
- [siem-detection-engineering-lab](https://github.com/jfrance167/siem-detection-engineering-lab) — A multi-source SIEM detection engineering lab with ATT&CK-mapped alerts, sanitized evidence, automated tests, and security-hardened CI.
- [siem-logging-pipeline](https://github.com/jfrance167/siem-logging-pipeline) — Containerized SIEM logging pipeline with Grafana Alloy, Loki, LogQL detections, and a provisioned Grafana SOC dashboard.
- [ransomware-incident-response-lab](https://github.com/jfrance167/ransomware-incident-response-lab) — Synthetic ransomware detection, correlation, and incident response lab.
- [windows-event-log-investigation](https://github.com/jfrance167/windows-event-log-investigation) — Defensive Windows security lab that collects and analyzes event logs, detects suspicious activity, and generates incident timelines.
- [failed-login-detector](https://github.com/jfrance167/failed-login-detector) — Defensive Python lab that detects brute-force, password-spray, and distributed login attacks in Linux logs, Windows Event 4625 XML, live Security logs, and JSONL.
- [file-integrity-monitor](https://github.com/jfrance167/file-integrity-monitor) — Defensive Python lab that detects file content and metadata changes using SHA-256 baselines, optional HMAC protection, safe symlink handling, and automation-ready reports.
- [phishing-investigation-email-auth-lab](https://github.com/jfrance167/phishing-investigation-email-auth-lab) — Isolated SPF, DKIM and DMARC investigation lab with synthetic Postfix/Rspamd evidence and defensive analysis.
- [hybrid-enterprise-security-lab](https://github.com/jfrance167/hybrid-enterprise-security-lab) — Fictional isolated VirtualBox company operations and incident response capstone.
- [audit-policy-coverage-lab](https://github.com/jfrance167/audit-policy-coverage-lab) — Offline Python lab evaluating declared Windows auditing prerequisites while keeping effective event and alert coverage unknown.
- [event-timeline-uncertainty-lab](https://github.com/jfrance167/event-timeline-uncertainty-lab) — Offline Python lab comparing synthetic event-time envelopes while preserving clock assumptions and uncertain ordering.
- [structured-log-redaction-lab](https://github.com/jfrance167/structured-log-redaction-lab) — Offline synthetic Python lab minimizing structured events through known-field validation before log output.

## Cloud and container security

- [aws-cloudtrail-iam-detection-lab](https://github.com/jfrance167/aws-cloudtrail-iam-detection-lab) — AWS CloudTrail and IAM detection engineering lab with Terraform, EventBridge, CloudWatch, Athena, synthetic evidence, and security-focused CI.
- [container-security-hardening-lab](https://github.com/jfrance167/container-security-hardening-lab) — Policy-as-code lab for hardening Docker and Kubernetes configurations.

## Vulnerability management and governance

- [vulnerability-management-lab](https://github.com/jfrance167/vulnerability-management-lab) — Reproducible vulnerability prioritization, remediation, and closure-verification lab.
- [iso-27001-information-security-policy](https://github.com/jfrance167/iso-27001-information-security-policy) — An anonymized ISO/IEC 27001:2022 and NIST CSF 2.0 information security policy template.
- [cvss-vector-model-lab](https://github.com/jfrance167/cvss-vector-model-lab) — Offline Python model of conditional CVSS 3.1 Base scores from synthetic supplied metrics.
- [software-inventory-consistency-lab](https://github.com/jfrance167/software-inventory-consistency-lab) — Offline Python lab checking synthetic inventory references and assertions; it does not discover software or validate SPDX/CycloneDX.

## Web, application and AI security

- [web-access-control-security-lab](https://github.com/jfrance167/web-access-control-security-lab) — Safe broken-access-control lab with secure RBAC, ownership, and tenant isolation.
- [owasp-juice-shop-top-10-lab](https://github.com/jfrance167/owasp-juice-shop-top-10-lab) — Hands-on OWASP Juice Shop lab report mapping completed vulnerability exercises to the OWASP Top 10:2025.
- [secure-calculator](https://github.com/jfrance167/secure-calculator) — Secure, extensible Python calculator with Decimal arithmetic, strict validation, fuzz testing, Docker hardening, and CI.
- [crystal](https://github.com/jfrance167/crystal) — Synthetic API-key rotation learning lab with a local dashboard and simulated lifecycle events.
- [ctf-tryhackme-writeups](https://github.com/jfrance167/ctf-tryhackme-writeups) — Structured TryHackMe walkthroughs and packet-analysis methodology with defensive mitigations.
- [ai-tool-policy-lab](https://github.com/jfrance167/ai-tool-policy-lab) — Python learning lab showing how trusted application permissions constrain AI tool actions.
- [llm-prompt-injection-firewall](https://github.com/jfrance167/llm-prompt-injection-firewall) — Local mock-LLM gateway lab separating fallible content screening from enforced permissions for simulated tools.
- [local-llm-security-lab](https://github.com/jfrance167/local-llm-security-lab) — Bounded local LLM prompt-injection lab with Garak, strict evidence analysis, and supervised agent evaluation.
- [cookie-scoping-policy-lab](https://github.com/jfrance167/cookie-scoping-policy-lab) — Offline Python teaching model for synthetic stored-cookie scope with explicit unknowns and reproducible security checks.
- [cors-preflight-policy-lab](https://github.com/jfrance167/cors-preflight-policy-lab) — Offline CORS model separating request transmission, response visibility and intended origin policy.
- [http-cache-semantics-lab](https://github.com/jfrance167/http-cache-semantics-lab) — Python teaching model of shared-cache storage, matching, freshness and intended sharing.
- [http-media-negotiation-lab](https://github.com/jfrance167/http-media-negotiation-lab) — Offline HTTP media negotiation model explaining preference specificity and candidate quality.
- [http-precondition-lab](https://github.com/jfrance167/http-precondition-lab) — Offline Python model of origin-side HTTP preconditions over declared synthetic snapshots.
- [http-redirect-policy-lab](https://github.com/jfrance167/http-redirect-policy-lab) — Offline Python lab explaining redirect methods, body replay policy, blockers, and uncertainty.
- [http-byte-range-lab](https://github.com/jfrance167/http-byte-range-lab) — Offline Python model of single-range byte geometry and declared HTTP server handling.
- [csv-formula-boundary-lab](https://github.com/jfrance167/csv-formula-boundary-lab) — Python learning lab comparing CSV quoting with data-changing apostrophe-prefix demonstrations.

## Data formats, parsing and integrity

- [binary-analysis-workbench](https://github.com/jfrance167/binary-analysis-workbench) — An offline static PE and ELF analysis workbench with Ghidra-backed evidence and inert reports.
- [archive-metadata-risk-lab](https://github.com/jfrance167/archive-metadata-risk-lab) — Inspect synthetic ZIP metadata risks without extracting or decompressing archive members.
- [pickle-opcode-inspector](https://github.com/jfrance167/pickle-opcode-inspector) — Learning CLI that explains Python pickle instructions without restoring objects; decoded instructions do not establish safe deserialization.
- [json-canonicalization-lab](https://github.com/jfrance167/json-canonicalization-lab) — Offline JSON comparison lab using an explicitly restricted integer canonicalization profile; byte equality does not authenticate origin.
- [json-merge-patch-lab](https://github.com/jfrance167/json-merge-patch-lab) — Offline Python lab explaining JSON Merge Patch deletion, root replacement and whole-array replacement on synthetic values.
- [json-patch-transaction-lab](https://github.com/jfrance167/json-patch-transaction-lab) — Offline Python JSON Patch lab demonstrating ordered operations, preconditions and rollback of a private working value.
- [json-pointer-resolution-lab](https://github.com/jfrance167/json-pointer-resolution-lab) — Offline Python lab resolving bounded JSON Pointers while distinguishing missing values from present null, false and zero.
- [json-schema-subset-lab](https://github.com/jfrance167/json-schema-subset-lab) — Offline Python learning lab explaining five JSON Schema keywords and explicitly unassessed unsupported definitions.
- [unicode-identifier-policy-lab](https://github.com/jfrance167/unicode-identifier-policy-lab) — Offline Python lab comparing synthetic Unicode strings under explicit normalization policies and explaining induced collisions.
- [merkle-transparency-proof-lab](https://github.com/jfrance167/merkle-transparency-proof-lab) — Offline Python lab for Merkle inclusion and append-only consistency proofs against supplied roots; roots remain unauthenticated.
- [sarif-location-model-lab](https://github.com/jfrance167/sarif-location-model-lab) — Offline Python lab interpreting synthetic SARIF location provenance and column units without opening named artifacts.

## Linux permissions and filesystem models

- [linux-permission-model-lab](https://github.com/jfrance167/linux-permission-model-lab) — Offline Python model of ordinary Linux mode selection and ancestor search checks; actual host access remains unverified.
- [linux-acl-evaluation-lab](https://github.com/jfrance167/linux-acl-evaluation-lab) — Offline Python model explaining Linux access-ACL selection and masks using invented IDs; actual host access remains unverified.
- [linux-creation-mask-lab](https://github.com/jfrance167/linux-creation-mask-lab) — Offline Python lab deriving mode bits from invented requested modes and masks without creating files or changing host permissions.
- [linux-sticky-directory-lab](https://github.com/jfrance167/linux-sticky-directory-lab) — Offline Python model distinguishing sticky-directory removal predicates from file-content permissions using invented declarations.
- [filesystem-link-lifecycle-lab](https://github.com/jfrance167/filesystem-link-lifecycle-lab) — Educational Python ledger distinguishing filesystem names, identities and open references.
- [filesystem-rename-model-lab](https://github.com/jfrance167/filesystem-rename-model-lab) — Bounded Python ordinary-rename namespace model with independent oracles and security checks.

## Distributed systems and dependency models

- [bounded-queue-admission-lab](https://github.com/jfrance167/bounded-queue-admission-lab) — Offline Python model of finite FIFO waiting capacity and separately owned service slots.
- [circuit-breaker-transition-lab](https://github.com/jfrance167/circuit-breaker-transition-lab) — Offline Python model of circuit-breaker admission and recovery using invented event records.
- [lease-fencing-model-lab](https://github.com/jfrance167/lease-fencing-model-lab) — Offline Python model of numeric fencing-token admission; lease validity, holder identity and real enforcement remain unverified.
- [rate-limit-admission-lab](https://github.com/jfrance167/rate-limit-admission-lab) — Offline Python model comparing token-bucket and fixed-window admission with invented timestamps, costs and identity labels.
- [retry-idempotency-lab](https://github.com/jfrance167/retry-idempotency-lab) — Offline synthetic retry and idempotency model: separate attempts, effects and client observations.
- [dependency-constraint-lab](https://github.com/jfrance167/dependency-constraint-lab) — Offline SemVer constraint model explaining which invented candidates satisfy explicit endpoints.
- [finite-dependency-resolution-lab](https://github.com/jfrance167/finite-dependency-resolution-lab) — A bounded, evidence-tested finite dependency resolution lab using Python standard-library code.
- [version-precedence-lab](https://github.com/jfrance167/version-precedence-lab) — Offline Python SemVer learning lab distinguishing precedence equality from literal equality with explanatory comparison rules.

## Coursework and historical records

These retain course artifacts and learning history. The VM lab is documented as incomplete; the inter-VNet repository is a coursework fork, and the early Lab 1 setup record is archived.

- [challenge-lab01-jf](https://github.com/jfrance167/challenge-lab01-jf) — Azure storage challenge-lab coursework with a hardened StorageV2 ARM template and lifecycle management.
- [lab01-arm-jf](https://github.com/jfrance167/lab01-arm-jf) — Azure ARM coursework lab covering StorageV2, private blob access, lifecycle rules, and access testing.
- [lab02-virtual-networking-jf](https://github.com/jfrance167/lab02-virtual-networking-jf) — Azure virtual-networking coursework archive covering VNets, subnets, ARM exports, and Git workflows.
- [lab03-virtual-machines](https://github.com/jfrance167/lab03-virtual-machines) (incomplete coursework) — Incomplete Azure virtual-machine coursework archive with ARM export artifacts and networking planning.
- [lab04-intervnet-5183](https://github.com/jfrance167/lab04-intervnet-5183) (coursework fork) — Azure inter-VNet connectivity coursework archive with ARM templates, Bastion, and virtual-machine networking.
- [-lab01-arm-jf](https://github.com/jfrance167/-lab01-arm-jf) (archived) — Archived early Azure coursework setup record; completed Lab 1 artifacts are in lab01-arm-jf.

## Portfolio navigation

- [jfrance167](https://github.com/jfrance167/jfrance167) — Cybersecurity, networking, and systems administration portfolio — Jacob Franciosa.

## Evidence and attribution

For setup, commands, dated validation, dependencies, licenses, borrowed-code attribution and AI-assistance details, read each repository’s documentation. Synthetic samples demonstrate behavior under stated assumptions; historical validation is not a current CI guarantee. The profile’s featured projects retain their links to detailed evidence.

[Return to profile](README.md)
