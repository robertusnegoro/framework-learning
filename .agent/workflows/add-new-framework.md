---
description: Add a brand new IT/business framework to the repository from scratch
---

# Add New Framework Workflow

Use this workflow when adding a completely new framework (e.g., TOGAF, PRINCE2, SAFe, ISO 27001) to the repository.

## Steps

1. **Gather requirements from the user**
   - Confirm the framework name, version, and scope.
   - Ask about target audience and priority depth (foundation only, or full coverage).

// turbo
2. **Read the workspace rules**
   - Review `.agent/rules.md` for conventions.
   - Review the root `README.md` for context on existing frameworks.

3. **Research the framework**
   - Follow the **Framework Research** skill (`.agent/skills/framework-research/SKILL.md`).
   - Use `search_web` and `read_url_content` to gather information from official and authoritative sources.
   - Collect: official body, current version, certification paths, key concepts, domains/processes.

4. **Create the directory structure**
   - Create `<FRAMEWORK>/` at repository root.
   - Create subdirectories: `01_foundation/`, `02_intermediate/`, `03_advanced/`, `references/`.
   - Add specialized directories (e.g., `04_practices/`) if the framework warrants it.

5. **Write the framework README.md**
   - Include: overview, version info, learning paths, directory map, key concepts summary.
   - Follow the pattern of existing framework READMEs (e.g., `ITIL/README.md`).

6. **Author foundation-level materials**
   - Follow the **Content Authoring** skill (`.agent/skills/content-authoring/SKILL.md`).
   - Minimum files: `01_overview_and_history.md`, `02_core_concepts.md`, `03_key_terminology.md`.

7. **Author intermediate and advanced materials**
   - At least 2 files in `02_intermediate/` and 1 file in `03_advanced/`.
   - Include practical examples relevant to banking/financial services where applicable.

8. **Create reference materials**
   - `01_official_resources.md` — links to official documentation and communities.
   - `02_certification_paths.md` — certification tiers, providers, costs, exam details.

9. **Update the root README.md**
   - Add the new framework to the comparison table.
   - Add it to the directory structure diagram.
   - Add it to the Overview section and any relevant learning paths.

10. **Quality review**
    - Run through the quality checklist in `.agent/rules.md`.
    - Check all cross-references link to real files.
    - Verify mermaid diagrams render correctly.
    - Ensure version and date metadata is present in all files.
