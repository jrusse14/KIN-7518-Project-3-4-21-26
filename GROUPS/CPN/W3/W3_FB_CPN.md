# Week 3 Feedback: CPN Group  
**Reviewer:** Dr. Qian  
**Date:** January 27, 2026

---

## Overall Assessment

Your plan demonstrates strong technical execution in data preprocessing and a solid understanding of AI-assisted workflows. The sentiment analysis validation (68.5% accuracy via manual coding) is commendable. To strengthen your project, focus on aligning your research question more explicitly with the context and significance you've articulated.

---

## 1. Research Questions & Significance

### Strengths
- Your RQ is answerable with the data you have
- You've correctly identified a timely, relevant phenomenon (Clark-Reese transition to WNBA)

### Area for Improvement: RQ-Context Alignment
**The Issue:**
- Your **context** discusses: "race, representation, and how female athletes are portrayed," specifically mentioning "Black women athletes"
- Your **RQ** asks: "How do Clark's and Reese's **performance and image** affect positive and negative comments?"
- **Race is not mentioned in your RQ**, yet it appears central to your significance argument

**Suggestions for Revision (Choose One):**

**Option A: Revise RQ to match your context**
"How do performance and race interact to shape comment sentiment for Caitlin Clark (white athlete) vs. Angel Reese (Black athlete)?"

**Option B: Revise context to match your RQ**  
Remove discussions of race/representation. Focus instead on: "How does on-court performance influence social media reception for women athletes?"

**Option C: Hybrid approach**  
Keep race in context but frame it as exploratory: "While performance may drive sentiment, we will also explore whether patterns differ by athlete, which could reflect racialized discourse."

### Next Steps:
- Decide which option (A, B, or C) aligns with your actual interests
- Rewrite either RQ or context to ensure alignment
- If keeping race: Explicitly hypothesize how you expect it to manifest (e.g., "We hypothesize Reese will receive more appearance-based comments despite similar performance")

---

## 2. Dataset Selection & Justification

### Strengths
- Excellent data preprocessing workflow (4 clear steps)
- Manual validation of sentiment analysis (68.5% accuracy)
- Temporal alignment between performance and comments

### Areas Needing Clarification

**Issue 1: AI Model Specification**
- You mention "we will use AI model" but which specific model?
- For sentiment analysis, you used "antigravity," but Antigravity is an IDE, not a sentiment model
- **Suggestion:** Specify the actual model (e.g., "Gemini 2.5 Flash via Antigravity," "Claude 3.5 Sonnet," etc.)

**Issue 2: Performance Metrics Definition**
- You say "good = 1, bad = 0" but how do you define good vs. bad?
  - Relative to own average?
  - Relative to opponent?
  - Relative to each other?
  - Threshold-based (e.g., >15 points = good)?

**Issue 3: Accuracy Considerations**
- 68.5% accuracy is moderate for sentiment analysis
- Consider exploring:
  - Testing other models
  - Using a 3-category scheme (positive/neutral/negative) instead of binary

**Issue 4: Dataset Scope**
- You're limiting to only a slice of the 2024 WNBA regular season (data ends in October, 2024)
- This excludes their final college season (when media attention peaked)
- **Suggestion:** Consider focusing on their final NCAA season (2023-24) for a more complete picture, or justify why the truncated 2024 WNBA season alone is sufficient

### Next Steps:
- Document specific AI model used for sentiment analysis
- Define performance metrics explicitly (add to Section 3)
- Consider testing alternative sentiment models if 68.5% is insufficient for your claims
- Justify dataset scope decision

---

## 3. Preliminary Variable Operationalization

### Area for Development: Performance Operationalization Missing

Your table includes sentiment and likes, but **performance metrics are not yet operationalized**.

**Suggestion to Add:**

| Construct | Operational Definition | Data Source / Indicator |
|-----------|------------------------|-------------------------|
| Good performance (weekly) | Week where player had above-median PPG, rebounds, and assists relative to their season average | Official WNBA game stats aggregated weekly |
| Bad performance (weekly) | Week where player had below-median PPG, rebounds, and assists relative to their season average | Official WNBA game stats aggregated weekly |

**OR** if you're doing comparative:

| Construct | Operational Definition | Data Source / Indicator |
|-----------|------------------------|-------------------------|
| Better performance (comparative) | Week where player outperformed the other athlete in at least 2 of 3 categories: PPG, total rebounds, assists | Official WNBA game stats, Clark vs. Reese weekly comparison |

### Next Steps:
- Add performance operationalization to Section 3 table
- Specify exact metrics (PPG? Rebounds? Assists? Field goal %?)
- Clarify: individual performance or comparative performance?

---

## 4. Proposed Analyses

### Area for Refinement: Adding Statistical Specificity

**Current:** "Examine relationship between performance (good vs. bad) and comment sentiment (positive vs. negative)"

**What Would Strengthen This:**
- Which statistical test? (Chi-square? Logistic regression?)
- What's your hypothesis? (Do you expect performance to predict sentiment?)
- What about athlete differences? (Is the performance-sentiment relationship the same for Clark vs. Reese?)

**Suggested Refinement:**

