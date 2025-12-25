# Contributing

> **Last Updated**: 2025-12-25 by Keming He

Maintainer guide for @KemingHe to add cybersecurity and AI governance documents to the collection. This repository is solely maintained by [@KemingHe](https://github.com/KemingHe) - external contributions are welcome via issues and suggestions only.

## Adding Documents

**Workflow**:

1. Source materials: Download original PDF, then generate audio and video overviews via [NotebookLM](https://notebooklm.google.com)
2. Upload to Google Drive: Store PDF, audio, video with public access links
3. Create .md file: Use [CONTRIBUTING-summary-template.md](./CONTRIBUTING-summary-template.md)
4. Place in directory: Choose appropriate folder based on document type
5. Commit changes: Follow git conventions below

**Directory placement**:

- `frameworks-controls-and-playbooks/`: Official standards, frameworks, and playbooks (NIST, ISO, COBIT, etc.)
- `google-cybersecurity-certificate/`: Learning resources from the [Google Cybersecurity Certificate](https://grow.google/certificates/cybersecurity/) program
- `industry-reports/`: Market analysis, threat landscape, workforce insights
- `laws-and-regulations/`: Laws, regulations, compliance requirements, governance policies
- `product-guides/`: Security tools (SIEM, SOAR, etc.), implementation guides, best practices
- `research-papers/`: Academic papers, research studies, technical analysis
- `securiti-ai-security-and-governance-certification/`: Learning resources from the [Securiti AI Security and Governance Certification](https://education.securiti.ai/certifications/ai-governance/) program

> [!TIP]
>
> See [CONTRIBUTING-summary-template.md](./CONTRIBUTING-summary-template.md) for complete formatting guidelines and placeholder details.

## Git Conventions

**Branch naming**: `<type>/<scope>/<assignee>`

Example: `docs/add-nist-framework/KemingHe`

**Commit format**: `<type>(<scope>): <description>`

Example: `docs(frameworks-controls-and-playbooks): add NIST CSF 2.0 summary`

**Types**: `docs`, `fix`, `feat`, `refactor`, `chore`

> [!TIP]
>
> Use [commit message generation prompt](./prompts/prompt-commit-msg-gen.md) for structured commits.

## Issues & Pull Requests

**External contributions**: Submit issues for document suggestions, broken links, or categorization improvements

**Maintainer PRs**: Template compliance, Google Drive links tested, directory placement verified, 3-sentence significance included

**Templates**: [Summary template](./CONTRIBUTING-summary-template.md), [GitHub templates](./.github/), [AI prompts](./prompts/)

---

> Contributing Guide Template v1.0.2 - KemingHe/common-devx
