# CIS Controls v8 Audit Checklist

**Organisation:** [Your Organisation]
**Audit Period:** [Quarter/Year]
**Lead Auditor:** [Name]
**Implementation Group:** IG1 / IG2 / IG3 (circle applicable)
**Review Date:** [Date]

---

## Status Key

| Status | Meaning |
|--------|---------|
| ✅ | Implemented and evidenced |
| 🟡 | Partially implemented |
| ❌ | Not implemented |
| N/A | Not applicable to this scope |

**Implementation Groups:**
- **IG1** — Basic cyber hygiene; applicable to all organisations
- **IG2** — IG1 + additional controls for organisations handling sensitive data
- **IG3** — IG2 + advanced controls for organisations facing sophisticated threats

---

## CIS Control 1 — Inventory and Control of Enterprise Assets

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 1.1 | Establish and maintain detailed enterprise asset inventory | IG1 | ❌ | | IT |
| 1.2 | Address unauthorised assets | IG1 | ❌ | | IT |
| 1.3 | Utilise an active discovery tool | IG2 | ❌ | | IT |
| 1.4 | Use DHCP logging to update asset inventory | IG2 | ❌ | | IT |
| 1.5 | Use passive asset discovery | IG3 | ❌ | | SOC |

**Notes:** _______________

---

## CIS Control 2 — Inventory and Control of Software Assets

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 2.1 | Establish and maintain software inventory | IG1 | ❌ | | IT |
| 2.2 | Ensure authorised software is currently supported | IG1 | ❌ | | IT |
| 2.3 | Address unauthorised software | IG2 | ❌ | | IT |
| 2.4 | Utilise automated software inventory tools | IG2 | ❌ | | IT |
| 2.5 | Allowlist authorised software | IG2 | ❌ | | IT |
| 2.6 | Allowlist authorised libraries | IG3 | ❌ | | IT |
| 2.7 | Allowlist authorised scripts | IG3 | ❌ | | IT |

**Notes:** _______________

---

## CIS Control 3 — Data Protection

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 3.1 | Establish and maintain a data management process | IG1 | ❌ | | CISO |
| 3.2 | Establish and maintain a data inventory | IG1 | ❌ | | CISO |
| 3.3 | Configure data access control lists | IG1 | ❌ | | IT |
| 3.4 | Enforce data retention | IG1 | ❌ | | CISO |
| 3.5 | Securely dispose of data | IG1 | ❌ | | IT |
| 3.6 | Encrypt data on end-user devices | IG2 | ❌ | | IT |
| 3.7 | Establish and maintain a data classification scheme | IG2 | ❌ | | CISO |
| 3.8 | Document data flows | IG2 | ❌ | | CISO |
| 3.9 | Encrypt data on removable media | IG2 | ❌ | | IT |
| 3.10 | Encrypt sensitive data in transit | IG2 | ❌ | | IT |
| 3.11 | Encrypt sensitive data at rest | IG2 | ❌ | | IT |
| 3.12 | Segment data processing and storage based on sensitivity | IG3 | ❌ | | IT |
| 3.13 | Deploy a data loss prevention (DLP) solution | IG3 | ❌ | | SOC |
| 3.14 | Log sensitive data access | IG3 | ❌ | | SOC |

**Notes:** _______________

---

## CIS Control 4 — Secure Configuration of Enterprise Assets and Software

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 4.1 | Establish and maintain secure configuration process | IG1 | ❌ | | IT |
| 4.2 | Establish and maintain a secure configuration process for network infrastructure | IG1 | ❌ | | Network |
| 4.3 | Configure automatic session locking on enterprise assets | IG1 | ❌ | | IT |
| 4.4 | Implement and manage a firewall on servers | IG1 | ❌ | | Network |
| 4.5 | Implement and manage a firewall on end-user devices | IG1 | ❌ | | IT |
| 4.6 | Securely manage enterprise assets and software | IG2 | ❌ | | IT |
| 4.7 | Manage default accounts on enterprise assets | IG2 | ❌ | | IT |
| 4.8 | Uninstall or disable unnecessary services on enterprise assets | IG2 | ❌ | | IT |
| 4.9 | Configure trusted DNS servers on enterprise assets | IG2 | ❌ | | Network |
| 4.10 | Enforce automatic device lockout on portable end-user devices | IG2 | ❌ | | IT |
| 4.11 | Enforce remote wipe capability on portable end-user devices | IG2 | ❌ | | IT |
| 4.12 | Separate enterprise workspaces on mobile end-user devices | IG3 | ❌ | | IT |

**Notes:** _______________

---

