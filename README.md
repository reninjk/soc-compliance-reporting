# SOC Compliance & Reporting Hub

> Centralised repository for compliance frameworks, audit checklists, SOC metrics, and executive reporting templates.

## Repository Structure

```
soc-compliance-reporting/
├── checklists/
│   ├── nist-csf-audit.md        # NIST Cybersecurity Framework audit checklist
│   ├── iso27001-audit.md        # ISO/IEC 27001 controls checklist
│   ├── pci-dss-audit.md         # PCI-DSS SOC-relevant controls
│   └── cis-controls-audit.md    # CIS Controls v8 implementation checklist
├── metrics/
│   ├── soc-metrics-template.md  # KPI/KRI definitions and collection guide
│   ├── mttr-mttd-tracker.md     # Mean Time to Detect/Respond tracking
│   └── coverage-matrix.md       # Detection coverage vs MITRE ATT&CK
├── reporting/
│   ├── weekly-report-template.md        # Weekly operational report (L1/L2)
│   ├── monthly-executive-summary.md     # Monthly board/executive summary
│   ├── quarterly-review-template.md     # Quarterly programme review
│   └── incident-trend-analysis.md       # Trend analysis for leadership
├── scripts/
│   ├── generate_metrics_report.py       # Auto-generate metrics from ticket data
│   └── compliance_gap_checker.py        # Check controls against framework
└── .github/
    └── workflows/
        └── validate.yml         # Validate template structure on push
```

## Compliance Frameworks Covered

| Framework | Focus Area | Audit Checklist |
|-----------|-----------|-----------------|
| NIST CSF | Identify, Protect, Detect, Respond, Recover | [nist-csf-audit.md](checklists/nist-csf-audit.md) |
| ISO 27001 | Information Security Management System | [iso27001-audit.md](checklists/iso27001-audit.md) |
| PCI-DSS | Payment card data security | [pci-dss-audit.md](checklists/pci-dss-audit.md) |
| CIS Controls | Prioritised security actions | [cis-controls-audit.md](checklists/cis-controls-audit.md) |

## SOC KPIs & Metrics

### Operational Metrics
| Metric | Target | Measurement Frequency |
|--------|--------|----------------------|
| Mean Time to Detect (MTTD) | < 15 min | Per incident |
| Mean Time to Respond (MTTR) | P1 < 1hr, P2 < 4hr | Per incident |
| Alert Volume | Baseline ±20% | Daily |
| False Positive Rate | < 30% | Weekly |
| Analyst Utilisation | 70–85% | Weekly |
| Escalation Rate | < 20% of alerts | Weekly |
| SLA Compliance | > 95% | Monthly |

### Programme Metrics
| Metric | Target | Measurement Frequency |
|--------|--------|----------------------|
| Detection Coverage (MITRE) | > 70% tactics | Quarterly |
| Open Vulnerabilities (Critical) | 0 > 30 days | Weekly |
| Completed Training | 100% annually | Annually |
| Audit Findings (Open) | 0 critical | Monthly |
| Playbook Coverage | 100% P1/P2 scenarios | Quarterly |

## Reporting Cadence

```
Daily    → Shift handover summary (verbal + ticket notes)
Weekly   → Operational report → SOC Manager → IT Leadership
Monthly  → Executive summary → CISO → Board/Steering Committee
Quarterly→ Programme review → CISO → Risk Committee
Annual   → Compliance audit report → External auditors
```

## Quick Links

| Resource | Description |
|----------|-------------|
| [soc-incident-response](https://github.com/reninjk/soc-incident-response) | IR playbooks and runbooks |
| [soc-detection-rules](https://github.com/reninjk/soc-detection-rules) | Sigma rules and hunt queries |
| [soc-automation](https://github.com/reninjk/soc-automation) | Automation scripts |

## Getting Started

1. **Audit prep**: Start with the relevant framework checklist in `checklists/`
2. **Metrics collection**: Use `metrics/soc-metrics-template.md` to set up your data collection
3. **Reporting**: Copy the appropriate template from `reporting/` and populate weekly/monthly
4. **Automation**: Run `scripts/generate_metrics_report.py` to pull data from your ticketing system

## Contributing

- All checklists use `[ ]` checkboxes — check off as you complete items
- Keep metric targets updated to reflect current SLAs
- Tag report commits with the period: `report/2024-Q4` or `report/2024-W47`
