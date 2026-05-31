# User-Acquisition-Quarter-Analysis
User acquisition case study for a simulated paid ads performance - mobile app. 

# Q-end UA Performance Review and Next-Quarter Plan

<img width="1274" height="716" alt="image" src="https://github.com/user-attachments/assets/534a71f8-367b-490b-aceb-f00740a2967c" />


## Overview

The portfolio is profitable but poorly balanced. During this quarter, **$160K** was spent on paid acquisition, returned **$192K** in revenue at a **1.20 paid ROAS**, and generated **$32K of contribution margin**. However, **70% of the profit comes from two channels (Google and Unity), and 26% of the budget is currently burning without payback (TikTok and Facebook).**

Four moves are suggested, all executable inside two weeks:

- **Pause TikTok entirely** and reallocate the $25K/qtr to Google and Unity. TikTok is returning $0.23 for every $1 spent - this is the single biggest unforced error in the portfolio.

- **Scale Google and Unity by 15%** on a 3-day period, with marginal CPA monitoring. Combined headroom is roughly $20K gradual revenue per quarter at current LTV.

- **Rebuild Facebook creative** before any further spend. Pause the bottom 30% of ad sets, run a fresh creative batch, and only scale once ROAS clears 1.05.

- **Retire the 1M-install goal** and replace it with a contribution margin target, as current install goal is actively driving the wrong behaviour.

→ Aiming  **~$110K additional contribution margin** with only allocation, no cumulative budget. 

## Current performance

Headline numbers from the Power BI dashboard, using paid-only metrics (organic isolated):

| **Metric** | **This quarter** | **Read** |
| --- | --- | --- |
| Paid spend | $160,078 | On plan |
| Paid revenue | $192,299 | On plan |
| **Paid ROAS** | **1.20** | Profitable but masked |
| **Contribution margin** | **$32,221** | Concentrated in two channels |
| Paid CAC | $0.47 per install | Healthy vs LTV ceiling |
| Organic lift | 16.2% of installs ($20K rev) | Now reported separately |
| Paid installs | 338,292 | - |

## Channel portfolio

| **Channel** | **Spend** | **CAC** | **ROAS** | **Quadrant** | **Verdict** |
| --- | --- | --- | --- | --- | --- |
| **Google** | $42,698 | $0.36 | **2.01** | **SCALE** | Best channel in the portfolio. Scale aggressively but monitor marginal CPA |
| **Unity** | $37,558 | $0.31 | **1.49** | **SCALE** | Second profitable channel. Cheapest CAC in the portfolio. Same scaling treatment as Google. |
| **Ironsource** | $11,070 | $0.48 | 0.99 | **MONITOR** | Sits on breakeven. Maintain as a diversification hedge. |
| **AppLovin** | $17,395 | $0.40 | 0.97 | **OPTIMIZE** | Just below breakeven. Hold spend flat, push three new creative concepts. If ROAS doesn't clear 1.05 in 14 days, demote to Monitor. |
| **Mintegral** | $9,014 | $0.39 | 0.81 | **MONITOR** | Cheap CAC, poor revenue. Indicates low-LTV cohorts - investigate quality before scaling. |
| **Facebook Ads** | $17,079 | $3.16 | **0.57** | **REWORK** | CAC is 7× the portfolio average. Creative fatigue or targeting mismatch. Pause bottom 30% of ad sets and rebuild from creative. |
| **TikTok Ads** | **$25,264** | **$8.47** | **0.23** | **KILL** | Losing $0.77 on every dollar spent. CAC is 18× Google's. Pause entirely. |

### Put TikTok Ads on hold

TikTok is 15.8% of overall paid budget and is returning **$0.23 for every dollar**. With this channel returning 23, The problem is no longer in the creative assets, rather a **structural mismatch** between the platform's user base and the product. Players acquired via TikTok do not monetise in the title at anything close to cost of acquisition.

→ Recommendation: **pause TikTok entirely for one quarter**. Revisit only if the product team ships meaningful changes to early-game monetisation, or need testing a new title with a different demographic fit. This recovers ~$19.5K of unrecouped spend immediately.

### 2. Salvage Meta Ads

Although looking bad at first with the ROAS being 0.57, CAC of $3.16 with relatively modest install volume is the signature of **creative fatigue** - the same audiences seeing the same creative for too long, click-through collapses, CPA inflates.

**Plan:** pause the bottom 30% of ad sets this week. Deploy three new creative concepts (and make sure the brief comes in the same week). Test at $3K total spend over 10 days. Scale only the variants that clear ROAS 1.05. If nothing clears, demote Facebook to the Mintegral monitor bucket and reallocate the budget.

## Geo strategy

| **Tier** | **Spend share** | **ROAS** | **Action** | **Why** |
| --- | --- | --- | --- | --- |
| **Tier 1 - Scale (US, UK, DE, JP, FR, CA, CH)** | 67.0% | 1.18 | **Grow** | Profitable AND scalable. Take 70% of incremental budget here. |
| **Tier 2 - Niche profit (AR, AT, IT, MX)** | 9.9% | **2.05** | **Cap** | Excellent ROAS but small TAM.|
| **Tier 3 - Rework (ZA, AU, CZ)** | 9.3% | 0.75 | **Pause** | Sub-breakeven. Localise creative before any further spend. |
| **Tier 4 - Test (ES, IN, PE, HK, KR, NZ)** | 13.8% | 1.01 | **Pilot** | Small fixed budgets. Promote to T1 only with sustained ROAS > 1.15. |

**Tier 1 detail:** the US alone is $36K of spend at 1.18 ROAS, and performing well. The UK, Germany, Japan all behave similarly. The marginal install in Tier 1 is still profitable. Allocate the Google/Unity scale-up budget first.

**Tier 3:** South Africa, Australia, and Czechia are spending $14.9K to return $11.1K, losing $3.7K a quarter on these regions. Pause paid spend, deploy localized creative if/when capacity allows to drive organic installs, and re-enter as a Tier 4 test.

## 4. The reallocation plan

Cumulative impact of the four moves, assuming current-quarter run-rate and no LTV degradation at the margin:

| **Move** | **Budget shift** | **Expected rev impact** | **Timing** |
| --- | --- | --- | --- |
| **Pause TikTok** | −$25,264 | **+$19,578 recovered loss** | This week |
| **Reallocate to Google +15%** | +$6,405 | +$11,841 revenue | Next 2 weeks |
| **Reallocate to Unity +15%** | +$5,634 | +$7,722 revenue | Next 2 weeks |
| **Hold remainder for Facebook test + T1 fill** | +$13,225 | Variable | 30–45 days |
| **Pause Tier 3 geos** | −$14,880 | +$3,745 recovered loss | This week |
| **Net quarterly impact** | **Budget-neutral** | **≈ +$27K contribution** | - |

Annualised, this is **~$110K of additional contribution margin** against zero additional budget. Contribution margin would move from $32K/qtr to roughly $59K/qtr - an **83% improvement** on the metric that actually matters.

