# Incident Trend Analysis Template

**Period:** [e.g. H1 2025 / Full Year 2024 / Rolling 12 Months]
**Prepared by:** [SOC Manager]
**Date:** [Date]
**Classification:** CONFIDENTIAL — Internal Use Only

---

## Purpose

This template structures a recurring analysis of security incident trends to identify patterns, measure SOC performance over time, and surface systemic risks before they become critical. Complete this analysis quarterly at minimum; monthly for organisations with high incident volume.

---

## 1. Incident Volume Trends

### 1.1 Monthly Incident Count

| Month | P1 | P2 | P3 | P4 | Total | vs. Prior Month |
|-------|----|----|----|----|-------|----------------|
| Jan | | | | | | |
| Feb | | | | | | |
| Mar | | | | | | |
| Apr | | | | | | |
| May | | | | | | |
| Jun | | | | | | |
| Jul | | | | | | |
| Aug | | | | | | |
| Sep | | | | | | |
| Oct | | | | | | |
| Nov | | | | | | |
| Dec | | | | | | |
| **Total** | | | | | | |

**Key Observations:**
- Highest volume month: [Month] ([N] incidents) — reason: ___
- Lowest volume month: [Month] ([N] incidents) — reason: ___
- Trend: ↑ Increasing / → Stable / ↓ Decreasing

### 1.2 Year-over-Year Comparison

| Metric | [Year-2] | [Year-1] | [Year] | YoY Change |
|--------|----------|----------|--------|-----------|
| Total incidents | | | | |
| P1 incidents | | | | |
| P2 incidents | | | | |
| False positive rate | | | | |
| Mean MTTD (all) | | | | |
| Mean MTTR (all) | | | | |

---

## 2. Incident Type Breakdown

### 2.1 By Category

| Category | Count | % of Total | vs. Prior Period | Trend |
|----------|-------|------------|-----------------|-------|
| Malware / Ransomware | | | | |
| Phishing / BEC | | | | |
| Account Compromise | | | | |
| Data Exfiltration | | | | |
| Insider Threat | | | | |
| DDoS / Availability | | | | |
| Vulnerability Exploitation | | | | |
| Supply Chain | | | | |
| Other | | | | |
| **Total** | | 100% | | |

### 2.2 By Initial Access Vector

| Vector | Count | % | Notes |
|--------|-------|---|-------|
| Phishing email | | | |
| Credential stuffing / brute force | | | |
| Exploited public-facing application | | | |
| Supply chain compromise | | | |
| Insider / privileged abuse | | | |
| Physical | | | |
| Unknown | | | |

### 2.3 MITRE ATT&CK Tactic Frequency

| Tactic | Observed in N incidents | % | Top Technique |
|--------|------------------------|---|--------------|
| Initial Access (TA0001) | | | |
| Execution (TA0002) | | | |
| Persistence (TA0003) | | | |
| Privilege Escalation (TA0004) | | | |
| Defence Evasion (TA0005) | | | |
| Credential Access (TA0006) | | | |
| Discovery (TA0007) | | | |
| Lateral Movement (TA0008) | | | |
| Collection (TA0009) | | | |
| Exfiltration (TA0010) | | | |
| Impact (TA0040) | | | |

---

## 3. Response Performance Trends

### 3.1 MTTD Trend (Mean Time to Detect)

| Quarter | P1 MTTD | P2 MTTD | P3 MTTD | Overall MTTD | Target | Status |
|---------|---------|---------|---------|-------------|--------|--------|
| Q1 | | | | | P1: 15 min | |
| Q2 | | | | | P2: 30 min | |
| Q3 | | | | | P3: 2 hrs | |
| Q4 | | | | | | |

### 3.2 MTTR Trend (Mean Time to Respond/Resolve)

| Quarter | P1 MTTR | P2 MTTR | P3 MTTR | Overall MTTR | Target | Status |
|---------|---------|---------|---------|-------------|--------|--------|
| Q1 | | | | | P1: 4 hrs | |
| Q2 | | | | | P2: 24 hrs | |
| Q3 | | | | | P3: 72 hrs | |
| Q4 | | | | | | |

