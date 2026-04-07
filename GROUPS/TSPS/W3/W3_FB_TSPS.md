# Week 3 Feedback: TSPS Group  
**Reviewer:** Dr. Qian  
**Date:** January 27, 2026

---

## Overall Assessment

Your plan demonstrates exceptional academic professionalism and theoretical sophistication. The literature citations, clear operational definitions, and systematic approach are exemplary. However, you have not yet created the required visualization. This is your top priority.

---

## 1. Research Questions & Significance

### Strengths
- **Excellent RQ specificity**: "What proportion of social media comments about female athletes emphasize athletic performance compared to physical appearance?"
- **Strong theoretical grounding**: Cites Krieger et al. (2023) and University of Cambridge (2016) research
- **Clear gap identification**: "Fewer studies quantify appearance-focused commentary at scale"
- **Well-articulated significance**: Implications for athletes, organizations, media consumers, and researchers
- **Professional academic tone** throughout

### Minor Suggestion

Your "Why It Matters" is strong, but could add ONE sentence about:
"This is particularly timely given the 2023-2024 surge in women's basketball visibility (NCAA Championship viewership records, WNBA expansion). As the sport grows, understanding discourse patterns can inform efforts to shift focus toward athletic achievement."

---

## 2. Dataset Selection & Justification

### Strengths
- **Clear rationale**: Large-scale social media comments, textual data for

 systematic analysis
- **Methodological transparency**: Acknowledges instructional/public access context
- **Multiple files specified**: INS_COMMENT, INS_POST, INS_METADATA

### Question for Clarification

**Why are you using INS_POST and INS_METADATA files?**
- Your RQ is about COMMENTS (emphasis on performance vs. appearance)
- INS_COMMENT contains the comment text you'll analyze
- What will POST and METADATA files add to your analysis?

**Possible Justifications:**
- POST: To control for post content type (do basketball posts get more performance comments?)
- METADATA: To track temporal patterns or platform differences

**Action Needed:** Clarify in 1-on-1 consultation or explicitly state how each file will be used.

---

## 3. Preliminary Variable Operationalization

### Strengths
- **Three clear constructs**: Performance-focused, Appearance-focused, Neutral
- **Detailed operational definitions**: Each construct has specific description
- **Method specified**: "Keyword identification and manual review"
- **Proper table format**

### Issue: Missing Keyword Lists

You specify "keyword identification" but don't provide keywords.

**Add Column to Table:**

| Construct | Operational Definition | **Example Keywords** | Data Source / Indicator |
|-----------|------------------------|---------------------|-------------------------|
| Performance-focused discourse | Comments referencing skill, performance outcomes, training, competition results | **"points," "rebounds," "defense," "MVP," "ROTY," "game," "stats," "championship," "clutch," "assist"** | Keyword ID + manual review in ARCC_INS_COMMENT |
| Appearance-focused discourse | Comments referencing physical appearance, body shape, clothing, attractiveness | **"beautiful," "hot," "sexy," "outfit," "legs," "body," "pretty," "gorgeous," "look," "style"** | Keyword ID + manual review in ARCC_INS_COMMENT |
| Neutral discourse | Comments not clearly referencing performance or appearance | **Residual category** | Identified during coding |

---

## 4. Proposed Analyses

### Strengths
- **Clear three-step approach**: Keyword-assisted coding → Frequency/proportion calculation → Descriptive comparison
- **Methodological soundness**: "Followed by manual verification" shows awareness of keyword limitations

### Enhancement Suggestions

**Add Specificity:**

| Analysis Type | Description | RQ Addressed | **Statistical Test** |
|---------------|-------------|--------------|---------------------|
| Keyword-assisted content coding | Keyword lists flag comments; manual review validates categorization | RQ 1 | N/A (coding step) |
| Frequency and proportion analysis | Calculate counts and percentages of each discourse type | RQ 1 | **Chi-square goodness-of-fit test (test if proportions differ significantly from expected values)** |
| Descriptive comparison | Compare prevalence to identify dominant patterns | RQ 1 | **Report confidence intervals for proportions** |

