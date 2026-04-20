# RQ2 Analysis: Moral Outrage & Engagement
**Group:** TheMcGradys  
**Course:** KIN 7518 Social Issues in Sport  
**Date:** April 19, 2026  
**Dataset:** B50 — Trump/Political Polarization Discourse  
**Addresses:** RQ2 — *Do comments expressing moral outrage receive higher engagement (likes) than neutral comments across platforms?*

---

## Answer: No — Outrage Comments Receive Significantly *Fewer* Likes

Contrary to the hypothesis, moral outrage comments receive **significantly fewer likes** than neutral comments across platforms. The difference is statistically significant overall and on YouTube and X (Twitter).

---

## Results

| Platform | Outrage n | Outrage Mean Likes | Neutral n | Neutral Mean Likes | t-stat | p-value | Cohen's d |
|---|---|---|---|---|---|---|---|
| YouTube | 831 | 6.18 | 44,792 | 14.19 | -3.340 | 0.0008 *** | -0.031 |
| X (Twitter) | 19 | 2.05 | 989 | 33.26 | -4.538 | <0.001 *** | -0.206 |
| Instagram | 128 | 4.74 | 11,705 | 10.84 | -1.688 | 0.093 (ns) | -0.042 |
| **Overall** | **978** | **5.91** | **57,486** | **13.84** | **-3.897** | **<0.001 ***| **-0.033** |

`*** p<0.001  ** p<0.01  * p<0.05  ns = not significant`

---

## Key Findings

1. **Overall: Outrage comments receive ~57% fewer likes than neutral comments** (mean 5.91 vs. 13.84), a highly significant difference (p<0.001).

2. **YouTube**: Outrage comments average 6.18 likes vs. 14.19 for neutral — significantly lower (p=0.0008). Effect size is small (d=-0.031).

3. **X (Twitter)**: The largest gap — outrage averages 2.05 likes vs. 33.26 for neutral (p<0.001, d=-0.206). The effect size on X is small-to-medium, the strongest of any platform.

4. **Instagram**: The difference is in the same direction (4.74 vs. 10.84) but does **not** reach statistical significance (p=0.093). Instagram may reward outrage less selectively than other platforms.

5. **Effect sizes are uniformly small** (d = -0.031 to -0.206), meaning the effect is statistically real but modest in practical magnitude.

---

## Interpretation

These findings challenge the common assumption that moral outrage drives social media engagement. Several explanations are possible:

- **Platform norms**: Likes may signal agreement or approval rather than emotional resonance — neutral, informative, or humorous comments may attract more agreement than angry ones
- **Audience fatigue**: In a highly politicized dataset (Trump discourse), users may scroll past outrage content rather than engaging with it
- **Algorithmic suppression**: Some platforms may deprioritize flagged or emotionally negative content in feeds, reducing visibility and likes
- **Selection effect**: Outrage comments may attract replies and shares rather than likes — metrics not captured here

---

## Statistical Notes

- **Test used:** Welch's independent samples t-test (unequal variance assumed due to large sample size disparity between groups)
- **Effect size:** Cohen's d (negative = outrage group has lower mean)
- **Outrage classification:** Keyword-based regex matching (disgust, corrupt, liar, rage, shame, pathetic, deplorable, etc.)
- **Median likes = 0** for most groups, indicating heavily right-skewed distributions; mean comparisons reflect extreme values

---

## Limitations

1. **Like counts only** — does not capture replies, shares, or retweets, which may tell a different story
2. **Small outrage sample on X** (n=19) — results should be interpreted cautiously
3. **Keyword classification** may miss outrage expressed without explicit outrage words (e.g., sarcasm, coded language)
4. **Causal claims not possible** — we cannot determine whether outrage *causes* lower likes or whether other factors confound the relationship

---

## Visualization

See `visualizations/rq2_outrage_engagement.png` for a bar chart of mean likes by comment type and platform.
