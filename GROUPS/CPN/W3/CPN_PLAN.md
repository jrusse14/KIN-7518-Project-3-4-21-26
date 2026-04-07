Project 1: Group Research Plan

**Course:** KIN 7518 Social Issues in Sport
**Due:** Monday, January 27, 2026 by 11:59 PM
**Submission:** Email to yqian@lsu.edu — One member submits, **CC all group members**
**Format:** Markdown (.md) file
**File Naming:** `CPN_PLAN.md` (see group names below)


1\. Research Questions & Significance

For each research question, address all three components below. The goal is to show the logical connection between the phenomenon you're investigating, the question you're asking, and why it matters.

RQ 1

**The Question:**
How do Caitlin Clark’s and Angel Reese’s performance and image affect positive and negative comments on their own social media? 

**The Context:**
What phenomenon, debate, or gap does this question address?

This question  reveals the relationship between fans attitude towards performance and athletes’ profiles with specific representative of athletes. This topic is vital due to the significant media attention that Clark and Reese received during their transition from college careers towards the WNBA. This attention has led to public discussions about race, representation, and how female athletes are portrayed in the media.

**Why It Matters:**
Athletes, media, researchers, and fans are all interested in this question because it reveals how content created by athletes influences public perception and media representation, and how the performance under combination of certain profiles can affect fans or audiences’ attitude. As women's basketball is receiving increased attention, this representative phenomenon can cause significant impact from shaping narratives, branding, and fairness in the sport. Key concerns include empowering athletes, ensuring accurate and fair representation—particularly for Black women athletes—and developing better media strategies to promote equality in sports coverage.

2\. Dataset Selection & Justification

Identify which dataset you are using and explain why.

**Dataset Choice:** Clark-Reese (ARCC)

**Justification:**
The ARCC dataset is ideal because it connects Instagram posts from Angel Reese and Caitlin Clark with the sentiments expressed in audience comments. It offers plenty of information, including post data, comments, and visual content. This allows us to effectively measure and compare the performance of their posts and images. Furthermore, having data from both athletes over time allows for meaningful comparisons and the identification of patterns, rather than just isolated observations. In this case, we will be using AI model to determine the audience attitude based on the comments and using binary variables to indicate the attitude (i.e. 1 \= positive, 0 \= negative) based on the season data from ARCC\_INS\_COMMENT. Also, we will utilized the like numbers to indicate how strong the feelings.

Meanwhile, to collect information for performance, we will be collecting personal performance statistics from certain time point as the posts/comments were collected. After the data were collected, we will be comparing the performance data between two athletes and use binary variables to indicate the performance (i.e. 1 \= good, 0 \= bad). In this case, we can use this as a variable to determine the relationship between performance and audience’s attitude.

Data selection and preprocessing were conducted in four steps. First, the official 2024 WNBA season schedule was collected to define the temporal boundaries of the regular season. All comment data generated outside the regular season period (e.g., preseason, Olympic break, postseason) were removed, and only comments posted during regular-season game weeks were retained for analysis. This step ensured temporal consistency between fan discourse and on-court performance.

Second, full 2024 regular-season game-by-game performance data for AR and CC were downloaded from official score sources. Using antigravity, both players’ performance data were aggregated to the weekly level. Each comment was then assigned a weekly performance comparison label based on the relative on-court performance of the two players during that week (better performance \= 1; worse performance \= 0).

Third, the textual content of each comment was processed using antigravity for sentiment analysis. Comments classified as positive were coded as 1, while negative comments were coded as 0, generating a binary sentiment variable aligned with the performance comparison labels.

Finally, to assess the validity of the automated sentiment classification, a random subsample of 200 comments was manually coded. Manual coding achieved an accuracy rate of 68.5% (137/200) compared with the automated labels, indicating moderate agreement and acceptable reliability for exploratory analysis.

**Key files you plan to use:**

* ARCC\_INS\_COMMENT.xlsx


3\. Preliminary Variable Operationalization

For your main constructs, describe how you will measure or identify them in the data.