## CIS Control 5 — Account Management

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 5.1 | Establish and maintain an inventory of accounts | IG1 | ❌ | | IT |
| 5.2 | Use unique passwords | IG1 | ❌ | | IT/HR |
| 5.3 | Disable dormant accounts | IG1 | ❌ | | IT |
| 5.4 | Restrict administrator privileges to dedicated administrator accounts | IG1 | ❌ | | IT |
| 5.5 | Establish and maintain an inventory of service accounts | IG2 | ❌ | | IT |
| 5.6 | Centralise account management | IG2 | ❌ | | IT |

**Notes:** _______________

---

## CIS Control 6 — Access Control Management

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 6.1 | Establish an access-granting process | IG1 | ❌ | | IT |
| 6.2 | Establish an access-revoking process | IG1 | ❌ | | IT/HR |
| 6.3 | Require MFA for externally-exposed applications | IG1 | ❌ | | IT |
| 6.4 | Require MFA for remote network access | IG2 | ❌ | | IT |
| 6.5 | Require MFA for administrative access | IG2 | ❌ | | IT |
| 6.6 | Establish and maintain an inventory of authentication and authorisation systems | IG2 | ❌ | | IT |
| 6.7 | Centralise access control | IG2 | ❌ | | IT |
| 6.8 | Define and maintain role-based access control | IG3 | ❌ | | CISO |

**Notes:** _______________

---

## CIS Control 7 — Continuous Vulnerability Management

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 7.1 | Establish and maintain vulnerability management process | IG1 | ❌ | | SOC |
| 7.2 | Establish and maintain a remediation process | IG1 | ❌ | | SOC |
| 7.3 | Perform automated OS patch management | IG1 | ❌ | | IT |
| 7.4 | Perform automated application patch management | IG1 | ❌ | | IT |
| 7.5 | Perform automated vulnerability scans of internal enterprise assets | IG2 | ❌ | | SOC |
| 7.6 | Perform automated vulnerability scans of externally-exposed enterprise assets | IG2 | ❌ | | SOC |
| 7.7 | Remediate detected vulnerabilities | IG2 | ❌ | | IT/SOC |

**Notes:** _______________

---

## CIS Control 8 — Audit Log Management

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 8.1 | Establish and maintain an audit log management process | IG1 | ❌ | | SOC |
| 8.2 | Collect audit logs | IG1 | ❌ | | SOC |
| 8.3 | Ensure adequate audit log storage | IG2 | ❌ | | SOC |
| 8.4 | Standardise time synchronisation (NTP) | IG2 | ❌ | | IT |
| 8.5 | Collect detailed audit logs | IG2 | ❌ | | SOC |
| 8.6 | Collect DNS query audit logs | IG2 | ❌ | | SOC |
| 8.7 | Collect URL request audit logs | IG2 | ❌ | | SOC |
| 8.8 | Collect command-line audit logs | IG2 | ❌ | | SOC |
| 8.9 | Centralise audit logs | IG2 | ❌ | | SOC |
| 8.10 | Retain audit logs | IG2 | ❌ | | SOC |
| 8.11 | Conduct audit log reviews | IG2 | ❌ | | SOC |
| 8.12 | Collect service provider logs | IG3 | ❌ | | SOC |

**Notes:** _______________

---

## CIS Control 10 — Malware Defences

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 10.1 | Deploy and maintain anti-malware software | IG1 | ❌ | | IT |
| 10.2 | Configure automatic anti-malware signature updates | IG1 | ❌ | | IT |
| 10.3 | Disable autorun and autoplay for removable media | IG1 | ❌ | | IT |
| 10.4 | Configure automatic anti-malware scanning of removable media | IG2 | ❌ | | IT |
| 10.5 | Enable anti-exploitation features | IG2 | ❌ | | IT |
| 10.6 | Centrally manage anti-malware software | IG2 | ❌ | | IT |
| 10.7 | Use behaviour-based anti-malware software | IG3 | ❌ | | SOC |

**Notes:** _______________

---

## CIS Control 11 — Data Recovery

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 11.1 | Establish and maintain a data recovery process | IG1 | ❌ | | IT |
| 11.2 | Perform automated backups | IG1 | ❌ | | IT |
| 11.3 | Protect recovery data | IG1 | ❌ | | IT |
| 11.4 | Establish and maintain an isolated instance of recovery data | IG2 | ❌ | | IT |
| 11.5 | Test data recovery | IG2 | ❌ | | IT |

**Notes:** _______________

---

