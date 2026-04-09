# KIN 7518 — Project 3: TheMcGradys

**Course:** KIN 7518 Social Issues in Sport  
**Institution:** Louisiana State University  
**Instructor:** Dr. Yiqing Qian  
**Semester:** Spring 2026

---

## Team Members

| Name | Role |
|------|------|
| Jake Russell | Manager / Repo Lead |
| Prosser Crow | Data Lead |
| Jamon Gracin | Methods Lead |

---

## Research Questions

**RQ1:** Do Instagram posts featuring revealing clothing or sexualized imagery by Angel Reese and Caitlin Clark receive higher engagement (likes and comments) compared to non-sexualized posts?

> *Research questions will be refined as analysis develops.*

---

## Dataset

- **Dataset:** Clark-Reese (ARCC) — Instagram posts and visual analysis data
- **Key files used:** `ARCC_INS_POST.xlsx`, `ARCC_INS_VA.xlsx`
- **Note:** Raw data files are stored locally and are not uploaded to this repo (see `.gitignore`)

---

## Analytical Approach

| Analysis | Description | RQ |
|----------|-------------|----|
| Post content coding | Categorize each post as sexualized or non-sexualized using defined criteria | RQ1 |
| Engagement comparison | Calculate mean engagement (likes + comments) for each post type per athlete | RQ1 |
| Effect size calculation | Determine magnitude of engagement difference (Cohen's d) | RQ1 |

---

## Repo Structure

```
KIN-7518-Project-3-4-21-26/
├── README.md                  # Project overview (this file)
├── .gitignore                 # Excludes data files and system files
├── code/                      # Analysis scripts
├── visualizations/            # Charts and figures
├── report/                    # Report drafts in markdown
└── GROUPS/TheMcGradys/        # Group plan and feedback docs
```

---

## Workflow

This repo uses a **branch-and-PR workflow**. No one commits directly to `main`.

```bash
git pull origin main          # Start every session here
git checkout -b your-branch   # Create your branch
# ... do your work ...
git add -A
git commit -m "descriptive message"
git push origin your-branch   # Push branch to GitHub
# Then open a Pull Request on GitHub for manager review
```

---

## Key Links

- **Course:** KIN 7518 Social Issues in Sport
- **Instructor contact:** yqian@lsu.edu
