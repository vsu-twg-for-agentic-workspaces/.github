# 🤝 Contributing to VSU TWG for Agentic Workspaces

Thank you for contributing to the **VSU Technical Working Group for Agentic Workspaces**. We develop open, ethical, and practical AI workflow tools for Visayas State University.

The full standards live in `AGENTS.md` in the training repository. This page is a short summary; if the two ever differ, `AGENTS.md` wins.

---

## 1. Core operating principles

1. **Issue first:**
   - Every change, proposal, or curriculum update starts with a GitHub Issue that has a full scope, an assigned facilitator, labels, and clear acceptance criteria before any content is written.
2. **5-point AI review checklist:**
   - Before submitting, review all content against:
     - ✅ **Facts** — Are numbers, names, and statements verified?
     - ✅ **Sources** — Are all references verifiable?
     - ✅ **Tone** — Formal, respectful, and encouraging for university staff.
     - ✅ **Privacy** — Absolutely no real student or personnel identifiable data (RA 10173).
     - ✅ **Ownership** — Edited and verified by a human.
3. **Branches:**
   - A branch is a working copy where you make changes without touching the main copy. Create it from the repository's default branch: `master` for the training repository, `main` for this repository.
   - Name it `<type>/issue-N-short-desc`, where `<type>` is a commit type from Section 2, `N` is the issue number, and `short-desc` is a few lowercase words joined by hyphens (for example, `feat/issue-1-design-standards`).
4. **Pull requests and multi-facilitator review:**
   - Every pull request links its issue in the description (`Closes #N`), names the assignee, and carries the right labels.
   - When you open the pull request, request every facilitator except the author or assignee as a GitHub reviewer. If someone cannot be added yet (for example, their organization invite is pending), name them in the description instead.
   - Every pull request **must be reviewed and approved by all other facilitators** (non-assignees) before it is merged, except in the two cases below.
5. **Owner exception:**
   - The lead facilitator may review and merge a pull request alone **only when** one or more co-facilitators cannot review (invite not yet accepted, or unavailable). The reason is stated in a pull request comment before merging. Co-facilitators may still review afterward; any changes they ask for go into a new issue and pull request.
6. **`AGENTS.md` review exemption:**
   - Pull requests that change `AGENTS.md` (plus its `CHANGELOG.md` entry and matching wording in `README.md` or issue templates) do not need facilitator review. The lead facilitator may merge them directly. The issue-first rule still applies, and the exemption is stated in a pull request comment before merging.

---

## 2. Commit message standards

Format: `<type>: <short description>`, in the imperative mood, at most 72 characters.
- `feat`: New material, lesson, script, or template
- `fix`: Correction to existing content
- `docs`: Documentation updates
- `refactor`: Structural reorganization
- `chore`: Maintenance

Example:
```text
feat: add module 3 hands-on CRISP lab
fix: correct typo in token calculation table
```

---

## 3. Brand compliance

Visuals, diagrams, badges, and templates follow the [VSU Brand Book](https://brandbook.vsu.edu.ph). The VSU colors are green and gold:
- **Green:** `#146939` (Dark Green `#17321A`, Light Green `#00954F`)
- **Golden Yellow:** `#FDC530` (Corn Yellow `#FCD83D`, Yellow `#FFE800`)

Workshop materials are for workshop use only and do not represent the university in an official capacity, so they may also use the TWG logo colors: **TWG Blue** `#123F8C`, **TWG Silver** `#C4CBD6`, and white. Official VSU marks (seal, brand logo, text logo) are always used exactly as the Brand Book specifies. See `resources/vsu-brandbook.md` and `resources/design-standards.md` in the training repository for the detailed rules.