## CIS Control 12 — Network Infrastructure Management

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 12.1 | Ensure network infrastructure is up-to-date | IG2 | ❌ | | Network |
| 12.2 | Establish and maintain a secure network architecture | IG2 | ❌ | | Network |
| 12.3 | Securely manage network infrastructure | IG2 | ❌ | | Network |
| 12.4 | Establish and maintain architecture diagram(s) | IG2 | ❌ | | Network |
| 12.5 | Centralise network authentication, authorisation, and auditing | IG2 | ❌ | | IT |
| 12.6 | Use of secure network management and communication protocols | IG2 | ❌ | | Network |
| 12.7 | Ensure remote devices utilise a VPN | IG2 | ❌ | | IT |
| 12.8 | Establish and maintain dedicated computing resources for all administrative work | IG3 | ❌ | | IT |

**Notes:** _______________

---

## CIS Control 13 — Network Monitoring and Defence

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 13.1 | Centralise security event alerting | IG2 | ❌ | | SOC |
| 13.2 | Deploy a host-based intrusion detection solution | IG2 | ❌ | | SOC |
| 13.3 | Deploy a network intrusion detection solution | IG2 | ❌ | | SOC |
| 13.4 | Perform traffic filtering between network segments | IG2 | ❌ | | Network |
| 13.5 | Manage access control for remote assets | IG2 | ❌ | | IT |
| 13.6 | Collect network traffic flow logs | IG2 | ❌ | | SOC |
| 13.7 | Deploy a host-based intrusion prevention solution | IG3 | ❌ | | SOC |
| 13.8 | Deploy a network intrusion prevention solution | IG3 | ❌ | | SOC |
| 13.9 | Deploy port-level access control | IG3 | ❌ | | Network |
| 13.10 | Perform application layer filtering | IG3 | ❌ | | Network |
| 13.11 | Tune security event alerting thresholds | IG3 | ❌ | | SOC |

**Notes:** _______________

---

## CIS Control 17 — Incident Response Management

| Sub-Control | Title | IG | Status | Evidence | Owner |
|-------------|-------|----|--------|----------|-------|
| 17.1 | Designate personnel to manage incident handling | IG1 | ❌ | | SOC Manager |
| 17.2 | Establish and maintain contact information for reporting incidents | IG1 | ❌ | | SOC Manager |
| 17.3 | Establish and maintain an enterprise process for reporting incidents | IG1 | ❌ | | SOC Manager |
| 17.4 | Establish and maintain an incident response process | IG2 | ❌ | | SOC Manager |
| 17.5 | Assign key roles and responsibilities | IG2 | ❌ | | SOC Manager |
| 17.6 | Define mechanisms for communicating during incident response | IG2 | ❌ | | SOC Manager |
| 17.7 | Conduct routine incident response exercises | IG2 | ❌ | | SOC Manager |
| 17.8 | Conduct post-incident reviews | IG2 | ❌ | | SOC Manager |
| 17.9 | Establish and maintain security incident thresholds | IG3 | ❌ | | SOC Manager |

**Notes:** _______________

---

## Audit Summary

| CIS Control | IG1 Controls | IG2 Controls | IG3 Controls | ✅ | 🟡 | ❌ |
|-------------|-------------|-------------|-------------|----|----|-----|
| 1 – Asset Inventory | 2 | 2 | 1 | 0 | 0 | 5 |
| 2 – Software Inventory | 2 | 4 | 1 | 0 | 0 | 7 |
| 3 – Data Protection | 5 | 7 | 2 | 0 | 0 | 14 |
| 4 – Secure Config | 5 | 7 | 1 | 0 | 0 | 13 |
| 5 – Account Mgmt | 4 | 2 | 0 | 0 | 0 | 6 |
| 6 – Access Control | 3 | 4 | 1 | 0 | 0 | 8 |
| 7 – Vuln Management | 4 | 3 | 0 | 0 | 0 | 7 |
| 8 – Audit Logs | 2 | 9 | 1 | 0 | 0 | 12 |
| 10 – Malware | 3 | 3 | 1 | 0 | 0 | 7 |
| 11 – Data Recovery | 3 | 2 | 0 | 0 | 0 | 5 |
| 12 – Network Infra | 0 | 7 | 1 | 0 | 0 | 8 |
| 13 – Network Defence | 0 | 6 | 5 | 0 | 0 | 11 |
| 17 – Incident Response | 3 | 5 | 1 | 0 | 0 | 9 |
| **TOTAL** | **36** | **61** | **15** | **0** | **0** | **112** |

---

## Action Items

| # | Control | Finding | Priority (CVSS) | Owner | Due Date | Status |
|---|---------|---------|-----------------|-------|----------|--------|
| 1 | | | | | | Open |

---

*Template: CIS Controls v8 | Baseline — update status as controls are implemented*
