---
description: Refresh existing materials when a framework releases a new version or update
---

# Update Materials Workflow

Use this workflow when a framework releases a new version (e.g., ITIL 5, COBIT 2024) or significant update, and existing materials need to be refreshed.

## Steps

1. **Research what changed**
   - Use `search_web` to find official release notes, changelogs, and analysis articles.
   - Document: new version number, release date, key changes, deprecated concepts, new concepts.

// turbo
2. **Inventory affected files**
   - List all files in the framework's directory tree.
   - For each file, assess: no change needed / minor update / major rewrite / delete.

3. **Update content files**
   - Start with `README.md` — update version info, overview, and learning paths.
   - Update `01_foundation/` files first (terminology and concepts may have changed).
   - Work through `02_intermediate/` and `03_advanced/` systematically.
   - For each file:
     - Update the `**Version:**` and `**Last Updated:**` header.
     - Revise content to reflect the new version.
     - Mark deprecated concepts with `> [!WARNING]` alerts.
     - Add new concepts introduced in the update.

4. **Update references**
   - Refresh official resource links.
   - Update certification path info (new exams, retired exams).
   - Add new recommended reading/resources.

5. **Update the root README.md**
   - Update the version info table at the top.
   - Update the comparison table if the framework's scope changed.
   - Update the "Version Information" section.

6. **Quality review**
   - Verify no stale version references remain (search for the old version string).
   - Run through the quality checklist in `.agent/rules.md`.
   - Confirm all cross-references still point to valid files.
