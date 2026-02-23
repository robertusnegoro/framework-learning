---
name: Content Authoring
description: Write high-quality, structured learning materials for IT governance and service management frameworks, following repo conventions and targeting different skill levels.
---

# Content Authoring Skill

Use this skill when you need to **write or revise learning material** for any framework in this repository.

## Prerequisites

- Read `.agent/rules.md` for formatting and quality standards.
- Review the target framework's `README.md` to understand existing coverage.
- Identify the **skill level** the content targets (foundation, intermediate, or advanced).

## Document Template

Every content file should follow this structure:

```markdown
# <Topic Title>

**Last Updated:** <Month Year>
**Version:** <Framework version, e.g., ITIL 4>
**Level:** <Foundation | Intermediate | Advanced>

---

## Overview

<1-2 paragraph introduction to the topic>

## <Main Sections>

<Organized content using headings, tables, diagrams>

## Key Takeaways

- <Bullet list of 3-5 main points>

## Cross-References

- Related topics in this framework: [link]
- Related topics in other frameworks: [link]

## Sources

- <Official sources with URLs>
```

## Writing Guidelines by Skill Level

### Foundation Level (`01_foundation/`)

- **Audience:** Newcomers, certification candidates
- **Tone:** Educational, clear, avoids jargon without explanation
- **Content:** Definitions, core principles, high-level overviews
- **Diagrams:** Simple conceptual diagrams, overview flowcharts
- **Length:** 150–400 lines per document

### Intermediate Level (`02_intermediate/`)

- **Audience:** Practitioners with foundation knowledge
- **Tone:** Professional, assumes familiarity with basics
- **Content:** Detailed processes, capabilities, domains, practical examples
- **Diagrams:** Process flows, relationship maps, detailed breakdowns
- **Length:** 200–500 lines per document

### Advanced Level (`03_advanced/`)

- **Audience:** Senior practitioners, consultants, strategists
- **Tone:** Strategic, analytical, references real-world scenarios
- **Content:** Implementation strategy, maturity assessments, framework integration, case studies
- **Diagrams:** Integration maps, maturity models, strategic roadmaps
- **Length:** 200–600 lines per document

## Formatting Toolbox

### Comparison Tables

Use tables when comparing attributes, roles, or processes:

```markdown
| Aspect | Option A | Option B |
|--------|----------|----------|
| Scope  | ...      | ...      |
| Cost   | ...      | ...      |
```

### Mermaid Diagrams

Use mermaid for process flows and hierarchies:

```markdown
​```mermaid
graph TD
    A[Start] --> B{Decision}
    B -->|Yes| C[Action]
    B -->|No| D[Alternative]
​```
```

### Callout Alerts

Use GitHub-style alerts for emphasis:

```markdown
> [!TIP]
> Practical advice for practitioners

> [!IMPORTANT]
> Critical concept that must be understood

> [!WARNING]
> Common misconception or pitfall
```

### Cross-Reference Links

Link to other files in the repo using relative paths:

```markdown
See also: [ITIL Change Enablement](../ITIL/04_practices/change_enablement.md)
```

## Quality Checklist

Before finalizing any content:

- [ ] Header metadata complete (Last Updated, Version, Level)
- [ ] Content matches the declared skill level
- [ ] At least one diagram or table per major section
- [ ] Key Takeaways section present
- [ ] Cross-references to related content included
- [ ] Sources section with at least one official reference
- [ ] Spell check and grammar review complete
- [ ] File name follows `XX_descriptive_snake_case.md` convention
