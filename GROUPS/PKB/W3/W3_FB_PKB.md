# Week 3 Feedback: PKB Group  
**Reviewer:** Dr. Qian  
**Date:** January 27, 2026

---

## Overall Assessment

Your plan demonstrates strong conceptual clarity with a well-focused research question. The framing analysis approach (athletic performance vs. personal attributes vs. legitimacy) is theoretically sound and directly addresses a meaningful phenomenon in women's sports coverage. However, you need to complete your visualization and provide more specific keyword lists for operationalization.

---

## 1. Research Questions & Significance

### Strengths
- **Excellent RQ specificity**: You ask about "framing" with three clear categories (athletic performance, personal attributes, legitimacy)
- **Clear subjects**: Angel Reese vs. Caitlin Clark comparison
- **Timely context**: Women's basketball growth and ongoing rivalry narrative
- **Platform-specific**: Instagram comments (manageable scope)

### Minor Refinement Suggestion

**"Why It Matters" repeats "The Context":**
- You say in context: "analyzing comments can provide insights into public discourse"
- You say in "Why It Matters": "analyzing comments can provide insights into public discourse"
- This is the same statement

**Suggested Enhancement for "Why It Matters":**
"Understanding how these athletes are framed differently in public discourse has implications for their marketability, endorsement opportunities, and career trajectories. If one athlete is framed primarily through personal attributes while the other through athletic performance, this reflects and potentially reinforces gendered and racialized stereotypes in sports media. This analysis can inform athletes, agents, and organizations about managing public perception and challenging limiting narratives."

---

## 2. Dataset Selection & Justification

### Issue: Justification Lacks Substance

**Current:** "Most relevant to our research interest. None of us have experience with fit-mom dataset."

This doesn't explain WHY ARCC is appropriate for your specific RQ.

**Suggested Revision:**
"The ARCC dataset is appropriate because it contains extensive Instagram comment data for both Angel Reese and Caitlin Clark, allowing direct comparison of how they are framed by audiences. The temporal coverage (2017-2024) spans their college and professional careers, capturing the evolution of their rivalry narrative. Using only ARCC_INS_COMMENT.xlsx provides platform consistency and manageable scope for our framing analysis."

### Missing Information:
- **Temporal scope**: Are you analyzing all comments (2017-2024) or focusing on specific period?
- **Sample size**: How many comments per athlete will you analyze?

---

## 3. Preliminary Variable Operationalization

### Strengths
- Three clear constructs aligned with RQ
- Appropriate data source identified

### Issue: Missing Keyword Lists

You specify "keyword search" but don't provide keywords. Here's what you need:

| Construct | Operational Definition | Example Keywords | Data Source |
|-----------|------------------------|------------------|-------------|
| Athletic Performance | Comments mentioning stats, gameplay, skills, achievements | "points," "rebounds," "assists," "defense," "ROTY," "MVP," "All-Star," "game," "championship," "stats" | ARCC_INS_COMMENT.xlsx |
| Personal Attributes | Comments mentioning appearance, personality, demeanor, fashion | "pretty," "beautiful," "style," "outfit," "hair," "personality," "attitude," "classy," "cocky" | ARCC_INS_COMMENT.xlsx |
| Legitimacy | Comments questioning or affirming deservingness of recognition | "deserve," "earned," "overrated," "goat," "best," "real," "fraud," "legitimate," "hype" | ARCC_INS_COMMENT.xlsx |

### Additional Considerations:
- **Overlapping comments**: What if a comment mentions both performance AND appearance? How will you code?
- **Coding scheme**: Will you use exclusive categories (one per comment) or allow multiple tags?

---

## 4. Proposed Analyses

### Strengths
- Keyword frequency analysis directly addresses RQ
- Sentiment analysis adds valuable dimension

### Areas for Refinement

**Analysis 1: Keyword Frequency**
- Add specificity: "Calculate proportion of comments in each category for each athlete separately. Use chi-square test to determine if category distributions differ significantly between athletes."
- Add hypothesis: "We expect Clark to receive higher proportion of performance-based comments, while Reese may receive higher proportion of personal attribute comments."

**Analysis 2: Sentiment Analysis**
- Add detail: "Within each framing category, analyze sentiment (positive/negative/neutral). Example question: Are personal attribute comments more positive or negative for each athlete?"
- Specify tool: Which sentiment analysis tool/model will you use?

**Missing Analysis:**
- **Temporal comparison**: Do framing patterns change over time (college vs. WNBA)?
- **Post-type control**: Do framing patterns differ based on what the POST is about?

---

## 5. Limitations & Potential Issues

### Strengths
- Recognition that post content influences comment type
- Acknowledgment of ML model accuracy concerns
- Awareness of temporal confounds (current form affecting comments on old posts)

### Suggestions for Addressing

