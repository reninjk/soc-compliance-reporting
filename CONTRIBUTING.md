# Contributing to SOC Compliance Reporting

This repository contains compliance checklists, audit templates, and reporting frameworks for the SOC. Contributions must maintain accuracy, confidentiality standards, and document structure consistency.

## What Lives Here

```
soc-compliance-reporting/
├── checklists/          # Audit checklists (ISO 27001, CIS Controls, NIST CSF, etc.)
├── reporting/           # Report templates (quarterly review, trend analysis, exec summaries)
├── evidence/            # Evidence collection guides and templates (never real evidence)
└── .github/             # Workflow and issue templates
```

## Contribution Types

### Adding a New Checklist

1. Use an existing checklist (e.g. `iso27001-audit.md`) as your structural template
2. Name the file: `checklists/<framework>-audit.md` (e.g. `nist-csf-audit.md`, `pci-dss-audit.md`)
3. Required sections: Status key, controls table with columns for Status/Evidence/Owner, Audit Summary table, Action Items table
4. All controls must start as ❌ (baseline — assessors fill in actual status)
5. Include the framework version in the header and file footer

### Adding or Updating a Report Template

1. Name: `reporting/<purpose>-template.md` or `reporting/<purpose>-<frequency>.md`
2. Required header block: Period, Prepared by, Reviewed by, Distribution, Classification
3. All data fields must be blank placeholders — never pre-fill with real metrics
4. Include a purpose section explaining when and how to use the template
5. Tables should include a "Target" or "Threshold" column wherever applicable

### Updating an Existing Document

- Minor fixes (typos, broken markdown, formatting): submit directly to `main` with a clear commit message
- Structural changes (new sections, changed fields, different control mappings): require PR review
- Framework version updates (e.g. CIS v7 → v8): create a new file, don't overwrite; keep old version with a deprecation notice

## Sensitive Data Policy

This repository is for **templates only**. It must never contain:

| Prohibited Content | Example |
|-------------------|---------|
| Real audit findings | Actual ❌ Non-compliant entries with named systems |
| Real metric data | Actual MTTD/MTTR figures from your environment |
| System or asset names | Hostnames, IP ranges, account names |
| Vendor names (production) | Names of your actual SIEM, EDR, ticketing tools |
| Regulatory correspondence | Letters from regulators, audit firm reports |
| Evidence artefacts | Screenshots, log exports, scan results |

If you need to show example data, use clearly fictional placeholders:
- Systems: `[System A]`, `[SIEM Platform]`, `[Your EDR]`
- IPs: Use documentation ranges (192.0.2.x, 198.51.100.x per RFC 5737)
- Dates: Use `[Date]` or `[Q# YYYY]`
- Names: Use `[Analyst Name]`, `[CISO Name]`

## Commit Message Format

Use Conventional Commits:

| Type | Use for |
|------|---------|
| `docs:` | New or updated templates, checklists, guides |
| `fix:` | Broken markdown, incorrect control references, typos |
| `feat:` | New framework checklist or major new template section |
| `ci:` | Workflow changes |
| `chore:` | Non-content maintenance |

Examples:
```
docs: add NIST CSF 2.0 audit checklist
fix: correct ISO 27001 Annex A control numbering (2013→2022)
feat: add PCI-DSS v4 compliance checklist
docs: update quarterly review template with threat landscape section
```

## Review Process

| Change Type | Reviewers Required | Approval Required |
|-------------|-------------------|-------------------|
| Typo / formatting fix | 0 | Merge directly |
| New section in existing template | 1 peer | SOC Manager |
| New checklist (new framework) | 1 peer | CISO or SOC Manager |
| Framework version update | 2 peers | CISO |

## Compliance Framework References

When contributing checklist content, always reference the authoritative source:

| Framework | Source | Version in use |
|-----------|--------|---------------|
| ISO 27001 | iso.org | 2022 |
| CIS Controls | cisecurity.org | v8 |
| NIST CSF | nist.gov/cyberframework | 2.0 |
| NIST SP 800-53 | csrc.nist.gov | Rev 5 |
| PCI-DSS | pcisecuritystandards.org | v4.0 |
| SOC 2 | aicpa.org | 2017 Trust Services Criteria |

For security issues in this repository itself, see [SECURITY.md](SECURITY.md).