**Why Statistical Tests Matter:**
- You'll find X% performance-focused vs. Y% appearance-focused
- But is the difference statistically significant, or could it be chance?
- Adding chi-square test strengthens your analysis

---

## 5. Limitations & Potential Issues

### Strengths
- **All three limitations are methodologically important**:
  1. Keyword limitations (context, sarcasm, implicit meanings)
  2. Platform/audience representativeness
  3. Researcher interpretation bias

### These Are Excellent
No major changes needed. Consider adding:

**Limitation 4: Temporal Scope**
"Comments span multiple years (2017-2024), during which women's basketball visibility changed significantly. We do not control for temporal trends."

**Limitation 5: Athlete-Specific**
"Analysis focuses on two specific athletes (Reese and Clark). Patterns may not generalize to athletes with different profiles, sports, or career stages."

---

## 6. Ethical Considerations

### Strengths
- **Privacy**: Aggregate-level analysis, no individual profiling
- **Harm**: "Framing findings within critical, analytical perspective rather than normalizing such discourse"
- **Bias**: Transparent coding rules, team discussion of disagreements, acknowledged subjectivity

### This Section Is Exemplary
Your harm mitigation strategy ("critical, analytical perspective") is exactly right. Your recognition of potential bias and transparency commitment is scholarly best practice.

---

## 7. Group Role Assignments

### Observation

You have **four roles** but **four group members** listed:
- Data Lead: Qiaoyin Tan, Paul Son (2 people)
- Methods Lead: Qiaoyin Tan, Paul Son (same 2 people)
- Theory Lead: Lauryn Porter (1 person)
- Visualization Lead: Jolyn Seow (1 person)

**This works fine**, but clarify:
- Qiaoyin and Paul: Are you co-leads on Data AND Methods? Or is one primarily Data, one primarily Methods?

**Suggestion for Clarity:**

| Role | Group Member | Primary Responsibilities |
|------|--------------|-------------------------|
| Data \u0026 Methods Co-Lead | Qiaoyin Tan | Data cleaning, coding scheme development (primary) |
| Data \u0026 Methods Co-Lead | Paul Son | File organization, analysis implementation (primary) |
| Theory Lead | Lauryn Porter | Literature integration, interpretation |
| Visualization Lead | Jolyn Seow | Creating and verifying visualizations |

---

## 8. Data Visualization Plan

**Considerations For Next Week's Submission:**
- Temporal trends of key terms
- Your interpretations of the results

---

## 9. AI-Assisted Work Documentation & Verification

### Strengths
- **Clear tool specification**: Antigravity for structure and academic language
- **Honest about scope**: "Did not generate analysis code at this stage" (checking N/A)
- **Verification process**: Reviewed for accuracy and alignment, ensured no fabrication
- **Good reflection**: "Importance of human judgment, methodological clarity, and ethical responsibility"

### This Section Is Strong
Your acknowledgment that you used AI for drafting/refinement (not analysis) is appropriate transparency.

---

## Summary: Moving Forward

**During Week 3 Class (Today):**
- **PRIORITY**: Refine your visualization (even if pilot sample)
- Discuss keyword lists during 1-on-1 consultation
- Clarify why you're using POST and METADATA files
- Get feedback on coding scheme before full analysis

**This Week (After Class):**
- **Refine the visualization**
- Finalize keyword lists (add to operationalization table)

**Next Week (Week 4):**
- Complete full comment coding
- Run chi-square test for statistical significance
- Calculate confidence intervals for proportions
- Refine visualization based on full dataset (if Week 3 version was pilot)

---

**Overall:** Your plan demonstrates exceptional academic professionalism. The literature integration, theoretical grounding, and methodological rigor are exemplary for a graduate course. Your ethical considerations are thoughtfully developed. Your ONE critical gap is the missing visualization. Once you create it, your plan will be complete and excellent. Focus on getting a visualization—even from a pilot sample—created ASAP.
