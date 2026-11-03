# RiajulTech affiliate brand research

**Research date:** 2026-11-03 · **Source snapshot:** OpenAffiliate commit [`b13bab678b0f31112077c346c7d990f98a38ed7c`](https://github.com/Affitor/open-affiliate/tree/b13bab678b0f31112077c346c7d990f98a38ed7c) · **Audience:** English-speaking, mainly US/UK/EU · **Status:** internal shortlist, not final terms

## Executive summary

Start with the five automatically approved programs in Tier 1 **if their relevant product categories are actually covered**. They are leads, not endorsements or a promise of acceptance. The highest-scoring program overall is not necessarily the first to apply to: tiers express practical sequencing and content fit, not a second score ranking. The premium targets may be approached earlier if the site already has suitable content; 6–12 months is an editorial planning horizon, **not a stated traffic requirement**.

**All numbers and descriptions below are historical repository entries, not current confirmed terms.** No official program page was independently checked during this research. Manually confirm eligibility, publisher and buyer country coverage, rates, cookie rules, payout and restrictions on the brand page and in the applicable network agreement before applying or publishing links. Where the YAML does not list a field, it is marked “Not listed — verify manually”; this is not evidence of no restriction. Listed verification dates are repository metadata, not a new verification. In particular, Grammarly's quoted rates were sourced in its YAML from an Impact brand listing, not directly from the brand page.

## Source and selection

The checkout contains **1,382** individual `programs/*.yaml` files; 655 have `verified: true` at this snapshot. Records include `name`, `category`, `commission` (type and rate), and `agents.prompt`; optional data can include commission conditions and duration, `signup_url`, verification metadata, `cookie_days`, `payout`, `approval`, `restrictions` and `network`. A discovery `source` is not necessarily the payment network; `url` is generally a product homepage, while `signup_url` is the listed program link. `not_published`, comments and `conflicts` help distinguish unknowns and conflicting claims. The schema and [README](README.md#verification) distinguish crawl checks from maintainer verification. A `verified: true` flag is not proof that terms are still current. The recommendation context in each selected `agents.prompt` was reviewed.

We selected 17 tech-relevant, non-scam-flagged candidates with `verified: true` and brand-hosted program links in the snapshot, excluding unverified or unrelated entries. This is a judgmental shortlist, not proof that all 1,382 records were exhaustively screened for scams. No consumer-electronics or course brand is included merely to fill a category: this selection prioritizes records with sufficiently relevant, brand-hosted affiliate pages and usable terms; physical-product opportunities remain an open research gap. A product should be reviewed on its merits, not promoted solely for its payout.

## Scoring and ranking

Each dimension is scored 1–5; **score /100 = 5 × commission + 3 × cookie + 5 × approval + 3 × recurrence + 4 × trust/conversion**. This implements high weights of 25%, 25% and 20%, and medium weights of 15% each. Scores are independent editorial estimates, not OpenAffiliate's OAS and not measured conversion rates.

- **Commission potential (C):** subjective 1 = weak/unknown, 3 = moderate, 5 = strong potential based on base payouts and qualifying conditions, not headline maximum alone. Unknown negotiated rates are conservatively scored 2.
- **Cookie (K):** 1 = none; 2 = under 30 days or missing; 3 = 30–59; 4 = 60–89; 5 = 90+ days. Missing windows are penalized, not assumed to be short.
- **Approval (A):** 5 = listed automatic; 3 = listed manual; 2 = unspecified or explicit established-audience requirement; 1 = documented hard barrier. Automatic is not a guarantee and the score does not infer undisclosed thresholds.
- **Recurrence (R):** 1 = one-time; 3 = signup/first-payment hybrid; 4 = capped recurring; 5 = lifetime recurring or lifetime recurring plus a one-time bonus. Topaz is 4 for monthly plans only; Pictory is 5 based on the YAML description and lifetime field.
- **Trust/conversion (T):** subjective 1–5 proxy for brand familiarity and match to a tech buying-intent audience; no independent brand-trust study or conversion data was used. Stronger familiarity and broad fit score higher; no claim of actual conversion performance.

Equal totals are ordered alphabetically. The tier is a workflow decision: Tier 1 requires listed automatic approval; Tier 2 builds category coverage; Tier 3 focuses on premium offerings or a more developed editorial/audience fit. Unknowns are not evidence of difficulty. This is why tier order and overall rank may differ.

### Summary table — overall ranking

| Rank | Brand | Tier | Score /100 | C | K | A | R | T | Editorial use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | ElevenLabs | 1 | 83 | 4 | 2 | 5 | 4 | 5 | AI voice, audio and text-to-speech comparisons |
| 2 | Kinsta | 3 | 83 | 5 | 4 | 3 | 5 | 4 | Premium WordPress hosting comparisons |
| 3 | Fliki | 1 | 81 | 4 | 3 | 5 | 5 | 3 | Text-to-video and voiceover tool reviews |
| 4 | Writesonic | 1 | 81 | 4 | 3 | 5 | 5 | 3 | AI writing and chatbot comparisons |
| 5 | Pictory AI | 1 | 76 | 3 | 3 | 5 | 5 | 3 | Script-to-video and creator tool comparisons |
| 6 | WP Engine | 3 | 74 | 5 | 5 | 3 | 1 | 4 | Managed WordPress and WooCommerce hosting |
| 7 | Synthesia | 3 | 70 | 3 | 4 | 3 | 4 | 4 | AI avatar and enterprise training video comparisons |
| 8 | Grammarly | 2 | 68 | 3 | 5 | 3 | 1 | 5 | AI writing assistant reviews |
| 9 | Hostinger | 2 | 67 | 4 | 3 | 3 | 1 | 5 | Hosting and AI site-builder comparisons |
| 10 | 1Password | 2 | 65 | 3 | 2 | 3 | 3 | 5 | Password manager and security comparisons |
| 11 | AwardSpace | 1 | 62 | 4 | 2 | 5 | 1 | 2 | Free and budget hosting reviews |
| 12 | Shopify | 3 | 62 | 4 | 3 | 2 | 1 | 5 | Online store builder and commerce platform comparisons |
| 13 | Surfshark | 2 | 62 | 4 | 3 | 2 | 1 | 5 | VPN and security-suite comparisons |
| 14 | Topaz Labs | 2 | 62 | 3 | 3 | 2 | 4 | 4 | AI photo and video enhancement reviews; apply only with relevant editorial coverage |
| 15 | SiteGround | 2 | 61 | 4 | 4 | 2 | 1 | 4 | WordPress and WooCommerce hosting reviews |
| 16 | DreamHost | 2 | 58 | 4 | 3 | 2 | 1 | 4 | Hosting and managed WordPress comparisons |
| 17 | ExpressVPN | 3 | 54 | 2 | 2 | 3 | 1 | 5 | Premium VPN comparisons |

## Tiered recommendations and provisional program terms

All approval rows explicitly flag missing traffic and geography terms. “Manual” means a review is listed, not that a site must meet an invented traffic threshold. Links under each brand open the exact YAML record; the program URL is the `signup_url` in that record.

### Tier 1 — apply first (5)

Listed automatic approval and a plausible payout; check terms and product suitability before submitting. Five Tier 1 verification notes below specify what to check.

| Rank / score | Brand / YAML | Category | Commission / structure | Cookie | Payout / minimum | Approval / traffic / geography | Network | Official program URL | Verification note |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 / 83 | [ElevenLabs](programs/eleven-labs-inc.yaml) | AI audio | 22% recurring for 12 months on Starter, Creator, Pro and Scale; 11% on Business; enterprise excluded | Not listed — verify manually | End of third month after earning; $5 minimum; methods: Not listed — verify manually | Automatic; active ElevenLabs account required; paid placement restrictions; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | PartnerStack | https://elevenlabs.io/affiliates | https://elevenlabs.io/affiliates — confirm Plan-specific 22%/11% rates and 12-month period, cookie window, automatic approval/account eligibility, third-month payout and methods |
| 3 / 81 | [Fliki](programs/fliki.yaml) | AI video and voice | 30% recurring while the customer remains subscribed | 30 days | Monthly; $50 minimum; Wise or PayPal | Automatic; later re-evaluation possible; no paid ads or coupon sites; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Rewardful | https://fliki.ai/affiliate-program | https://fliki.ai/affiliate-program — confirm 30% recurring duration, 30-day cookie, automatic approval and re-evaluation; paid-ad restrictions and payout |
| 4 / 81 | [Writesonic](programs/writesonic.yaml) | AI writing | 30% recurring for the customer lifetime | 30 days | Monthly; $50 minimum; bank or PayPal | Automatic; instant; no spam or misleading promotion; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | In-house | https://writesonic.com/affiliate | https://writesonic.com/affiliate — confirm 30% lifetime, 30-day cookie, automatic/instant approval; payout and eligibility |
| 5 / 76 | [Pictory AI](programs/pictory.yaml) | AI video | 20% base recurring, up to 50% at 500+ referred customers; lifetime | 30 days | Monthly; $50 minimum; bank or PayPal | Automatic; instant; no spam or unsolicited promotion; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | In-house | https://pictory.ai/partnernow | https://pictory.ai/partnernow — confirm 20% base, 50% tier threshold and lifetime duration, 30-day cookie, automatic/instant approval and payout |
| 11 / 62 | [AwardSpace](programs/awardspace.yaml) | Web hosting | One-time $60 per paid sale at 1–2 monthly sales; $110 at 3+; $0.10 per active free signup. Paid plans must be annual or longer shared/VPS; discounted or promo-code orders excluded | Not listed — verify manually | Net-60 described with conflicting payment dates; $100 minimum, but terms say over $100; PayPal, Moneybookers, bank or check; $30 bank/check fee | Automatic; no self-referrals, incentives without approval or branded PPC; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | In-house | https://www.awardspace.com/web-hosting/affiliates/ | https://www.awardspace.com/web-hosting/affiliates/ — confirm Paid-sale tiers, free-signup payment and eligibility, missing cookie, automatic approval; reconcile payout dates and threshold against terms |

**Specific cautions:** ElevenLabs lists a plan-rate conflict (22% general language versus 11% Business in terms) and a payment lag; cookie and payment methods were marked unpublished. AwardSpace describes conflicting net-60 payment dates and “reaches $100” versus “over $100”; verify both documents. The older April 2026 Writesonic and Pictory entries deserve extra scrutiny.

### Tier 2 — after some traffic (7)

Useful for broadening coverage after relevant reviews and readership exist. Some approvals are unknown, not necessarily stricter.

| Rank / score | Brand / YAML | Category | Commission / structure | Cookie | Payout / minimum | Approval / traffic / geography | Network | Official program URL |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 8 / 68 | [Grammarly](programs/grammarly.yaml) | AI writing | One-time $20 per paid upgrade plus $0.20 per account signup; separate creator offer $25 per upgrade. Rates cited in YAML from Impact, not the brand page | 90 days | Frequency, minimum and methods: Not listed — verify manually | Manual, about 2 business days; no unapproved coupon sites or branded keyword bidding; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Impact | https://www.grammarly.com/affiliates |
| 9 / 67 | [Hostinger](programs/hostinger.yaml) | Hosting / AI website builder | One-time: up to 40% on hosting; up to 60% on Horizons plans | 30 days | Monthly; $100 minimum; bank or PayPal | Manual, 1–5 business days; no coupon sites without approval or branded PPC; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | In-house | https://www.hostinger.com/affiliates |
| 10 / 65 | [1Password](programs/1password.yaml) | Password manager | Hybrid: $2 per completed signup plus 25% of first month or year payment, $2 minimum | Not listed — verify manually | Frequency, minimum and methods: Not listed — verify manually | Manual; review time: Not listed — verify manually; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | CJ Affiliate | https://1password.com/affiliate |
| 13 / 62 | [Surfshark](programs/surfshark.yaml) | VPN / security | 40% of new sales, one-time; custom CPA possible | 30 days | On request; $100 minimum; methods: Not listed — verify manually | Approval: Not listed — verify manually; commission clears after 30-day money-back period; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Tunes (HasOffers); Impact, CJ, Awin also mentioned in YAML description | https://surfshark.com/affiliate-signup |
| 14 / 62 | [Topaz Labs](programs/topaz-labs.yaml) | AI photo and video editing | 20% of sale; monthly plans recurring up to 12 months, annual plans first payment only | 30 days | Net-30; $50 minimum; PayPal | Conflicting account-access versus approval language; working photography/design-related website required; no paid ads; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | In-house | https://topazlabs.com/affiliates/ |
| 15 / 61 | [SiteGround](programs/siteground.yaml) | Web hosting | One-time hosting tiers: $50 at 1–5 monthly sales, $75 at 6–10, up to $100 at 11–20; 21+ custom. Other listed services: 60% of first-year revenue | 60 days | Weekly; $0 minimum; methods: Not listed — verify manually | Approval and restrictions: Not listed — verify manually; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | In-house | https://www.siteground.com/affiliates |
| 16 / 58 | [DreamHost](programs/dreamhost.yaml) | Web hosting | One-time $15–$1,000 depending on plan and term; $1,000 is for DreamPress 20 on a three-year term | 30 days | Monthly per agent note; $0 minimum; bank; 97-day holding period | Approval: Not listed — verify manually; no branded search bidding; deal sites require approval; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Not listed — verify manually | https://www.dreamhost.com/affiliates/ |

**Specific cautions:** Surfshark’s structured `network` is null; its description names Tunes and additional networks, so confirm which actually accepts RiajulTech. Topaz lists conflicting immediate account access versus approval language and requires a photography/design-related website. Grammarly’s rates are attributed to Impact in the record; confirm with the brand and applicable offer.

### Tier 3 — premium / later-stage targets (5)

A 6–12 month planning target for premium, more specialized or audience-dependent offers. These are not proven competitive approval thresholds.

| Rank / score | Brand / YAML | Category | Commission / structure | Cookie | Payout / minimum | Approval / traffic / geography | Network | Official program URL |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2 / 83 | [Kinsta](programs/kinsta.yaml) | Premium managed hosting | One-time $50–$500 by plan plus 10% lifetime recurring; bonus qualifies after 2 months | 60 days | Monthly; $50 minimum; PayPal | Manual, within 3 business days; Kinsta customers auto-approved; disclosure required; some site types require further information; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | In-house | https://kinsta.com/affiliates/ |
| 6 / 74 | [WP Engine](programs/wp-engine.yaml) | Premium managed hosting | One-time $100 Lite; other plans $200 or first month payment, whichever is higher; no upgrades or add-ons | 180 days | Around the 20th of month after referral reaches 62 days in good standing; minimum and methods: Not listed — verify manually | Manual; affiliate links only on owned domains; social traffic through owned landing page; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Not listed — verify manually | https://wpengine.com/affiliate-program/ |
| 7 / 70 | [Synthesia](programs/synthesia.yaml) | AI video | 25% recurring on net Starter and Creator plan payments for 12 months | 60 days | Monthly first five business days; commission must exceed $30; methods: Not listed — verify manually | Manual; approved marketing materials only; no branded paid keywords or incentives; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Rewardful | https://www.synthesia.io/partners/affiliates |
| 12 / 62 | [Shopify](programs/shopify.yaml) | E-commerce software | One-time up to $150 per qualified new merchant; amount varies by referral location; full-price Basic, Grow or Advanced only | 30 days | Monthly; $10 minimum; bank or PayPal | Manual; active website or established audience required; not every application approved; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Impact | https://www.shopify.com/affiliates |
| 17 / 54 | [ExpressVPN](programs/expressvpn.yaml) | VPN / security | One-time CPA per irrevocable new sale; rate set in individual insertion order and not published | Not listed — verify manually | Monthly net-30; FAQ says $50 minimum but agreement says balance must exceed $50; PayPal, wire only above $1,000/month | Manual, 1–2 business days; no coupon sites, resellers or branded PPC; traffic threshold: Not listed — verify manually; publisher/buyer geography: Not listed — verify manually | Impact | https://www.expressvpn.com/affiliates |

**Specific cautions:** Kinsta lists an automatic-approval exception for its customers; its placement is a product-fit decision, not an assertion of strict eligibility. ExpressVPN’s actual CPA is private and its $50 payout wording differs between FAQ and agreement. Shopify’s commission varies with the buyer’s location; publisher eligibility is not specified in the record.

## Next actions

- [ ] Publish a handful of original, independently tested reviews/comparisons in each category before applying; match each program to actual reader intent. Do not add AI creator tools to unrelated gadget pages just to monetize them.
- [ ] Open each Tier 1 program URL and its terms; record the date and confirm the exact commission, qualifying plans and duration, cookie and attribution, approval rules, publisher/buyer geography, payment method, timing and minimum. Resolve the conflicts above in writing with the program where needed.
- [ ] Confirm RiajulTech's own publisher-country eligibility and ability to receive funds, separately from US/UK/EU buyer eligibility. Unknown does not mean available worldwide.
- [ ] Check the accepted channel, brand-bidding, coupon, advertising and disclosure rules; add clear affiliate disclosures near links and in relevant audio/video where required. Comply with applicable FTC, UK and EU rules.
- [ ] Apply to the Tier 1 programs that pass checks; log applications, approvals and actual offered terms. Then pursue Tier 2 and Tier 3 when content and audience fit justify it.
- [ ] Research reputable electronics/accessory and tech-learning programs separately, using official program pages; do not infer their terms or availability from this shortlist.
- [ ] Recheck terms periodically and whenever a network offer, product plan or program agreement changes. Keep editorial rankings independent of commission.

The accompanying `affiliate_shortlist.csv` has the same 17 programs, detailed terms, component scores, source slugs and verification notes for filtering. The `verified` column contains the YAML's `last_verified_at` date, not a fresh check.
