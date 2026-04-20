# B50 Thematic Analysis
**Group:** TheMcGradys  
**Course:** KIN 7518 Social Issues in Sport  
**Date:** April 19, 2026  
**Dataset:** B50 — Trump/Political Polarization Discourse  
**Addresses:** RQ1 — *What recurring themes and moral frames characterize user-generated political discourse about Trump across YouTube, X, and Instagram?*

---

## Overview

This document reports a keyword-based thematic analysis of all 58,464 B50 comments across YouTube, X (Twitter), and Instagram. Comments were categorized into nine themes using regex pattern matching. A single comment may contribute to multiple themes.

---

## Results

| Rank | Theme | Matching Comments | % of Total |
|------|-------|:-----------------:|:----------:|
| 1 | Anti-Trump / Criticism | 1,347 | 2.3% |
| 2 | Media & Misinformation | 1,211 | 2.1% |
| 3 | Pro-Trump / MAGA Support | 932 | 1.6% |
| 4 | Religion & Morality | 821 | 1.4% |
| 5 | Democracy & Elections | 794 | 1.4% |
| 6 | Economy & Policies | 709 | 1.2% |
| 7 | Race & Identity | 583 | 1.0% |
| 8 | Conflict & Violence Language | 432 | 0.7% |
| 9 | Immigration & Border | 183 | 0.3% |

**Total comments analyzed:** 58,464

---

## Key Findings

1. **Anti-Trump criticism is the dominant theme** (2.3%), slightly outpacing Pro-Trump/MAGA support (1.6%), suggesting discourse across these platforms skews critical of Trump.

2. **Media & Misinformation is nearly as prominent as Anti-Trump criticism** (2.1%), indicating that distrust of media is a central rhetorical frame in political polarization discourse — users frequently invoke "fake news," propaganda, or media manipulation narratives.

3. **Religion & Morality ranks 4th** (1.4%), pointing to moral framing as a key rhetorical device. Users invoke God, evil, sin, and prayer to anchor political positions in moral absolutes — a hallmark of polarized discourse.

4. **Democracy & Elections** (1.4%) and **Economy & Policies** (1.2%) reflect substantive policy concerns underlying the polarization, not just personal attacks.

5. **Immigration is surprisingly low** (0.3%) relative to its prominence in Trump's political brand, suggesting the B50 dataset may not heavily feature immigration-specific content.

6. **Conflict & Violence Language** (0.7%) — while not the most common theme, its presence is notable given its implications for escalating polarization.

---

## Methodology

**Theme definitions and example keywords:**

| Theme | Example Keywords |
|-------|-----------------|
| Anti-Trump / Criticism | liar, criminal, convicted, fraud, pathetic, disgrace, impeach, prison |
| Pro-Trump / MAGA Support | MAGA, America First, Great Again, patriots, Trump won, rigged |
| Media & Misinformation | fake news, propaganda, CNN, MSNBC, deep state, conspiracy, brainwash |
| Religion & Morality | God, Bible, Christ, prayer, moral, evil, satan, faith, blessed |
| Democracy & Elections | election, vote, democrat, republican, constitution, corrupt, swamp |
| Economy & Policies | economy, inflation, tax, jobs, tariff, gas price, cost |
| Race & Identity | racist, woke, diversity, identity, discrimination |
| Conflict & Violence Language | war, revolution, fight, weapon, shoot, kill, attack |
| Immigration & Border | immigration, border, deport, illegal, migrant, wall |

**Method:** Python regex pattern matching (case-insensitive) on primary text column per file. Comments may match multiple themes. Percentages are out of total comments (58,464).

---

## Limitations

1. **Keyword overlap** — a single comment may match multiple themes; percentages are not mutually exclusive
2. **Context-free matching** — keywords may appear in non-political contexts (e.g., "God" in casual speech)
3. **English-only** — non-English comments are not captured
4. **Understates true theme prevalence** — only explicit keyword matches are counted; implicit or coded language is missed

---

## Next Steps

- Qualitatively code a random sample (n=100) of flagged comments per theme to validate keyword accuracy
- Break down theme prevalence **by platform** to address cross-platform differences (RQ1)
- Cross-reference themes with engagement data (likes) to address RQ2
- Create visualization: horizontal bar chart of theme frequencies ranked by prevalence
