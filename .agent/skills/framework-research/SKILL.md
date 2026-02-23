---
name: Framework Research
description: Research a new IT/business framework from scratch — identify scope, official bodies, versions, certification paths, and key concepts — then produce structured learning materials.
---

# Framework Research Skill

Use this skill when you need to **research and document a new framework** that does not yet exist in this repository (e.g., TOGAF, PRINCE2, SAFe, ISO 27001, NIST CSF, etc.).

## Prerequisites

- Read the workspace rules in `.agent/rules.md` for content and formatting standards.
- Review the root `README.md` to understand how existing frameworks are documented.
- Skim at least one existing framework directory (e.g., `ITIL/`) as a reference template.

## Step-by-Step Instructions

### 1. Define the Research Scope

Before searching the web, answer these questions:

| Question | Why It Matters |
|----------|---------------|
| What is the framework's full name and common abbreviation? | Establishes proper naming throughout docs |
| Who is the governing body / standards organization? | Ensures you cite the right official source |
| What is the current version and release date? | Version accuracy is critical per rules |
| Is there a certification program? If so, who administers it? | Needed for learning paths and references |
| What is the framework's primary scope? (governance, delivery, risk, etc.) | Sets the correct directory structure |

### 2. Conduct Web Research

Use `search_web` and `read_url_content` to gather information:

1. **Official website & documentation** — Always start here.
2. **Wikipedia / overview articles** — Good for historical context and scope.
3. **Comparison articles** — e.g., "TOGAF vs COBIT" — reveals overlaps with existing frameworks.
4. **Certification pages** — Official cert provider sites for learning-path data.
5. **Practitioner blogs / case studies** — For practical examples and real-world context.

> [!IMPORTANT]
> Collect source URLs as you go — you will need them for the `references/` directory.

### 3. Organize Findings into Tiers

Map your findings into the standard tier structure:

| Tier | Directory | Content |
|------|-----------|---------|
| Foundation | `01_foundation/` | Core concepts, principles, terminology, history |
| Intermediate | `02_intermediate/` | Detailed processes, capabilities, domains, practices |
| Advanced | `03_advanced/` | Strategy, implementation guidance, integration with other frameworks |
| Specialized (optional) | `04_*` | Framework-specific deep dives (e.g., specific domains, toolkits) |
| References | `references/` | Certification paths, official links, recommended books, practice exams |

### 4. Produce the Output

Use the **Content Authoring** skill (`.agent/skills/content-authoring/SKILL.md`) to write each file following repo conventions.

**Minimum viable output for a new framework:**

```
<FRAMEWORK>/
├── README.md                    # Overview, learning paths, directory map
├── 01_foundation/
│   ├── 01_overview_and_history.md
│   ├── 02_core_concepts.md
│   └── 03_key_terminology.md
├── 02_intermediate/
│   └── (at least 2 topic files)
├── 03_advanced/
│   └── (at least 1 topic file)
└── references/
    ├── 01_official_resources.md
    └── 02_certification_paths.md
```

### 5. Integrate with the Repository

- Update the root `README.md` comparison table to include the new framework.
- Add the new framework to the directory structure diagram.
- Note cross-references and synergies with existing frameworks.

## Quality Gate

Before considering the research complete, verify:

- [ ] All "Define the Research Scope" questions have answers
- [ ] At least 3 official/authoritative sources cited
- [ ] Minimum viable output structure created
- [ ] Root `README.md` updated
- [ ] Content reviewed against `.agent/rules.md` quality checklist
