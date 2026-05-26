# Quarterly Security Review — [Q# YYYY]

**Period:** [Start Date] — [End Date]
**Prepared by:** [SOC Manager Name]
**Reviewed by:** [CISO / VP Engineering]
**Distribution:** [Executive Team / Board / Stakeholders]
**Classification:** CONFIDENTIAL — Internal Use Only
**Published:** [Date]

---

## Executive Summary

> 2–3 sentences summarising the quarter's security posture, headline metrics, and any significant events or risks requiring executive attention.

**Overall Security Posture:** 🟢 Green / 🟡 Amber / 🔴 Red

| Area | Status | Change from Last Quarter |
|------|--------|------------------------|
| Threat Detection | 🟢 | ↑ Improved |
| Incident Response | 🟡 | → Stable |
| Vulnerability Management | 🟡 | ↓ Declined |
| Compliance | 🟢 | ↑ Improved |
| Security Awareness | 🟢 | → Stable |

---

## 1. SOC Operations Metrics

### 1.1 Alert Volume

| Metric | Q[N-1] | Q[N] | Target | Status |
|--------|--------|------|--------|--------|
| Total alerts generated | — | | | |
| Alerts investigated | — | | | |
| True positives | — | | | |
| False positive rate | — | | < 60% | |
| Alerts auto-closed by rules | — | | | |
| Avg alerts per analyst per day | — | | < 50 | |

### 1.2 Incident Summary

| Metric | Q[N-1] | Q[N] | Target | Status |
|--------|--------|------|--------|--------|
| Total incidents declared | — | | | |
| P1 (Critical) | — | | 0 | |
| P2 (High) | — | | < 2 | |
| P3 (Medium) | — | | | |
| P4 (Low) | — | | | |
| Incidents closed same-day | — | | > 80% | |

### 1.3 Response Time Performance

| Priority | MTTD Target | MTTD Actual | MTTR Target | MTTR Actual | SLA Met? |
|----------|-------------|-------------|-------------|-------------|---------|
| P1 | 15 min | | 4 hrs | | |
| P2 | 30 min | | 24 hrs | | |
| P3 | 2 hrs | | 72 hrs | | |
| P4 | 8 hrs | | 7 days | | |

### 1.4 Detection Coverage

| Framework | Previous Coverage | Current Coverage | Change |
|-----------|------------------|-----------------|--------|
| MITRE ATT&CK (techniques) | —% | % | |
| MITRE ATT&CK (tactics) | —% | % | |
| Custom rules in production | — | | |
| Rules tuned this quarter | — | | |
| Rules deprecated this quarter | — | | |

---

## 2. Threat Landscape

### 2.1 Top Threat Actors Targeting Our Sector

| Threat Actor | TTPs | Campaigns Observed | Relevance |
|-------------|------|--------------------|-----------|
| | | | High/Medium/Low |
| | | | |

### 2.2 Top Attack Vectors This Quarter

| Rank | Attack Vector | Incidents | % of Total | Trend |
|------|--------------|-----------|------------|-------|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |

### 2.3 Threat Intelligence Summary

- **New IOC feeds integrated:** [N]
- **IOCs ingested this quarter:** [N]
- **IOC true-positive hits:** [N]
- **Threat intelligence reports produced:** [N]
- **ISAC/ISAO sharing submissions:** [N]

---

## 3. Significant Incidents

> For each P1 or notable P2 incident this quarter. Keep to 3–5 sentences per incident. Full PIRs are linked separately.

### Incident 1: [Title]

- **Date/Time:** [Date]
- **Severity:** P[1/2]
- **Type:** [Ransomware / BEC / Data Exfiltration / etc.]
- **Impact:** [Systems affected, data involved, business impact]
- **Root Cause:** [Brief summary]
- **Resolution:** [How it was resolved]
- **PIR Link:** [Link to post-incident review]
- **Lessons Learned:** [Key takeaway]

### Incident 2: [Title]

*(repeat format above)*

---

## 4. Vulnerability Management

### 4.1 Vulnerability Inventory

| Severity | Open (Start of Quarter) | New This Quarter | Remediated | Open (End of Quarter) | % Reduction |
|----------|------------------------|-----------------|------------|-----------------------|-------------|
| Critical | | | | | |
| High | | | | | |
| Medium | | | | | |
| Low | | | | | |
| **Total** | | | | | |

