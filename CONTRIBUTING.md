# Contributing to Aruba Datapath Session Analyzer

Thank you for your interest in contributing! This is a community project and all constructive contributions are welcome.

---

## Ways to Contribute

- **Bug reports** — something not parsing correctly, a UI issue, a broken filter
- **Feature requests** — new columns, additional lookup tables, new chart types
- **Code improvements** — performance, browser compatibility, code clarity
- **Documentation** — improving the README, adding examples, correcting errors
- **Testing** — trying the tool against different ArubaOS versions and reporting results

---

## Reporting a Bug

Before opening an issue, please check if it has already been reported.

When filing a bug report, include:

1. **Browser and version** (e.g. Chrome 121, Firefox 122)
2. **ArubaOS version** if relevant (e.g. ArubaOS 8.11.2)
3. **What you expected to happen**
4. **What actually happened**
5. **Steps to reproduce** — if possible, include a sanitised snippet of the log output that triggers the issue (remove any real IP addresses or hostnames if needed)

> ⚠️ Please **do not upload real tech-support logs** containing sensitive network data to GitHub issues.

---

## Suggesting a Feature

Open an issue with the label `enhancement` and describe:

- What problem it solves
- How you imagine it working
- Any Aruba CLI output or field that would need to be parsed

---

## Submitting a Pull Request

1. **Fork** the repository
2. **Create a branch** with a descriptive name:
   - `fix/port-lookup-missing-8222`
   - `feature/add-vlan-filter`
   - `docs/improve-readme`
3. **Make your changes** — keep them focused; one concern per PR
4. **Test** in at least one modern browser before submitting
5. **Open a Pull Request** against the `main` branch with a clear description of what changed and why

### Code Style Guidelines

- This is a single-file HTML project — keep it that way unless there is a very strong reason to split
- JavaScript: `'use strict'`, `const`/`let` (no `var`), clear variable names
- CSS: use the existing CSS variable system (`--cyan`, `--bg1`, etc.) for all colours — do not hardcode hex values where a variable exists
- Keep lookup tables (port names, protocol names) in the same format as existing entries
- New features should work correctly in all three themes (Dark / Gray / Light)
- No new external dependencies without discussion first

---

## Code of Conduct

All contributors are expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md). Please be respectful and constructive in all interactions.

---

## Questions

If you are unsure whether something is a bug or a feature, or you want to discuss an idea before building it, open an issue and ask. That is always the right first step.
