# Week 3 Feedback: TheMcGradys Group  
**Reviewer:** Dr. Qian  
**Date:** January 27, 2026

---

## Overall Assessment

Your submission is incomplete. Multiple sections contain placeholder text ("[Your response here]") and critical deliverables are missing, including the required visualization. This plan needs substantial work before it's ready for the work session. Please prioritize completing all sections.

---

## 1. Research Questions & Significance

### Issue: RQ Needs Major Refinement

**Current RQ:** "Does the Sexualization of Social Media posts increase engagement for female athletes?"

**Problems:**

1. **Spelling/Grammar**: "increse" should be "increase"; "sexualization" capitalization inconsistent
2. **Missing specificity**: Which female athletes? Which platforms? What counts as "sexualization"?
3. **Context is vague**: "Growing issue" and "marketing opportunities" mentioned but not developed
4. **"Why It Matters" is incomplete**: "Positive and negative effects" stated but not explained

**Suggested Revision:**

**RQ:** "Do Instagram posts featuring revealing clothing or sexualized imagery by Angel Reese and Caitlin Clark receive higher engagement (likes and comments) compared to non-sexualized posts?"

**Context Enhancement:**
"Female athletes increasingly use social media for self-branding and endorsement opportunities. However, research documents persistent sexualization of female athletes in media (objectification theory, male gaze scholarship). Athletes face a dilemma: Sexualized content may increase engagement and visibility, but potentially reinforces harmful gender stereotypes and reduces focus on athletic achievement. Few studies quantitatively compare engagement patterns for sexualized vs. non-sexualized athlete-generated content."

**Why It Matters:**
"Understanding engagement patterns for sexualized content informs athlete decision-making about self-presentation strategies. For sport organizations and sponsors, these patterns reveal audience preferences and potential marketing tensions. For researchers, this addresses gaps in understanding athlete agency in self-sexualization vs. external objectification."

---

## 2. Dataset Selection & Justification

### Issue: Justification Contains Errors

**Current:** "This dataset...tracks post engagement as well as the sexual nature of the individual posts."