### 3.3 SLA Compliance Rate

| Quarter | P1 SLA % | P2 SLA % | P3 SLA % | Overall % | Target |
|---------|----------|----------|----------|-----------|--------|
| Q1 | | | | | > 95% |
| Q2 | | | | | > 95% |
| Q3 | | | | | > 95% |
| Q4 | | | | | > 95% |

**SLA Miss Root Causes (if any):**
| Date | Incident | Priority | Miss Reason | Owner | Corrective Action |
|------|----------|----------|-------------|-------|------------------|
| | | | | | |

---

## 4. Detection Source Analysis

### 4.1 How Were Incidents First Detected?

| Detection Source | Count | % | Avg MTTD |
|-----------------|-------|---|----------|
| SIEM alert (automated) | | | |
| EDR alert | | | |
| User report | | | |
| External notification (MSSP, CERT, partner) | | | |
| Threat intelligence hit | | | |
| Vulnerability scanner | | | |
| Manual SOC hunt | | | |
| Law enforcement / regulator | | | |
| Other | | | |

**Key Finding:** [e.g. "43% of P1 incidents were user-reported rather than auto-detected — detection gap in email threat vector"]

### 4.2 Detection Rule Performance

| Rule / Use Case | Fires (True+False) | True Positives | False Positive Rate | Incident Catches |
|----------------|-------------------|----------------|--------------------|--------------------|
| | | | % | |
| | | | % | |
| | | | % | |

**Rules to tune (FP rate > 60%):**
- [ ] ___
- [ ] ___

**Coverage gaps identified:**
- [ ] ___
- [ ] ___

---

## 5. Affected Assets and Business Impact

### 5.1 Most Targeted Asset Types

| Asset Type | Incidents | Avg Impact Score | Business Function |
|-----------|-----------|-----------------|------------------|
| End-user workstations | | | |
| Email / collaboration | | | |
| Identity / AD / IAM | | | |
| Cloud workloads | | | |
| Network infrastructure | | | |
| Servers (on-prem) | | | |
| OT / IoT | | | |

### 5.2 Business Impact Summary

| Impact Category | Incidents with this Impact | Total Hours Lost | Est. Cost |
|-----------------|--------------------------|-----------------|-----------|
| Service downtime | | | |
| Data exposure | | | |
| Regulatory notification required | | | |
| Reputational damage | | | |
| Financial fraud / loss | | | |

---

## 6. Recurrence & Systemic Issues

### 6.1 Repeat Incident Patterns

*Incidents with the same root cause occurring more than once indicate a systemic gap.*

| Root Cause Pattern | Occurrences | First Seen | Last Seen | Systemic Fix Applied? |
|-------------------|-------------|------------|-----------|----------------------|
| | | | | Yes / No / In Progress |

### 6.2 Recurring Vulnerabilities Exploited

| CVE / Vuln | Times Exploited | First Exploited | Patched? | Time to Patch |
|-----------|----------------|----------------|----------|---------------|
| | | | | |

---

## 7. Key Findings & Recommendations

### 7.1 Positive Trends

1. ___
2. ___
3. ___

### 7.2 Areas of Concern

| Finding | Severity | Evidence | Recommended Action | Owner | Due |
|---------|----------|----------|-------------------|-------|-----|
| | High/Med/Low | | | | |

### 7.3 Strategic Recommendations

| Recommendation | Priority | Estimated Effort | Expected Outcome |
|---------------|----------|-----------------|-----------------|
| | P1/P2/P3 | | |

---

## 8. Outlook — Next Period

**Anticipated threat trends:**
- ___

**Planned SOC improvements:**
- ___

**Metrics targets for next period:**

| Metric | Current | Target |
|--------|---------|--------|
| Overall MTTD | | |
| Overall MTTR | | |
| False positive rate | | |
| Detection coverage (MITRE %) | | |
| SLA compliance | | |

---

*Template: Incident Trend Analysis | Review quarterly or after any P1 incident*
