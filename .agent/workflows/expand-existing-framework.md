---
description: Expand an existing framework with new topics, deeper coverage, or missing sections
---

# Expand Existing Framework Workflow

Use this workflow when adding new content to a framework that already exists in the repository.

## Steps

1. **Identify the gap**
   - Review the framework's `README.md` and directory structure.
   - Ask the user what topic or depth level needs coverage.
   - Check if the topic overlaps with content in other frameworks.

// turbo
2. **Review existing content**
   - Read the files in the relevant tier directory (`01_foundation/`, `02_intermediate/`, etc.).
   - Note the numbering convention and writing style already in use.

3. **Research the topic**
   - Use `search_web` and `read_url_content` for official and practitioner sources.
   - Focus on the specific framework version documented in the repo.

4. **Author the new content**
   - Follow the **Content Authoring** skill (`.agent/skills/content-authoring/SKILL.md`).
   - Match the skill level of the target directory.
   - Use the next sequential file number (e.g., if the last file is `03_`, name the new file `04_`).

5. **Add cross-references**
   - Link from/to related topics within the same framework.
   - Link to related topics in other frameworks where relevant.
   - Use the **Framework Comparison** skill if producing a comparison section.

6. **Update the framework README.md**
   - Add the new file to the directory map.
   - Update learning paths if the new content affects recommended reading order.

7. **Quality review**
   - Run through the quality checklist in `.agent/rules.md`.
   - Verify file naming and placement match conventions.