**Problem:** ARCC does NOT automatically code "sexual nature of posts." The dataset contains:
- POST data (images, captions, engagement metrics)
- VISUAL ANALYSIS data (ARCC_INS_VA.xlsx may have appearance/clothing coding, but check what's actually in it)

**You will need to CODE posts as sexualized vs. not**—this should be in your operationalization section.

**Corrected Justification:**
"The ARCC dataset is appropriate because ARCC_INS_POST contains engagement metrics (likes, comments) and post images/captions for both Reese and Clark. The ARCC_INS_VA file includes visual analysis variables that may assist in categorizing post content. This allows us to compare engagement levels across post types for each athlete."

---

## 3. Preliminary Variable Operationalization

### Critical Issue: Table Is Incomplete and Incorrect

**Current Table:**
| Construct | Operational Definition | Data Source |
|-----------|------------------------|-------------|
| [e.g., Skill-based discourse] | [e.g., Comments mentioning...] | [e.g., Keyword search...] |
| [Instagram] | [Likes and comments on posts considered revealing] | [Likes and comments in ARCC_INS_POST.xlsx] |

**Problems:**
1. First row is just an example that should be deleted
2. "Instagram" is not a construct—it's a platform
3. "Posts considered revealing" is vague—WHO considers them revealing? What criteria?

**Required Table:**

| Construct | Operational Definition | Data Source / Indicator |
|-----------|------------------------|-------------------------|
| Sexualized post | Posts featuring revealing clothing (swimwear, crop tops, body-con dresses), suggestive poses, or appearance-focused captions | Manual coding of images/captions in ARCC_INS_POST.xlsx + ARCC_INS_VA.xlsx variables |
| Non-sexualized post | Posts featuring basketball content, everyday clothing, or non-appearance-focused captions | Residual category |
| Engagement level | Total likes + comments per post | Like_count and Comment_count fields in ARCC_INS_POST.xlsx |

**Critical Need:**
- Define SPECIFIC criteria for "sexualized" (clothing types, poses, caption themes)
- Explain who will code posts and how (manual review, team consensus, etc.)
- Address inter-rater reliability (will multiple people code to ensure consistency?)

---

## 4. Proposed Analyses

### Issue: Table Incomplete and Vague

**Current:**
| Analysis Type | Description | RQ Addressed |
|---------------|-------------|--------------|
| [e.g., Keyword frequency analysis] | [e.g., Count occurrences...] | [RQ 1] |
| [Engagement numbers on posts] | [Number of likes and comments on revealing vs. non-revealing posts] | [RQ 1] |

**Problems:**
1. First row is example text that should be deleted
2. "Engagement numbers" isn't an analysis—it's just data collection
3. Missing statistical test

**Required Table:**

| Analysis Type | Description | RQ Addressed | Statistical Test |
|---------------|-------------|--------------|------------------|
| Post content coding | Categorize each post as sexualized or non-sexualized using defined criteria | RQ 1 | N/A (coding step) |
| Engagement comparison | Calculate mean engagement (likes + comments) for sexualized vs. non-sexualized posts for each athlete | RQ 1 | Independent samples t-test |
| Effect size calculation | Determine magnitude of engagement difference between post types | RQ 1 | Cohen's d |

---

## 5. Limitations & Potential Issues

### Issues

**Current:**
1. "More Data available of Angel Reese than Caitlin Clark"
2. "Some post about their professional careers could skew data regarding sexual explicit posts"
3. "[Limitation 3]" (Incomplete)

**Problems:**

**Limitation #1 is actually important** but needs explanation:
- WHY is there more Reese data? More posts? Longer time period?
- How will you address this? Analyze proportions rather than raw counts? Sample equal numbers of posts from each athlete?

**Limitation #2 is unclear:**
- What does "professional career posts" mean?
- Do you mean: Basketball-related posts might be miscoded as non-sexualized even if they show revealing uniforms?
- Clarify: "Distinguishing basketball content from sexualized content is challenging when athletes wear revealing uniforms or athletic wear. We will address this by [specific coding rule]."

**Limitation #3 is blank.**

**Needed Limitations:**
1. **Unequal post volume between athletes**: "AR has more posts than CC (specify numbers). We will control for this by comparing PROPORTIONS of high-engagement posts rather than raw counts."
2. **Subjectivity in coding sexualization**: "Defining 'revealing' or 'sexualized' involves subjective judgment. We will mitigate this through explicit coding rules and inter-rater reliability testing."
3. **Correlation vs. causation**: "Higher engagement on sexualized posts doesn't prove sexualization CAUSES engagement. Other factors (post timing, content quality, current events) may confound results."
4. **Platform-specific**: "Analyzing only Instagram may not generalize to other platforms (TikTok, Twitter) where engagement patterns differ."

---

## 6. Ethical Considerations

### Issue: Response Needs Development

**Current:** "Privacy: we are analyzing public data...Harm: our analysis could reinforce stereotypes...Bias: the public might assume that all female athletes would post these things..."

**Problems:**
1. Privacy section is fine
2. Harm section acknowledges risk but doesn't state mitigation
3. Bias section confuses data bias with public bias

**Required Revisions:**

**Harm (add mitigation):**
"Our analysis could unintentionally suggest that sexualization is an effective or necessary strategy for female athletes, reinforcing harmful norms. To mitigate this, we will:
- Frame findings within critical gender theory context
- Avoid normative language suggesting athletes 'should' sexualize content
- Emphasize athlete agency while acknowledging structural pressures
- Discuss broader implications for sport culture and gender equity"

**Bias (clarify researcher vs. audience bias):**
"Potential biases in our analysis include:
- Researcher subjectivity in defining 'sexualized' content (addressed through explicit coding criteria and inter-rater reliability)
- Our own assumptions about athlete intent or audience motivations
- Platform algorithms that may amplify certain content types independent of user preferences
We will address these by documenting all coding decisions and acknowledging interpretation limitations."

---

## 7. Group Role Assignments

Roles are assigned. Good.

---

## 8. Data Visualization Plan

### Critical Issue: ALL SECTIONS INCOMPLETE

**Current Status:**
- Primary Goal: "[Your response here]"
- Visualization Description: "[Your response here]"
- Design Rationale: "[Your response here]"
- Verification: All boxes unchecked
- The Visualization: "[Insert visualization or link]"
- Interpretation: "[Your response here]"

**This Entire Section Is Missing**

**Required for Week 3 Submission:**

**Primary Goal:**
"Show whether sexualized posts receive higher engagement than non-sexualized posts for AR and CC."

**Visualization Description:**
"Grouped bar chart comparing mean engagement (likes + comments) for sexualized vs. non-sexualized posts. Two groups of bars: one for AR, one for CC. Each group has two bars: sexualized posts (one color) and non-sexualized posts (different color)."

**Design Rationale:**
"Grouped bar chart allows direct visual comparison of engagement levels across post types and athletes. Using mean engagement controls for differing post volumes."

**Create the visualization** using ANY preliminary data—even if you've only coded 20 posts per athlete for now.

---

## 9. AI-Assisted Work Documentation & Verification

### Critical Issue: ENTIRE SECTION BLANK

**Current:** "[Your response here]" for all fields

**If you used NO AI tools:**
- State: "No AI tools were used in creating this plan."

**If you DID use AI tools but didn't document:**
- This is **required** if you used ANY AI assistance
- Go back and document: Which tools? For what purpose? How did you verify outputs?

---

## Summary: Moving Forward

**IMMEDIATE PRIORITIES (Before or During Week 3 Class):**

1. **Complete ALL placeholder sections** ("[Your response here]" must be replaced)
2. **Create visualization** (required deliverable—missing entirely)
3. **Define sexualization criteria** explicitly (what counts as sexualized vs. not?)
4. **Revise RQ** for specificity and clarity
5. **Fix operationalization table** (remove example rows, add actual constructs)
6. **Fix proposed analyses table** (remove examples, add statistical tests)
7. **Complete AI documentation** (if AI was used)

**This Week (After Class):**
- Develop explicit coding scheme for sexualized vs. non-sexualized posts
- Code sample of posts (20-30 per athlete minimum) to create pilot visualization
- Test inter-rater reliability (have two team members code same posts, compare results)
- Revise ethical considerations to include mitigation strategies

**Next Week (Week 4):**
- Complete full post coding for both athletes
- Run t-test comparing engagement levels
- Calculate effect size (Cohen's d)
- Interpret findings within gender theory framework

---

**Overall:** Your submission is incomplete and needs immediate attention. Multiple required sections are blank or contain placeholder text. The required visualization is entirely missing. Your RQ has potential but needs substantial refinement. Use Week 3 class time to get consultation on completing these sections. This plan needs significant work before you're ready for the work session.

**Action Items (Priority Order):**
1. Create visualization (required deliverable)
2. Complete all "[Your response here]" sections
3. Revise RQ for specificity
4. Fix operationalization and analyses tables
5. Develop explicit coding criteria for sexualization
