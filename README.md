# 🔐 Research Vault

A personal repository for documenting research projects — from initial proposals through literature reviews to final findings and artifacts.

> *"The best time to document your research is while you're doing it."*

---

## 📂 Research Index

| # | Project | Status | Started | Tags |
|---|---------|--------|---------|------|
| 1 | [Merkle Tree Library](./projects/merkle-tree-library/) | 🟡 In Progress | Feb 2026 | `rust` `blockchain` `merkle-trees` `ethereum` |

**Status Legend:** 🟢 Complete · 🟡 In Progress · 🔴 On Hold · ⚪ Planned

---

## 🏗️ Repository Structure

```
research-vault/
├── README.md                  # You are here — research index
├── templates/                 # Reusable templates for new projects
│   ├── PROJECT_TEMPLATE.md    # New project checklist
│   ├── PROPOSAL_TEMPLATE.md   # Proposal structure
│   ├── LITERATURE_NOTE.md     # Template for individual paper notes
│   └── FINDING_TEMPLATE.md    # Template for documenting findings
│
└── projects/
    └── <project-name>/
        ├── README.md           # Project overview and navigation
        ├── proposal/           # Research proposals and revisions
        ├── literature-review/  # Paper summaries and gap analysis
        ├── findings/           # Results, analysis, and conclusions
        ├── artifacts/          # Code, data, diagrams, presentations
        └── references/         # BibTeX files and reference lists
```

---

## 🚀 Starting a New Research Project

1. Copy the project template:
   ```bash
   cp -r templates/ projects/<new-project-name>/
   ```
2. Fill in `projects/<new-project-name>/README.md`
3. Add an entry to the **Research Index** table above
4. Start documenting!

See [`templates/PROJECT_TEMPLATE.md`](./templates/PROJECT_TEMPLATE.md) for the full checklist.

---

## 📝 Conventions

- **One folder per project** under `projects/`
- **Date your files** using `YYYY-MM-DD-` prefix for easy sorting (e.g., `2026-02-12-initial-proposal.md`)
- **Literature notes** get one file per paper in `literature-review/papers/`
- **Findings** are numbered chronologically (`01-`, `02-`, etc.)
- **Keep raw data and code** in `artifacts/` — reference them from findings

---

## 👤 Author

**[Blessing Samuel]**  
Protocol Engineer

---

<sub>This vault is continuously updated as research progresses.</sub>
