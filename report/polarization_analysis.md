# B50 Polarization Analysis
**Group:** TheMcGradys  
**Course:** KIN 7518 Social Issues in Sport  
**Date:** April 19, 2026  
**Dataset:** B50 — Trump/Political Polarization Discourse

---

## Overview

This document reports a preliminary keyword-based analysis of polarizing language across all three B50 comment datasets (YouTube, X, and Instagram). This analysis addresses **RQ1** (recurring themes and moral frames) and provides context for **RQ2** (moral outrage and engagement).

---

## Results

| Platform | Total Comments | Polarizing Comments | % Polarizing |
|---|---|---|---|
| YouTube | 45,623 | 14,841 | 32.5% |
| X (Twitter) | 1,008 | 172 | 17.1% |
| Instagram | 11,833 | 1,230 | 10.4% |
| **TOTAL** | **58,464** | **16,243** | **27.8%** |

---

## Key Findings

- **YouTube has the highest rate of polarizing discourse** (32.5%) — nearly 1 in 3 comments contains polarizing language
- **Instagram has the lowest rate** (10.4%) — roughly 1 in 10 comments
- **X (Twitter) falls in the middle** at 17.1%
- **Across all platforms, ~28% of all B50 comments** contain at least one polarizing keyword

---

## Methodology

**Operational definition of "polarizing comment":** A comment containing at least one keyword from the following categories:

| Category | Example Keywords |
|---|---|
| Partisan/political hostility | MAGA, fake news, deep state, socialist, communist, fascist, woke, traitor, rigged, fraud |
| Moral outrage / us vs. them | liar, lies, disgusting, evil, pathetic, scum, brainwash, propaganda, sheeple |
| Conflict / threat language | fight back, resist, deport, lock up, arrest, revolution |

**Method:** Python regex pattern matching (case-insensitive) applied to the primary text column of each file (`text` for YouTube/Instagram, `contents` for X).

**Text columns used:**
- `B50_YT_COMMENT.xlsx` → `text`
- `B50_X_COMMENT.xlsx` → `contents`
- `B50_INS_COMMENT.xlsx` → `text`

---

## Limitations

1. **Keyword-based approach** — does not capture subtle polarization, sarcasm, or dog-whistle language
2. **False positives possible** — words like "war" or "evil" may appear in non-polarizing contexts
3. **False negatives likely** — actual polarization rate is probably higher than reported here
4. **Unequal sample sizes** — YouTube dominates the dataset (45,623 of 58,464 total comments), which may skew cross-platform comparisons
5. **Language limitation** — keywords are English-only; non-English comments are not captured

---

## Next Steps

- Run t-test comparing likes on polarizing vs. non-polarizing comments (RQ2)
- Conduct thematic coding on a sample of flagged comments to identify dominant moral frames (RQ1)
- Create visualization: grouped bar chart of polarization rates by platform
