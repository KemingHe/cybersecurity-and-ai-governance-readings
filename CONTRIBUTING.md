# Contributing

> Updated on 2025-08-30 by @KemingHe

Maintainer guide for @KemingHe to add cybersecurity documents to the collection. This repository is solely maintained by @KemingHe - external contributions are welcome via issues and suggestions only.

## Adding Documents

**Workflow overview**:

1. **Source materials**: Download original PDF, then generate audio and video overviews via [NotebookLM](https://notebooklm.google.com)
2. **Upload to Google Drive**: Store PDF, audio, video with public access links
3. **Create .md file**: Use [CONTRIBUTING-document-template.md](./CONTRIBUTING-document-template.md)
4. **Place in directory**: Choose appropriate folder based on document type
5. **Commit changes**: Follow git conventions below

**Directory placement**:

- `frameworks/`: Official standards and frameworks (NIST, ISO, COBIT, etc.)
- `industry-reports/`: Market analysis, threat landscape, workforce insights  
- `legal/`: Laws, regulations, compliance requirements, governance policies
- `product-guides/`: Security tools, implementation guides, best practices
- `research/`: Academic papers, research studies, technical analysis

> [!TIP]
> See [CONTRIBUTING-document-template.md](./CONTRIBUTING-document-template.md) for complete formatting guidelines and placeholder details.

## Git Conventions

**Branch**: `<type>/<scope>/<assignee>` → `docs/add-nist-framework/KemingHe`  
**Commit**: `<type>(<scope>): <description>` → `docs(frameworks): add NIST CSF 2.0 summary`

**Types**: `docs`, `fix`, `feat`, `refactor`, `chore`

> [!TIP]
> Use [commit message generation prompt](./prompts/prompt-commit-msg-gen.md) for structured commits.

## Issues & Pull Requests

**External contributions**: Submit issues for document suggestions, broken links, or categorization improvements

**Maintainer PRs**: ✅ Template compliance • ✅ Google Drive links tested • ✅ Directory placement • ✅ 3-sentence significance

**Templates**: [Document template](./CONTRIBUTING-document-template.md) • [GitHub templates](./.github/) • [AI prompts](./prompts/)

---

> Contributing Guide Template v1.0.1 - KemingHe/common-devx
