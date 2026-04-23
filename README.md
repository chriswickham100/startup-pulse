# startup-pulse

Personal intelligence repository for early- and seed-stage company research.
Built to develop pattern recognition across VC portfolios — for identifying
opportunities to work with companies or build in adjacent spaces.

---

## Repository Structure

```
startup-pulse/
├── README.md                          ← You are here
├── index.html                         ← Portfolio dashboard (open in browser)
│
├── templates/                         ← Reusable research tools (not company data)
│   ├── 1pager-template.md             ← Standard 1-pager format for every company
│   └── research-prompts.md            ← Claude prompts for each research phase
│
└── vcs/                               ← All VC portfolio research lives here
    └── menlo-ventures/                ← One folder per VC firm
        ├── _vc-profile.md             ← Firm overview, thesis, key partners
        └── companies/                 ← One subfolder per portfolio company
            └── company-name/
                ├── 1pager.md          ← Main research output
                └── notes-raw.md       ← Optional: raw research notes
```

**Rule of thumb:**
- `templates/` — tools you use *to* research. Never put company data here.
- `vcs/` — everything you learn *from* research. One VC folder, with companies nested inside.

---

## How to Add a New Company

1. **Research** — use the 30-min checklist in `templates/research-prompts.md`
2. **Draft** — paste raw notes + Prompt 1 into Claude
3. **Save** — create `vcs/<vc-name>/companies/<company-name>/1pager.md`
4. **Log** — add the company to `index.html` using the "Add company" form
5. **Commit** — `git add . && git commit -m "add: <company-name> 1-pager"`

## How to Add a New VC Firm

1. Create `vcs/<vc-name>/` folder
2. Copy `templates/1pager-template.md` as a reference
3. Add a `_vc-profile.md` (see Menlo Ventures as an example)
4. Start adding companies under `vcs/<vc-name>/companies/`

---

## Naming Conventions

| Thing | Convention | Example |
|---|---|---|
| VC folder | lowercase, hyphenated | `menlo-ventures` |
| Company folder | lowercase, hyphenated | `abnormal-security` |
| 1-pager file | always `1pager.md` | `1pager.md` |
| Raw notes | always `notes-raw.md` | `notes-raw.md` |
| VC profile | always `_vc-profile.md` | `_vc-profile.md` |

---

## Keeping Research Fresh

- Set a monthly calendar reminder to revisit high-interest companies (★★★★+)
- Use **Prompt 5** in `research-prompts.md` to do a structured refresh
- After every 5+ companies, run **Prompt 6** to spot cross-portfolio patterns
- Update the `Last Updated` field at the top of each 1-pager when you revise it

---

## Current VC Portfolios Being Tracked

| VC | Status | Companies Researched |
|---|---|---|
| Menlo Ventures | 🟢 Active | 0 |

---

*Started: April 2026*
