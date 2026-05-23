# IT Custom Solution LLC · Compliance Posture

Public-facing compliance documentation for procurement officers, primes, and partners. Live canonical pages on **[itcustomsolution.com/compliance-posture](https://itcustomsolution.com/compliance-posture)** — this repo mirrors the highlights for buyers who'd rather read in GitHub.

## Posture summary

| Framework | Status | Detail |
|---|---|---|
| **NIST SP 800-171 Rev. 3** | ✅ Self-assessment in place, refreshed quarterly | SPRS scores published to contracting officers on request, under mutual NDA. Not a third-party DFARS 252.204-7012 assessment. |
| **CMMC Level 2** | 🟡 Readiness stance, not certified | The NIST 800-171 baseline that CMMC L2 inherits is operational today. We have not yet scheduled a formal Level 2 assessment with a C3PAO. When a solicitation requires it, we scope the C3PAO engagement into the proposal cost basis, OR team with a prime that already holds the cert. |
| **Section 508 / WCAG 2.2 AA** | ✅ Conformant | VPAT 2.5-Rev published. axe-core WCAG 2.2 AA = 0 violations on all itcustomsolution.com priority routes (22 runs × 11 URLs). |
| **NIST SP 800-53** | 🟡 Subset operational | Applicable controls operational under our SaaS infrastructure (Cloudflare + Railway + Supabase). Not a FedRAMP authorization. |
| **DCAA / DCMA timekeeping** | ✅ Capable | Per-contract direct-and-indirect cost capture; audit-ready documentation patterns. |
| **FedRAMP** | ❌ Not authorized | We use FedRAMP Moderate substrates (Azure GovCloud, GCP federated) and document the inheritance, but ITC itself is not a FedRAMP-authorized service. |
| **SOC 1 / SOC 2** | ❌ Not certified · not in progress | We do not claim SOC certifications. If a solicitation requires SOC 1 or SOC 2, ITC is a NO-BID unless the prime holds the certification and ITC operates as a subcontractor within the prime's authorization boundary. |
| **HIPAA** | 🟡 BAA-capable | Will sign Business Associate Agreement when a customer engagement involves PHI. Operational controls inherit from NIST 800-171 baseline. |

## Identifiers (procurement-officer reference)

- **Legal name** · IT Custom Solution LLC
- **UEI** · PR9KWJPM4JU9
- **CAGE** · 91CE1
- **EIN** · (available under mutual NDA · canonical on SAM.gov)
- **NYC MBE Cert** · MWCERT2022-353 (valid through 2027-05-31)
- **SBA 8(a)** · Application submitted 2026, under SBA review
- **SAM.gov** · Registered, active

## Insurance

- **Workers compensation** · Hartford-backed, on-policy continuously
- **General liability** · Hartford-backed, bound on-award per project
- **COI delivery** · <24 hour SLA for any client / portal request

## Live documents

| Document | Location | Format |
|---|---|---|
| Capability statement | https://itcustomsolution.com/capability-statement.pdf | PDF |
| Accessibility Conformance Report (VPAT 2.5-Rev) | https://itcustomsolution.com/accessibility-conformance-report.pdf | Tagged PDF |
| Privacy policy | https://itcustomsolution.com/privacy | Web |
| Security policy | https://itcustomsolution.com/compliance-posture | Web |
| Past performance | https://itcustomsolution.com/past-performance | Web |

## How to request the SPRS score, POA&M, or NDA package

Email **sales@itcustomsolution.com** with:
1. Your buying organization name
2. The contract vehicle / solicitation reference (if applicable)
3. NDA preference (your template or ours)

We respond within one business day.

## What we don't claim

We publish a deliberately narrow list of operational claims. We do NOT assert:

- SOC 1 / SOC 2 in any form (certified, in progress, preparing, readiness, equivalent)
- HUBZone certification (parent firm denied 2023; rep-and-cert disclosure on solicitations is "HUBZone: no")
- GSA Schedule / MAS holder status (we are pursuing, not holding)
- 8(a) certified (application submitted; under SBA review)
- ISO 27001 certification (not pursued; controls operational under NIST 800-171)
- FedRAMP authorization (we use FedRAMP-authorized substrates; ITC itself is not authorized)
- TAA compliance without solicitation-specific scoping
- Brand-name flow-downs from primes without written sub-agreement

If a solicitation requires any of these as a hard pass/fail gate, we either (a) team with a prime that holds it, (b) scope the certification cost into the proposal, or (c) NO-BID.

## Contact

- **Sales / RFP responses** · sales@itcustomsolution.com
- **Compliance questions** · lu@itcustomsolution.com
- **Phone** · +1 (646) 671-3399

---

<sub>This repo mirrors the canonical compliance posture published at https://itcustomsolution.com/compliance-posture. The live page is the source of truth; this repo is a GitHub-native mirror for procurement officers who prefer reading documentation alongside the codebase.</sub>