### 4.2 SLA Compliance

| Severity | SLA Target | % On Time | Avg Days to Remediate |
|----------|-----------|-----------|----------------------|
| Critical | 15 days | | |
| High | 30 days | | |
| Medium | 90 days | | |
| Low | 180 days | | |

### 4.3 Outstanding Critical/High Vulnerabilities

| CVE | CVSS | System | Owner | Age (days) | Risk Accepted? | Due Date |
|-----|------|--------|-------|------------|----------------|----------|
| | | | | | | |

---

## 5. Compliance Status

### 5.1 Framework Status

| Framework | Last Assessment | Overall Status | Change |
|-----------|----------------|----------------|--------|
| ISO 27001:2022 | [Date] | 🟡 Partial | |
| CIS Controls v8 | [Date] | 🟡 Partial | |
| NIST CSF 2.0 | [Date] | 🟡 Partial | |
| GDPR / Data Protection | [Date] | 🟢 Compliant | |

### 5.2 Audit Findings Tracker

| Finding | Framework | Severity | Owner | Target Date | Status |
|---------|-----------|---------|-------|-------------|--------|
| | | | | | |

### 5.3 Policy Reviews Completed This Quarter

| Policy | Last Review | Next Review | Changes Made |
|--------|------------|------------|--------------|
| Information Security Policy | | | |
| Incident Response Policy | | | |
| Acceptable Use Policy | | | |
| Data Classification Policy | | | |

---

## 6. Security Awareness & Training

| Metric | Q[N-1] | Q[N] | Target |
|--------|--------|------|--------|
| Phishing simulation click rate | —% | % | < 5% |
| Phishing simulation report rate | —% | % | > 30% |
| Security training completion rate | —% | % | > 95% |
| Staff completing advanced training | — | | |
| Security incidents caused by human error | — | | 0 |

---

## 7. SOC Team & Capacity

| Metric | Q[N-1] | Q[N] |
|--------|--------|------|
| SOC FTE headcount | | |
| Open positions | | |
| Analyst attrition | | |
| Certifications achieved | | |
| Overtime hours (total) | | |
| Avg ticket backlog (end of quarter) | | |

---

## 8. Technology & Tooling

### 8.1 Tool Health

| Tool | Category | Health | Issues | Notes |
|------|----------|--------|--------|-------|
| [SIEM] | Detection | 🟢 | | |
| [EDR] | Endpoint | 🟢 | | |
| [Vuln Scanner] | Vuln Mgmt | 🟡 | | |
| [SOAR/Ticketing] | Response | 🟢 | | |
| [TI Platform] | Intelligence | 🟡 | | |

### 8.2 Tooling Changes This Quarter

| Tool | Change | Reason | Date |
|------|--------|--------|------|
| | Added | | |
| | Removed | | |
| | Upgraded | | |

---

## 9. Key Risks

| Risk | Likelihood | Impact | Current Mitigation | Residual Risk | Owner | Status |
|------|-----------|--------|--------------------|---------------|-------|--------|
| | High/Med/Low | High/Med/Low | | High/Med/Low | | Open |

---

## 10. Objectives Review

### Previous Quarter Objectives — Completion

| Objective | Target | Achieved | Status |
|-----------|--------|---------|--------|
| | | | ✅/🟡/❌ |

### Next Quarter Objectives

| Objective | Owner | Success Metric | Due Date |
|-----------|-------|---------------|----------|
| | | | |

---

## 11. Budget & Investment

| Category | Budget | Spent Q[N] | YTD Spend | % of Budget |
|----------|--------|-----------|-----------|-------------|
| Personnel | | | | |
| Tooling / Licences | | | | |
| Training | | | | |
| External Services | | | | |
| **Total** | | | | |

---

## Appendix

- **A:** Full incident reports / PIRs for P1 events
- **B:** Detailed vulnerability scan results
- **C:** ISO 27001 / CIS audit checklists
- **D:** Threat intelligence reports
- **E:** SOC metrics raw data

---

*Classification: CONFIDENTIAL | Quarterly SOC Review Template v1.0*