| Analysis Type | Description | RQ Addressed | Expected Finding |
|---------------|-------------|--------------|------------------|
| Chi-square test | Compare proportion of positive vs. negative comments in good performance weeks vs. bad performance weeks (for each athlete separately) | RQ 1 | We expect higher % of positive comments during good performance weeks |
| Logistic regression | Model: Sentiment (0/1) ~ Performance (0/1) + Athlete (Clark/Reese) + Interaction | RQ 1 | We expect performance effect may differ by athlete (interaction term) |

### Next Steps:
- Specify statistical test(s)
- State your hypothesis/expected findings
- Consider interaction effects (does performance-sentiment relationship differ by athlete?)

---

## 5. Limitations & Potential Issues

### Strengths
- Honest acknowledgment of sentiment analysis limitations
- Recognition of binary performance simplification

### Suggestions for Addressing Limitations

**For Sentiment Analysis Issues:**
- Conduct error analysis: Which types of comments are most frequently misclassified?
- Consider hybrid approach: AI classification + manual review of borderline cases
- Report results with sensitivity analysis (e.g., "Results hold even with 70% error rate")

**For Binary Performance Simplification:**
- Create sensitivity check using continuous performance metrics
- Or use 3 categories: good/average/bad

### Next Steps:
- Add concrete plan for how you'll address each limitation during analysis
- Consider additional limitation: Selection bias (not all games had posts)

---

## 6. Ethical Considerations

### Strengths
- Recognition of public data limitations
- Commitment to anonymization

### Additional Considerations:

**Sampling Bias:**
- You correctly note: "not all games came with posts so the sample itself is biased by default"
- **Implication:** Posts may only occur after exceptional performances or controversies
- **Suggestion:** Acknowledge this limits generalizability (you're studying posted-about games, not all games)

**Interpretation Responsibility:**
- If you find differences in sentiment between athletes, how will you frame this?
- Consider focusing on systemic patterns in audience discourse rather than individual athlete characteristics
- Frame findings as audience behavior patterns, not athlete-specific judgments

### Next Steps:
- Add limitation: "We analyze only games where athletes posted, which may skew toward notable performances or events"
- If findings reveal patterns by athlete, consider framing as audience discourse patterns

---

## 7. Group Role Assignments

Clear and complete. Thank you for providing role assignments.

---

## 8. Data Visualization Plan

### Note: Section Missing from Your Plan

You will need to create at least **one visualization** addressing your RQ.

**Suggested Visualizations for Longitudinal Performance-Sentiment Data:**

1. **Dual-axis line chart:**
   - X-axis: Week number (Week 1-20 of WNBA season)
   - Y-axis 1 (left): Performance metric (e.g., PPG)
   - Y-axis 2 (right): % positive comments
   - Two lines: one for Clark, one for Reese
   - **What it shows:** Whether comment sentiment tracks with performance over time

2. **Grouped bar chart:**
   - X-axis: Good performance weeks vs. Bad performance weeks
   - Y-axis: % positive comments
   - Two bars per group: Clark vs. Reese
   - **What it shows:** Performance-sentiment relationship by athlete

3. **Scatter plot with trend lines:**
   - X-axis: Weekly performance score
   - Y-axis: % positive comments that week
   - Points colored by athlete
   - **What it shows:** Whether performance-sentiment correlation differs by athlete

### Next Steps:
- Choose one visualization type from above (or propose your own)
- Create initial draft
- Add to Section 8: Primary goal, design rationale, verification method

---

## 9. AI-Assisted Work Documentation & Verification

### Strengths
- Thoughtful reflection on AI as collaborative tool
- Recognition of need for verification

### Questions to Consider:

1. **Challenges with Antigravity:**
   - What roadblocks did you encounter when using Antigravity for data analysis?
   - Did you face installation issues? Code errors? Unexpected outputs?

2. **When AI Was Less Helpful:**
   - Were there moments where AI suggestions led you in different directions?
   - Did AI generate code/functions that needed correction?
   - How did you identify and correct these issues?

3. **Verification Specifics:**
   - You mention you "will" verify, but you've already done verification for sentiment analysis
   - **Document your actual verification:** You mention 200 manual checks in Section 2. Include this in Section 9
   - Fill in your actual iteration count (how many prompt refinements?)

### Next Steps:
- Document **actual** verification steps you've already taken (e.g., 200 manual checks)
- Fill in iteration counts (how many times did you refine prompts?)
- Reflect on specific challenges encountered, not just general workflow

---

## Summary: Moving Forward

**During Week 3 Class (Today):**
- Share your visualization and get peer feedback
- Discuss RQ-context alignment options during 1-on-1 consultation
- Begin refining operationalization with instructor guidance
- Start preliminary data exploration

**Questions to Bring to 1-on-1 Consultation:**
- "Should we keep race in our RQ or focus only on performance?"
- "Which performance metrics are most defensible?"
- "Is 68.5% accuracy sufficient for our claims, or should we test other models?"

**This Week (After Class):**
- Finalize decision on RQ-context alignment
- Document specific AI model used for sentiment analysis
- Add performance metrics to Section 3 operationalization table
- Refine visualization based on class feedback

**Next Week (Week 4):**
- Add statistical tests (or other analytical alternatives) and expected findings to Section 4
- Test alternative sentiment models if needed
- Conduct full analysis with refined operationalization
- Prepare preliminary results for interpretation

---

**Overall:** Your technical execution is strong. Focusing on the alignment between your RQ and context will strengthen your conceptual framework and make your project more coherent. Once that's clarified, the rest of your plan can proceed smoothly.