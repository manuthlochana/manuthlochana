# Engineering Workflow — `manuthlochana/manuthlochana`

This profile repository follows the same Issue-to-PR discipline applied across Thunder Storm Studio production systems.

## 01 / Change Protocol

1. **Open an RFC or Defect Issue** using `.github/ISSUE_TEMPLATE/` before introducing structural or visual changes.
2. **Branch from `main`** using conventional prefixes:
   - `feat/<scope>` — editorial layout, SVG systems, or selected work updates
   - `chore/<scope>` — CI checks, governance templates, or maintenance
   - `fix/<scope>` — rendering, XML, or link defects
3. **Open a Pull Request** targeting `main`, reference `Closes #<issue>` via `.github/PULL_REQUEST_TEMPLATE.md`, and wait for `Validate Profile Architecture` CI checks to pass.
4. **Squash & Delete Branch** once verified so `main` retains a clean, auditable commit ledger.