| Construct  | Operational Definition  | Data Source / Indicator  |
| :---- | :---- | :---- |
| Performance-related content  | Data featuring athletic performance (e.g. gameplay ~~,~~ statistics)  | Official game stats.  |
| Positive sentiment  | Comments expressing support, admiration, and encouragement  | General tone of the post. And the meaning of the post.   |
| Negative sentiment  | Comments expressing criticism, hostility, and disagreement  | General tone of the post. And the meaning of the post.   |
| Likes  | The number of the post  |   |



4\. Proposed Analyses

Outline the analytical approaches you plan to use. For each, explain how it addresses your RQ.

| Analysis Type  | Description  | RQ Addressed  |
| :---- | :---- | :---- |
| Cross-analysis  | Examine relationship between performance (good vs. bad) and comment sentiment (positive vs. negative)  | RQ 1  |




5\. Limitations & Potential Issues

Identify at least 2-3 limitations or challenges with your approach. Be honest—acknowledging limits is a strength, not a weakness.

First, the sentiment analysis relied on automated classification using antigravity, which may not fully capture nuanced meanings such as sarcasm, humor, emoji use, or context-specific slang commonly present in sports-related comments. Although manual validation showed moderate accuracy (68.5%), misclassification of complex emotional expressions may still have influenced the observed associations between performance and sentiment.

Second, weekly performance comparisons were reduced to a binary indicator (better \= 1, worse \= 0), which simplified continuous performance differences into categorical labels. This may have obscured finer-grained variations in performance magnitude and limited the sensitivity of the analysis.![Shape][image6]

6\. Ethical Considerations

Address the following:

* **Privacy**: Are you analyzing public or private data? Any risks of identifying individuals?
* A: We are analyzing only public Instagram posts and public comments, but we will anonymize all usernames and avoid unnecessary harmful content.
* **Harm**: Could your analysis reinforce stereotypes or cause harm to groups discussed?
* A: Our analysis could reinforce stereotypes or cause harm if differences between athletes are misinterpreted. We will also minimize harm by focusing on patterns rather than extreme examples.
* **Bias**: What biases might exist in your data or your interpretation?
* A: Bias may arise from our own perspectives, and the dataset’s selection of extreme voices.


7\. Group Role Assignments

Specify who is responsible for what. Titles are flexible, but responsibilities must be clear.

| Role  | Group Member  | Primary Responsibilities  |
| :---- | :---- | :---- |
| Data Lead  | Andy Ceballos  | \[e.g., Data cleaning, preprocessing, file management\]  |
| Methods Lead  | Jacob Pickett  | \[e.g., Analysis design, tool implementation, documentation\]  |
| Theory Lead  | Yixin Nie  | \[e.g., Literature integration, RQ refinement, interpretation\]  |


8\. AI-Assisted Work Documentation & Verification

If you used AI tools (Antigravity, Cursor, ChatGPT, etc.) for any part of this plan, document your process and verification methods.

**Tools Used:**
Which AI tools/IDEs did you use, and for what purpose?

We used ChatGPT and Cursor to conduct our planning for the project. Also, we will use Cursor to identify the sentiment type from the data set based on the comment content.

**Verification Methods:**
How did you verify AI outputs were accurate and appropriate?

* **Code Explanation:**
* We will ask AI to explain what each line/section of code does
* We will review explanations and understand the logic
* 
* **Output Validation:**
* We will cross-check AI calculations against manual spot-checks (specify \# of checks: \_\_\_)
* We will verify outputs make logical sense given my data
* We will compare AI results with what I know about my dataset
* **Iterative Refinement:**
* Number of prompt iterations before getting usable output: \_\_\_
* Key refinements made: \[describe\]

**Learning Reflection:**
What did you learn from working with AI on this project? What did examining the AI-generated code/outputs teach you?

Working with AI taught us to see it as a helpful partner for coming up with ideas, finding missing parts, and explaining complicated choices. Looking at what it produces showed us how important it is to check and think carefully about AI-made code and content instead of just trusting it. Overall, we learned that AI works best when we are involved, give clear instructions, and improve its outputs thoughtfully.


