# msshreyaa-CRM-Lead-Nurture---SkillBridge
Simulated CRM lead nurture campaign — 3-segment, 18-email lifecycle sequence for an EdTech webinar-to-enrollment funnel, with trigger logic and projected performance metrics. 

# CRM-Based Lead Nurture Campaign — SkillBridge Academy (Simulated Case Study)

A simulated marketing automation project: a 3-segment, 18-email lead nurture sequence designed to convert free-webinar attendees into paid course enrollments for a fictional EdTech company, "SkillBridge Academy."

## Problem

SkillBridge Academy runs free webinars to generate leads for its self-serve course checkout, but has no structured follow-up after the webinar. Leads who don't convert immediately are never re-engaged, resulting in a low baseline lead-to-enrollment rate.

## Approach

Instead of one generic follow-up email, I designed a behavior-based nurture system that segments leads by intent and responds accordingly:

- **Segment A — Attended, didn't buy** (warm, moderate urgency)
- **Segment B — Abandoned checkout** (hot, highest urgency, shortest window)
- **Segment C — No-show / cold** (low intent, longer re-engagement play)

Each segment has its own trigger logic, timing, and messaging tone — mirroring how real marketing automation platforms (HubSpot, Marketo, Salesforce Marketing Cloud) structure lifecycle campaigns.

## Execution

### 1. Customer journey mapping
Mapped the full funnel from webinar signup → attendance → checkout → enrollment, identifying 3 natural drop-off branches.

### 2. Audience segmentation
Defined each segment by observed behavior (not demographics), since behavior is the strongest predictor of conversion likelihood in a self-serve funnel.

### 3. Trigger logic
| Segment | Emails | Trigger window | Priority |
|---|---|---|---|
| A — Attended, no buy | 6 | Day 1–7 | Medium |
| B — Abandoned checkout | 6 | Hour 1–Day 5 | Highest |
| C — No-show / cold | 6 | Day 0–14 | Lowest |

### 4. Email copywriting
Wrote all 18 emails (subject line + body + CTA), varying tone by segment — consultative for Segment A, friction-removal and urgency for Segment B, low-pressure value-add for Segment C.

### 5. Flow diagram
Visualized the full funnel and segment branching logic (see `/assets/flow-diagram.png`).

### 6. Projected performance modeling
Estimated open rate, click rate, and conversion rate per segment using published EdTech and e-commerce lifecycle-email benchmarks (Mailchimp, Klaviyo industry reports), not arbitrary numbers.

## Projected impact

| Segment | Open rate | Click rate | Sequence conversion |
|---|---|---|---|
| A — Attended, no buy | 45–55% | 12–18% | 8–12% |
| B — Abandoned checkout | 55–65% | 20–28% | 15–20% |
| C — No-show / cold | 20–30% | 4–8% | 2–4% (direct) |

**Blended projected lift: ~10–12% lead-to-enrollment conversion**, versus an estimated 2–4% baseline for leads with no structured follow-up.

*Note: this is a simulated project. All metrics are projections based on published industry benchmarks, not live campaign results.*

## Files in this repo

- `emails/segment-a-attended-no-buy.md` — full 6-email sequence
- `emails/segment-b-abandoned-checkout.md` — full 6-email sequence
- `emails/segment-c-no-show-cold.md` — full 6-email sequence
- `assets/flow-diagram.png` — visual funnel and trigger-logic diagram
- `case-study.pdf` — one-page summary version

## Why this project

This project applies CRM and lifecycle-marketing thinking directly from my experience managing learner engagement and Salesforce workflows in a Learner Success role — extended here into a full marketing automation case study.