**Limitation #1: Post content influence**
- Mitigation: "We will code post types (basketball vs. non-basketball content) and analyze if framing differences persist even when controlling for post type. If Reese's non-basketball posts get appearance comments while Clark's non-basketball posts get performance comments, this reveals framing bias."

**Limitation #2: ML model accuracy**
- Mitigation: "We will manually validate sentiment coding on random sample of 100 comments per athlete (200 total). Report accuracy rate and adjust interpretation accordingly."

**Limitation #3: Temporal confounds**
- This is a good observation. Add: "We will timestamp comments relative to post date to identify if patterns change based on current events."

### Missing Limitations:
- **Keyword limitations**: Keyword search misses context (sarcasm, nuance)
- **Platform bias**: Instagram comments may differ from Twitter/YouTube
- **Sample representativeness**: Are vocal commenters representative of broader public?

---

## 6. Ethical Considerations

### Strengths
- Recognition that data is public
- Commitment to objectivity

### Issues Needing Development

**Privacy:**
- You mention "risk of identifying individuals through user ID"
- Suggested addition: "We will not report specific usernames or link individual commenters to patterns. Analysis focuses on aggregate trends, not individual behavior."

**Harm:**
- Good intention stated, but add mitigation: "We will frame findings as patterns in audience discourse, not as characteristics of the athletes themselves. We will avoid language suggesting either athlete 'causes' or 'deserves' certain framing."

**Bias:**
- You mention "physical appearance bias" but this seems like a finding, not an ethical concern
- Replace with: "Our own preconceptions about these athletes may influence coding decisions. To mitigate bias, team members will independently code sample comments and compare results for inter-rater reliability."

---

## 7. Group Role Assignments

Clear and complete. Well done.

---

## 8. Data Visualization Plan

### Issue: Missing Visualization

**Current status:** "[Insert visualization or link]" and "[Your response here]"

**You described what you'll create** (bar chart comparing categories) but **didn't include it.**

**Priority for Week 3:** Create the visualization you described!

### Suggested Visualization Structure:

**Grouped bar chart:**
- X-axis: Three categories (Athletic Performance, Personal Attributes, Legitimacy)
- Y-axis: % of comments
- Two bars per category: Clark (one color) vs. Reese (different color)

**Alternative: Stacked bar chart:**
- Two bars (Clark vs. Reese)
- Each bar shows proportion breakdown of three categories
- Easier to see overall framing profile per athlete

**What Your Interpretation Should Include:**
- Which athlete receives more performance-based framing?
- Which receives more personal attribute framing?
- Are legitimacy challenges more common for one athlete?
- Are differences statistically significant? (add error bars or p-values)

---

## 9. AI-Assisted Work Documentation & Verification

### Strengths
- Clear documentation of tools used (ChatGPT for brainstorming, Antigravity for formatting)
- Honest reflection on AI as "support tool" not "brain of group"
- Iteration count provided (2 iterations for visualization)

### Areas for Enhancement

**For "Code Explanation" section:**
- You checked boxes but didn't describe what you did
- Add: "We asked ChatGPT to generate a mockup bar chart showing hypothetical data for our three categories. This helped us visualize what our final analysis should look like."

**For "Output Validation" section:**
- You write: "No definitive output validation...needed"
- This undersells your work. You DID validate conceptually.
- Revised: "We validated AI suggestions against our research question to ensure alignment. We modified AI-generated visualization mockup to include correct category names and athlete labels."

**Missing:**
- Example prompt you used: "We prompted ChatGPT: '[exact prompt]'"
- What worked and what didn't

---

## Summary: Moving Forward

**During Week 3 Class (Today):**
- **Priority #1**: Create and share your actual visualization (not just description)
- Discuss keyword lists and coding scheme during 1-on-1 consultation
- Begin preliminary keyword search to test if your categories work
- Get feedback on sentiment analysis tool choice

**Questions to Bring to 1-on-1 Consultation:**
- "What sentiment analysis tool should we use? How do we validate it?"
- "Should we allow comments to be coded in multiple categories or force exclusive coding?"
- "How do we handle sarcasm and context in keyword searches?"

**This Week (After Class):**
- **Create the visualization** (this is your required deliverable!)
- Finalize keyword lists with example terms
- Decide on coding scheme (exclusive vs. multiple tags)
- Test keyword search on small sample to refine lists

**Next Week (Week 4):**
- Conduct full keyword frequency analysis
- Run sentiment analysis with validation
- Test statistical significance of framing differences
- Analyze if patterns hold when controlling for post type

---

**Overall:** Your RQ is excellent and your conceptual approach is sound. Your biggest priority is creating the actual visualization you described. Once that's complete, refining your keyword lists and defining your coding scheme will make your analysis much stronger. You have a clear path to meaningful findings about differential framing.
