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

**RQ1:** What recurring themes and moral frames characterize user-generated political discourse about Trump across YouTube, X, and Instagram?

**RQ2:** Do comments expressing moral outrage receive higher engagement (likes) than neutral comments across platforms?

---

## Dataset

- **Dataset:** B50 — Trump/Political polarization discourse
- **Key files used:** `B50_INS_COMMENT.xlsx`, `B50_X_COMMENT.xlsx`, `B50_YT_COMMENT.xlsx`
- **Note:** Raw data files are stored locally and are not uploaded to this repo (see `.gitignore`)

---

## Analytical Approach

| Analysis | Description | RQ |
|----------|-------------|----|
| Thematic/keyword coding | Identify recurring moral frames and themes in comment text | RQ1 |
| Cross-platform comparison | Compare theme frequency across YouTube, X, and Instagram | RQ1 |
| Engagement comparison | Compare mean likes for high-outrage vs. neutral comments | RQ2 |
| Effect size calculation | Determine magnitude of engagement difference (Cohen's d) | RQ2 |

---

## Repo Structure

```
KIN-7518-Project-3-4-21-26/
├── README.md                       # Project overview (this file)
├── .gitignore                      # Excludes data files and system files
├── code/                           # Analysis scripts
├── visualizations/                 # Charts and figures
├── report/                         # Report drafts in markdown
└── GROUPS/TheMcGradys/             # Group plan and feedback docs
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
