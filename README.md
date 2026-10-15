# Healthcare Privacy Notice GDPR Analysis

This repository presents an independent, evidence-based assessment of a publicly available healthcare privacy notice. It converts an academic review into a practical GDPR transparency case study with a structured findings register, remediation roadmap, redesigned notice blueprint, report, and executive presentation.

![Project preview](docs/project-preview.png)

## Assessment conclusion

The reviewed notice has broad substantive coverage and addresses many core GDPR topics. Its main improvement opportunity is operational transparency: readers must connect long sections on data categories, purposes, legal bases, recipients, transfers, retention, and rights without a single purpose-level map.

The assessment assigns a **7.1/10 transparency maturity score**. This is a portfolio maturity rating, not a legal-compliance determination. The highest-value improvements are a layered notice, purpose-level processing tables, clearer entity roles, contextual notices at collection points, and documented review ownership.

## Repository contents

- [English assessment report](report/privacy-policy-gdpr-analysis-en.docx)
- [PDF report](report/privacy-policy-gdpr-analysis-en.pdf)
- [Executive presentation](presentation/privacy-policy-gdpr-analysis-en.pptx)
- [PDF presentation](presentation/privacy-policy-gdpr-analysis-en.pdf)
- [Assessment methodology](analysis/assessment-method.md)
- [GDPR transparency matrix](analysis/gdpr-transparency-matrix.md)
- [Findings register](analysis/findings-register.csv)
- [Layered notice blueprint](recommendations/layered-notice-blueprint.md)
- [Remediation roadmap](recommendations/remediation-roadmap.md)
- [References](references/references.md)

## Method

The public notice was reviewed against GDPR Articles 5, 9, 12, 13, 14, 15-22, 25, 32, 35 and 44-49; EDPB transparency guidance; and the Hellenic Data Protection Authority's notice-design guidance. Each topic was rated for presence, specificity, navigability, and actionability.

```mermaid
flowchart LR
    A[Public notice] --> B[Requirement mapping]
    B --> C[Evidence assessment]
    C --> D[Risk and usability findings]
    D --> E[Prioritised remediation]
    E --> F[Layered notice design]
    F --> G[Periodic governance review]
```

## Key findings

1. Coverage is broad, including health data, rights, retention, security, DPIAs, transfers, and DPO contact.
2. The notice is difficult to scan because multiple audiences and processing contexts share one long document.
3. Purposes and lawful bases are described, but not consistently connected to data categories, recipients, and retention periods.
4. Group entities are listed, while the controller role for each interaction could be easier to determine.
5. Several retention periods are specific, but broad fallback language reduces predictability.
6. Separate contextual notices for careers, applications, cookies, call recording, CCTV, and research should connect to one controlled notice architecture.
7. The July 2022 review date should trigger an evidence-based refresh and an owned annual review cycle.

## Scope and limitations

- The assessment is based on publicly accessible material reviewed on **15 October 2026**.
- It does not test internal processing, contracts, security controls, consent records, DPIAs, or deletion execution.
- A missing public explanation does not prove that an internal control is absent.
- The project is an educational governance assessment and does not constitute legal advice.
- No patient or employee personal data was used.

## Author

**Spyridon Grouztidis** — privacy-policy analysis, GDPR mapping, English redesign, and governance recommendations.

## License

All original analysis and repository documentation are All Rights Reserved. Referenced laws, guidance, and third-party policy content remain subject to their respective terms. See [LICENSE.md](LICENSE.md).
