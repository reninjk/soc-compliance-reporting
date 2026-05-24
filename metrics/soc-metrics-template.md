# SOC Metrics & KPI Template

**Reporting Period:** _______________
**Prepared By:** _______________
**Date:** _______________

---

## How to Use This Template

1. Populate each metric from your ticketing system / SIEM at the end of each period
2. Mark trend arrows: 🔺 Worsening | 🔻 Improving | ➡️ Stable
3. Flag any metric outside target in **bold red** (use `**value**` in markdown)
4. Share with leadership using the relevant report template from `../reporting/`

---

## Section 1 — Alert & Detection Metrics

| Metric | This Period | Last Period | Target | Trend | Notes |
|--------|-------------|-------------|--------|-------|-------|
| Total Alerts Generated | | | Baseline ±20% | | |
| Alerts Investigated (L1) | | | 100% within SLA | | |
| True Positives (TP) | | | > 70% of investigated | | |
| False Positives (FP) | | | < 30% of total | | |
| False Positive Rate (%) | | | < 30% | | |
| Alerts Escalated to L2 | | | < 20% of total | | |
| Alerts Auto-Closed (automation) | | | Track for tuning | | |
| Duplicate Alerts Suppressed | | | Track for tuning | | |
| Alerts per Analyst per Day | | | 30–60 | | |

**FP Rate Formula:** (False Positives ÷ Total Alerts) × 100

---

## Section 2 — Incident Metrics

| Metric | This Period | Last Period | Target | Trend | Notes |
|--------|-------------|-------------|--------|-------|-------|
| Total Incidents Declared | | | Track trend | | |
| P1 (Critical) Incidents | | | 0 per month ideal | | |
| P2 (High) Incidents | | | < 5 per month | | |
| P3 (Medium) Incidents | | | Baseline ±20% | | |
| P4 (Low) Incidents | | | Baseline ±20% | | |
| Incidents Closed | | | 100% within SLA | | |
| Incidents Pending/Open | | | < 5% aged > 30 days | | |
| Recurring Incidents (repeat root cause) | | | 0 | | |

---

## Section 3 — Response Time Metrics (MTTD / MTTR)

| Incident Priority | MTTD Target | MTTD Actual | MTTR Target | MTTR Actual | SLA Met? |
|-------------------|-------------|-------------|-------------|-------------|----------|
| P1 — Critical | < 5 min | | < 1 hour | | |
| P2 — High | < 15 min | | < 4 hours | | |
| P3 — Medium | < 30 min | | < 24 hours | | |
| P4 — Low | < 60 min | | < 72 hours | | |
| **All Priorities (avg)** | | | | | |

> **MTTD** = Mean Time to Detect: time from event occurrence to alert firing
> **MTTR** = Mean Time to Respond: time from alert firing to incident closure

---

## Section 4 — Analyst Performance & Capacity

| Metric | This Period | Last Period | Target | Trend | Notes |
|--------|-------------|-------------|--------|-------|-------|
| Total Analyst Hours Available | | | | | |
| Hours Spent on Alert Triage | | | 50–60% of capacity | | |
| Hours Spent on Incident Response | | | 20–30% of capacity | | |
| Hours Spent on Hunting | | | 10–15% of capacity | | |
| Hours Spent on Admin/Training | | | < 15% of capacity | | |
| Analyst Utilisation Rate (%) | | | 70–85% | | |
| Overtime Hours | | | < 5% of total hours | | |
| Sick / Unplanned Absence Rate | | | Track | | |
| Training Completion Rate (%) | | | 100% annually | | |

---

## Section 5 — Vulnerability & Patch Metrics

| Metric | This Period | Last Period | Target | Trend | Notes |
|--------|-------------|-------------|--------|-------|-------|
| Critical Vulns Identified | | | 0 unpatched > 7 days | | |
| High Vulns Identified | | | 0 unpatched > 30 days | | |
| Critical Vulns Patched (%) | | | 100% within 7 days | | |
| High Vulns Patched (%) | | | 100% within 30 days | | |
| Mean Time to Patch — Critical | | | < 7 days | | |
| Mean Time to Patch — High | | | < 30 days | | |
| Vulnerability Scan Coverage (%) | | | 100% of assets | | |
| Assets with Known Exploitable Vulns | | | 0 | | |

---

## Section 6 — Detection Coverage (MITRE ATT&CK)

| Tactic | Techniques Covered | Total Techniques | Coverage % | Gap Areas |
|--------|-------------------|-----------------|------------|-----------|
| Initial Access | | 10 | | |
| Execution | | 14 | | |
| Persistence | | 20 | | |
| Privilege Escalation | | 14 | | |
| Defense Evasion | | 43 | | |
| Credential Access | | 17 | | |
| Discovery | | 32 | | |
| Lateral Movement | | 10 | | |
| Collection | | 17 | | |
| Command & Control | | 16 | | |
| Exfiltration | | 9 | | |
| Impact | | 14 | | |
| **TOTAL** | | **216** | | |

---

## Section 7 — Programme Health Metrics

| Metric | This Period | Last Period | Target | Trend | Notes |
|--------|-------------|-------------|--------|-------|-------|
| Playbooks Reviewed/Updated | | | 100% reviewed annually | | |
| Detection Rules Reviewed | | | 100% reviewed quarterly | | |
| Tabletop Exercises Completed | | | 2 per year minimum | | |
| Audit Findings (Total Open) | | | 0 critical open | | |
| Audit Findings (Critical) | | | 0 | | |
| Security Awareness Training Completion | | | 100% | | |
| Phishing Simulation Click Rate | | | < 5% | | |
| External Penetration Test Findings Closed | | | 100% within agreed timeline | | |

---

## Period Summary

### RAG Status (Red / Amber / Green)
| Category | Status | Reason |
|----------|--------|--------|
| Alert Volume | 🟢 / 🟡 / 🔴 | |
| Response Times (MTTD/MTTR) | 🟢 / 🟡 / 🔴 | |
| False Positive Rate | 🟢 / 🟡 / 🔴 | |
| Analyst Capacity | 🟢 / 🟡 / 🔴 | |
| Detection Coverage | 🟢 / 🟡 / 🔴 | |
| Vulnerability Posture | 🟢 / 🟡 / 🔴 | |
| Programme Health | 🟢 / 🟡 / 🔴 | |

### Top 3 Wins This Period
1.
2.
3.

### Top 3 Concerns / Risks
1.
2.
3.

### Actions Required
| Action | Owner | Due Date | Priority |
|--------|-------|----------|----------|
| | | | |
