# Contributing

> Updated on 2025-08-30 by @KemingHe

Quick start guide for contributors adding cybersecurity documents, frameworks, and research to the collection.

## Adding Documents

**Step-by-step process:**

1. **Verify content quality**
   - [ ] Connects to cybersecurity practice or career development  
   - [ ] Recent (2022+) or foundational/authoritative document
   - [ ] From established organizations, government agencies, or recognized experts  
   - [ ] Text-searchable PDF with clear structure
   - [ ] Sourced from authoritative sites (NIST, ISO, vendor sites, research institutions) to ensure authenticity

2. **Name file**:
   - **Research papers**: `YYYY-MM-descriptive-title-by-author.pdf` (use **original** publication date)
   - **All other documents**: `YYYY-MM-descriptive-title-by-organization.pdf` (use **latest** revision date)

   ```plaintext
   # Research (original date)
   2020-08-zero-trust-architecture-by-nist.pdf
   
   # Frameworks/standards/guides (latest revision)  
   2024-02-csf-2-0-by-nist.pdf
   ```

3. **Choose directory**:
   - [**`frameworks/`**](./frameworks/): Official standards and frameworks (NIST, ISO, COBIT, etc.)
   - [**`industry-reports/`**](./industry-reports/): Market analysis, threat landscape, workforce insights
   - [**`legal/`**](./legal/): Laws, regulations, compliance requirements, governance policies
   - [**`product-guides/`**](./product-guides/): Security tools, implementation guides, best practices  
   - [**`research/`**](./research/): Academic papers, research studies, technical analysis

4. **Generate audio**: Upload PDF → [NotebookLM](https://notebooklm.google.com) → Generate audio/video overview → Save as `.wav`/`.mp4`

5. **Submit PR**: Reference issue or explain added value

## Git Conventions

**Branch**: `<type>/<scope>/<assignee>` → `docs/add-nist-framework/username`  
**Commit**: `<type>(<scope>): <description>` → `docs(frameworks): add NIST CSF 2.0`

**Types**: `docs`, `fix`, `feat`, `refactor`, `chore`

> [!TIP]
> Use [commit message generation prompt](./prompts/prompt-commit-msg-gen.md) for structured commits.

## Issues & Pull Requests

**Report Issues**: 🔗 Broken links • 📁 Better categorization • 📄 Missing frameworks/standards

**PR Requirements**: ✅ Issue reference • ✅ Proper naming/placement • ✅ PDF+audio pair

**Templates**: [GitHub templates](./.github/) or [AI prompts](./prompts/) for structured content

---

> Contributing Guide Template v1.0.1 - KemingHe/common-devx
