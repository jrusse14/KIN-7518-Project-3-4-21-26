# KIN 7518: Guide to Data Resources & Methodological Philosophy

## Course Philosophy: From Argument to Evidence

This course is designed to move graduate students from talking about social issues in sport to demonstrating how claims are built, constrained, and justified through data. Rather than emphasizing lectures or technical virtuosity, the course centers on structured, hands-on projects in which students execute complete analytical workflows—cleaning data, operationalizing concepts, justifying methodological choices, interpreting results, and confronting ethical limits. 

The intention is to make visible the gap between conceptual arguments and empirical execution. Students learn that social issues in sport are analytically complex, methodologically demanding, and ethically bounded—and that credible insight depends less on polished outputs than on transparent reasoning and defensible decisions. 

Across multiple reset-based projects, students gain repeat exposure to the same analytic logic applied to different substantive domains, reinforcing transfer rather than rote learning. The instructor’s role is deliberately repositioned from content transmitter to methodological arbiter: providing exemplars, detailed guidance, and diagnostic feedback that shape students’ analytical judgment while preserving student ownership of the work. 

By the end of the course, students should be able to independently evaluate social claims in sport, understand what data can and cannot support, and apply data-informed reasoning in academic, professional, and public contexts.

---

## Guide to Project Resources

This document maps the course's "friendly" dataset names to the actual files and folder structures you will find in the course repository. Use this to locate your data and relevant theoretical readings.

### Project 1: Visibility, Representation, and Inequality
**Location:** `DATA&RESOURCES/PROJECT1`

#### Data Files (The "Raw" Materials)
*   **Clark-Reese / Women's Sport Discourse** (Folder: `ARCC_INS`)
    *   `INS_ARCC_POST.xlsx`: Instagram posts data.
    *   `INS_ARCC_COMMENT.xlsx`: Massive comment dataset for analysis.
    *   `INS_ARCC_VA.xlsx`: Visual analysis/metadata.
*   **Fit-Mom Discourse** (Folder: `FITMOM_YT`)
    *   `FITMOM_VIDEO.xlsx`: YouTube video metadata.
    *   `FITMOM_COMMENT.xlsx`: Comments on "Fit Mom" content.

#### Reference Readings (Theoretical Context)
*   *Agha & Berri (2023)*: Demand for basketball (WNBA vs NBA).
*   *Antunovic & Bruce (2025)*: Feminist Media Scholarship response.
*   *Baker et al. (2022)*: Sport brandscape review.
*   *Bredikhina et al. (2024)*: Authenticity negotiation & personal brands.
*   *Bredikhina et al. (2025)*: Determinants of women football players’ popularity.
*   *Doyle et al. (2022)*: Athlete branding & consumer engagement on Instagram.
*   *Edelblum et al. (2025)*: The Beauty Backfire Effect (Fitfluencer study).
*   *Fink (2015)*: Female athletes & sport media commercial complex.
*   *Freitas et al. (2024)*: Motherhood and consumption.
*   *Harris & Brison (2023)*: Elite female athletes' branding strategies.
*   *Johnson et al. (2025)*: "I’m not just a mother" (Self-presentation).
*   *Keller (2025)*: Evolution of modern branding.
*   *Lopes & Nagel (2025)*: Women professional athletes & personal brands.
*   *Wanless et al. (2024)*: Brand-Related Sport Consumer Twitter topics.
*   *Xu (2025)*: Selfie Scores & Athlete Self-Presentation.

---

### Project 2: Legitimacy, Power, and Institutional Boundaries
**Location:** `DATA&RESOURCES/PROJECT2`

#### Data Files
*   **The Savannah Bananas** (Folder: `BANANAS`)
    *   `BANANAS_YT_VIDEO.xlsx`: YouTube video metadata.
    *   `BANANAS_YT_COMMENT.xlsx`: Audience comments/reactions.
*   **Esports: Asian Games vs. World Cup** (Folder: `ESPORTS`)
    *   `ESPORTS_UGC.xlsx`: User Generated Content (The primary comparative dataset).
    *   `ESPORTS_TOPICS.xlsx`: Topic modeling output.
*   **TGL Golf League** (Folder: `TGL`)
    *   `TGL_VIDEO.xlsx`: YouTube coverage of the launch.
    *   `TGL_COMMENT.xlsx`: Public discourse/reaction.

#### Reference Readings
*   *Bae et al. (2023)*: LPGA Tour Self-Presentation on Instagram.
*   *Cheng & Zhang (2024)*: Reputation burning & brand sponsorship.
*   *Joshi et al. (2023)*: Social media influencer marketing.
*   *Leung et al (2022)*: Influencer marketing effectiveness.
*   *Pizzo et al. (2022)*: Esports scholarship review.
*   *Scholz (2020)*: Deciphering the world of esports.
*   *Su et al. (2025)*: Mainstreaming stardom & esports athlete branding.
*   *Thompson et al. (2022)*: Developing esport tourism.
*   *Reading File*: `Esports Ecosystems and Stakeholders_25_12_03_11_08_29.pdf`

---

### Project 3: Conflict, Morality, and Polarization
**Location:** `DATA&RESOURCES/PROJECT3`

#### Data Files
*   **Gender Eligibility (Khelif/Lin)** (Folder: `GENDER`)
    *   `GENDER_X.xlsx`: Twitter/X dataset (Largest volume).
    *   `GENDER_YT_COMMENT.xlsx` / `GENDER_YT_VIDEO.xlsx`: YouTube discourse.
    *   `GENDER_FACEBOOK.xlsx`: Facebook public comments.
    *   `GENDER_WEIBO.xlsx`: Chinese social media discourse (Comparative).
    *   `GENDER_BILI_COMMENT.xlsx`: Bilibili comments.
*   **B50 / Trump Political Discourse** (Folder: `B50`)
    *   `B50_YT_COMMENT.xlsx`: YouTube comments.
    *   `B50_INS_COMMENT.xlsx`: Instagram comments.
    *   `B50_X_COMMENT.xlsx`: X (Twitter) comments.

#### Reference Readings
*   *Dahlike et al. (2025)*: Contextualizing misinformation patterns.
*   *Hwang & Lee (2024)*: Nudge to Credible Information on Twitter.
*   *Ji et al. (2025)*: Fact-checking misinformation on Chinese Social Media.
*   *Larkin (2025)*: Identity Conflict Among Politically Engaged Sport Fans.
*   *Lu & Shen (2023)*: Multimodal Fact-Checking on Chinese TikTok.
*   *Street (2018)*: Forms of ‘Celebrity’ in Celebrity Politics.
*   *Su et al. (2025)*: Digital Nationalism (Trump Blaming China).
*   *Suk et al. (2025)*: Temporal dynamics of MeToo politicization.
*   *Wang & Zhang (2025)*: Political influencers & Trump’s rhetoric.
*   *Wang et al. (2024)*: Partisan politicization of non-political spaces.
*   *Woods et al. (2024)*: Popularity Gap & Social Status.

---

### A Note on File Formats
You will notice that most data files are in `.xlsx` (Excel) format rather than `.csv`. This allows for easier initial browsing of the data. When importing into your analysis tools (RStudio, Python, etc.), you may read them directly using libraries like `readxl` (R) or `pandas` (Python), or you may "Save As" to `.csv` if your script requires it.
