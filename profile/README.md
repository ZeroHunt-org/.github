<p align="center">
  <a href="https://zerohunt.ai"><img src="https://zerohunt.ai/og/default.png" alt="Zero Hunt" width="720"></a>
</p>

# Zero Hunt

**Autonomous AI red team, on-premise, on private AI.**

Zero Hunt is an appliance that runs continuous penetration tests inside your network. A swarm of AI agents carries out black-box and gray-box campaigns: reconnaissance, exploitation, privilege escalation and lateral movement. The models are our own and run on the appliance, so no customer data is sent to a third-party LLM.

- **Human in the loop.** Five autonomy levels decide which actions wait for a named approver; scope and the emergency stop are enforced by the platform.
- **Proof, not estimates.** A finding the engine has not exploited is marked as unproven. Evidence is Ed25519-signed and hash-chained, so reports can be checked against what happened.
- **Compliance, worldwide.** Findings map to 34 frameworks, among them NIS2, DORA, PCI DSS, ISO 27001, NIST CSF, MAS TRM and Saudi NCA.

## Open source

| Repository | What it is |
|---|---|
| [**self-check**](https://github.com/ZeroHunt-org/self-check) | Free, read-only scripts to check your own hosts for exploited vulnerabilities (PHP2Shell CVE-2026-109618, the LiteLLM 1.107.0 compromise, the eMudhra CA keys). They run locally; nothing leaves your network. MIT. |

## Free resources

- [CISA KEV tracker](https://zerohunt.ai/cisa-kev-tracker/) — every vulnerability added to the Known Exploited Vulnerabilities catalog in the last 90 days, with due dates and analysis
- [Vulnerabilities by vendor](https://zerohunt.ai/vulnerabilities/) — our remediation write-ups grouped by vendor
- [Security research blog](https://zerohunt.ai/blog/) — exploited CVEs with a full remediation section: fixed versions, checks, compensating controls, hunting
- [Learn](https://zerohunt.ai/learn/) — guides on autonomous pentesting, exploit validation, CTEM and penetration-testing requirements by regulation

## Security

To report a vulnerability in zerohunt.ai, the appliance or code published here, write to **security@zerohunt.ai** ([security.txt](https://zerohunt.ai/.well-known/security.txt), [trust center](https://zerohunt.ai/trust/)).

## Contact

[zerohunt.ai](https://zerohunt.ai) · [Request a demo](https://zerohunt.ai/contact/?reason=demo) · [Partners](https://zerohunt.ai/partners/) · [@zerohuntai](https://x.com/zerohuntai)
