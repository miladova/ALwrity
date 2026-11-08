# Destined Digital — Instagram Feed & Reels Teardown

**Subject:** `@destined.digital` — the posts themselves (feed posts, carousels, Reels, captions, hashtags, CTAs, cadence, engagement)
**Prepared:** 8 November 2026 (MYT)
**Revision 2 — 8 November 2026:** adds §13, a deep dive on **posting frequency, content variety, aesthetic & colour scheme**, and corrects several format labels in §1/§2 using decoded Instagram CDN media tags.
**Revision 3 — 8 November 2026:** separates **content type** (the format: single image / carousel / Reel) from **topic variety** (the subject: founder, proof, BTS, offer, education) as two independent axes, adds a type × topic cross-tab, and sets a separate target for each.
**Revision 4 — 8 November 2026:** on the user's request to discuss type first, widens the observed corpus from 12 to **18 posts** using the Imginn Reels tab, adds a dedicated **§14 content type deep dive**, and corrects several earlier cadence, format and offer claims (list in §14.6).
**Revision 5 — 8 November 2026:** rebuilds **topic variety** on the full 18-post corpus in **§15** — full topic inventory, type × topic cross-tab, buyer-journey coverage, an operational topic target, and a second correction list (§15.7).
**Revision 6 — 8 November 2026:** at the client's request ("posts, specifically statics"), adds **§16 — twenty golden static / carousel post ideas**, a build-once reuse-many spec, and an explicit list of what is excluded by confidentiality.
**Revision 7 — 8 November 2026:** records the client's own five-slot **proposal skeleton** in **§17**, separates placement from content series, reads the four listed items against the corpus, and proposes a fifth.
**Companion to:** [`Destined-Digital-Instagram-Research.md`](Destined-Digital-Instagram-Research.md) (whole-account audit) and [`Destined-Digital-Instagram-Profile-Top-Analysis.md`](Destined-Digital-Instagram-Profile-Top-Analysis.md) (header, Highlights, Stories; **§7.11–§7.13** are the final three-pinned-post answer (About / Services / Proof for now); **§8.10–§8.14** have seventy sourced, clearance-free Story ideas (low-effort re-cut in §8.12) plus twenty chill interactive prompts (§8.14)) 
**Theory basis:** MKW1120 Lectures 1–10, especially L9 (IMC, communication process, AIDA / 5As, appeals), L7 (services, brand, positioning), L6 (STP), L5 (buyer decision process), L4 (MIS), L2 (relationship marketing)

---

## 0. Scope and evidence quality

This is a **post-level pass**: what is actually published, when, in what format, with what copy and what response. It does not repeat the header, Highlights or Stories analysis.

Instagram's own profile is login-walled. Data comes from two independent mirrors ([Imginn](https://imginn.com/destined.digital/), [Pixnoy](https://www.pixnoy.com/profile/destined.digital/)), their [Reels tab](https://imginn.com/reels/destined.digital/) and individual post pages, which expose exact dates, like/comment counts, co-creators and comments.

| Evidence | Status |
|---|---|
| Captions, hashtags, dates, like/comment counts | Observed, medium confidence (mirror-derived, not official analytics) |
| Format (static / carousel / Reel, clip duration) | Observed from post pages and CDN media types, medium confidence |
| Media class decoded from CDN `efg` tags (`FEED` / `CAROUSEL_ITEM` / `CLIPS`) | Observed in Revision 2, medium-high confidence (§13.2) |
| Automated descriptions of four post thumbnails | Low confidence — machine-generated text, not pixel inspection (§13.3) |
| Exact visual treatment, palette, typography, custom covers | **Not directly inspected** — low-confidence inferences only; no published palette or brand-guideline hex codes were located |
| Reach, impressions, saves, shares, profile visits, DMs, conversions | **Unknown** |
| Posts after 29 Sep 2026 | **Not visible on either mirror**, but the website and Threads show Oct/Nov activity — the mirrors are incomplete, not authoritative |

**Standing caveat:** all engagement figures below are a **mirror sample**, not official analytics. Relative patterns are useful; absolute performance claims are not. See also the client-confidentiality constraint in §8.9 of the profile-top teardown — nothing here uses client-confidential material, and any client result, quote or shoot asset needs written clearance before it appears in a post. **Revision 2** adds §13 below with a second evidence pass; its sources are listed separately in §13.6. **Terminology convention (Revision 3):** *content type* always means the format/container; *topic* always means the subject matter. They are reported separately — see §1 and §13.2. **Revision 4** widens the evidence base to 18 posts and makes §14 the authoritative type analysis; §14.6 lists the claims it supersedes. **Revision 5** makes §15 the authoritative topic analysis; §13.2.2/§13.2.3 remain labelled 12-post sub-samples. **Revision 6** adds a proposal bank of static ideas (§16); it is a menu, not an observed change to the grid. **Revision 7** records the client's own proposal skeleton (§17); it is a thinking aid, not a recommendation to publish.

---

## 1. Post inventory (mirror sample, chronological)

**Two independent descriptive columns — do not read them as one axis:**

| Axis | Question it answers | Values used in this audit |
|---|---|---|
| **Content type** (format) | *How* is the post packaged? | Single image (`FEED`) · Carousel (`CAROUSEL_ITEM`) · Reel (`CLIPS`) · Stories / Highlights are a separate surface (companion §8) |
| **Topic** (content pillar) | *What* is the post about? | Founder / people · Brand manifesto · BTS / process · Social proof · Offer / service · Education |

A Reel can carry any topic, and any topic can be carried by any type. §2 and §13.2.1 cover the type axis; §3 and §13.2.2 cover the topic axis; §13.2.3 crosses the two.

| # | Date (mirror) | Post | **Type** (format) | **Topic** (pillar) | Likes / comments |
|---|---|---|---|---|---|
| 1 | 3 May 2026 | "being a gen z boss is controversial…" | Carousel † | Founder / culture | **55 / 7** |
| 2 | 19–20 May 2026 | "A little peek into our heart behind our work" | Carousel, 3 frames | Brand identity | 8 / 0 |
| 3 | 30 May 2026 | "In a crowded market…" (manifesto, free-consult CTA) | Single image † | Manifesto | 18 / 2 |
| 4 | 2 Jul 2026 | "A snippet of the last bits of June" (monthly dump) | Reel (photo dump) † | BTS / culture | 7 / 0 |
| 5 | 5 Jul 2026 | "Sometimes even the smallest tweaks…" | Reel, 17 s | Process teaser | 10 / 4 |
| 6 | 21 Jul 2026 | Sunway University AUSMAT guest lecture | Carousel † | Authority / founder | **81 / 5** |
| 7 | 31 Jul 2026 | "Having Christ as my business partner…" | Reel | Founder story / faith | **61 / 9** |
| 8 | 31 Jul 2026 | Podcast clip: why packages start at RM1,500 (co-created with `@zhechambers.my`) | Reel, 81 s | Offer / PR / collaboration | 39 / 1 |
| 9 | 7 Aug 2026 | Client testimonial: "not just about likes and views" | Single image † | Social proof | 8 / 0 |
| 10 | 10 Aug 2026 | "Behind every 'effortless' product shot…" | Reel, 11 s | Process / BTS | 19 / 0 |
| 11 | 17 Aug 2026 | "If businesses from multiple industries trust us…" (request packages) | Single image † | Social proof / offer | 20 / 1 |
| 12 | 29 Sep 2026 | "Meta's performance data… 56% to 70%" (save this post) | Reel † | Abstract education | 8 / 0 |

**† Format labels revised in Revision 2.** The `o=` parameter on each Pixnoy thumbnail decodes to the original signed Instagram CDN URL; its `efg` tag names the media class — `FEED.best_image_urlgen.C3` (single image), `CAROUSEL_ITEM.best_image_urlgen.C3` (carousel frame), `CLIPS.best_image_urlgen.C3` (Reel). Earlier labels in this table were inferred from mirror post pages; the decoded tags supersede them. The 12 dated posts classify as **3 single images, 3 carousels, 6 Reels**. A `CLIPS` asset can be a video compiled from stills (the 2 Jul "photo dump" is the likely case), so verify in-app. One further date caveat: the CDN `Published Time` for the "industries" asset is **16 Aug 2026 13:06 GMT** (≈21:06 MYT) while the mirror labels the post 17 Aug — mirror dates mix UTC and MYT and may shift by ±1 day.

**Scope note (Revisions 4–5).** The 18-post corpus is the basis for the authoritative type analysis (§14) and topic analysis (§15); the 12-post grid tables in §1–§3 and §13.2 are labelled sub-samples. **Revision 4 note.** The Reels tab's six further clips (39/0, 19/3, 6/1, 21/0, 37/4, 59/0) are **not duplicates** — they are six older, individually dated Reels (10 Mar – 6 Jun 2026) missing from the truncated grid. The combined observed corpus is therefore **18 posts**, tabulated in §14.2. A "View more" control on Pixnoy confirms the grid mirror is truncated, so 18 is still a lower bound.

**Sample statistics (12-post grid sub-sample):** 334 likes, 29 comments; **mean ≈ 28 likes, median ≈ 19**, mean ≈ 2.4 comments. Nominal (likes + comments) / 396 followers ≈ **7.6% per post**. Comments are 0–2 on 9 of 12 posts. *§14.2 gives the 18-post figures; the two denominators are not interchangeable.*

---

## 2. Content type (format) and cadence

> **Axis note.** This section is about the **container** — single image, carousel, Reel — and says nothing about subject matter. Topic variety is a different axis (§3, §13.2.2).

**Content type mix (12-post grid sub-sample; revised in Revision 2, superseded by §14).** Decoded CDN tags give **3 single images, 3 carousels and 6 Reels** here; across the full 18-post corpus Reels are **12 of 18 (67%)** and durations run **9–81 s** (§14.2). Two of the strongest posts are Reels (founder faith, 61/9; podcast, 39/1), and the single best post (Sunway lecture, 81/5) is a **carousel**, not a static image — see §13.2 for the format-by-format breakdown. There is no consistent series, no recurring template and no recognisable cover system: every thumbnail carries a `best_image_urlgen` tag, i.e. an auto-generated frame rather than an uploaded custom cover (low-confidence inference).

**Cadence (corrected in Revision 4 — see §14.6).** The 12-post grid sample gives gaps of 17, 10, 33, 3, 16, 10, 0, 7, 3, 7, 43 days, but the Reels tab adds six earlier posts (10 Mar, 20/24/26 May, 5/6 Jun) which **remove the apparent 33-day void**: June had at least two posts, and the 30 May → 2 Jul stretch becomes 6 / 1 / 26 days.

- **Combined 18-post corpus:** 18 posts over 203 days (10 Mar → 29 Sep 2026) = **0.62 posts/week, ≈2.7 posts/month**, median gap **6 days**.
- Two long silences remain: **54 days** (10 Mar → 3 May, i.e. all of April) and **43 days** (17 Aug → 29 Sep).
- Burst-and-silence is therefore *more* pronounced, not less: inside a burst the account posts every 1–7 days, then disappears for six weeks.
- The mirrors stop at 29 Sep 2026 while the website and Threads show October/November activity (an October shoot dump, a skincare shoot, `@sivarajan x @fupi.co`), so the true current cadence remains unknown. Do not claim an exact posting rate.

The account's own published advice — "posting more is not the same as selling better" — is reasonable, but 54- and 43-day silences are not a strategy; they are absence. The fix is a maximum gap and a content buffer, not a higher volume target (§13.1).

---

## 3. Topic variety — pillars and what actually performs

> **Axis note.** This section is about **subject matter**, independent of format. Content type is §2 / §13.2.1; the two are crossed in §13.2.3.


| Topic (pillar) | Posts in sample | Likes (mean) | Reading |
|---|---|---|---|
| **Founder / person / values** | 5 | **49** (55, 8, 81, 61, 39) | By far the strongest. The three posts above 50 likes are all person-centred |
| Manifesto / brand identity | 2 | 13 (18, 8) | Mid-to-low |
| Social proof | 2 | 14 (8, 20) | Low, despite a `/testimonials` page full of real growth screenshots |
| BTS / process / craft | 3 | 12 (7, 10, 19) | Low |
| Abstract education | 1 | 8 | Lowest |

*The pillar tags above overlap — a post can count as both founder-centred and an authority signal — so the rows total 13 tags across 12 posts. §13.2.2 gives a strict one-topic-per-post partition with a different denominator; the conclusion is the same, but the two tables are not interchangeable.*

**The precise finding (corrected in Revision 5 — see §15.3):** in the 12-post sub-sample every post above 50 likes was person-centred. Across all 18 posts that is **no longer true** — four posts exceed 50 likes, three founder posts and one **education** Reel (10 Mar 2026, B2B messaging, 59/0). Person-centred content is still the strongest lever, not a guarantee, and it is the only topic that reliably generates comments.

**What is missing from the 12-post grid sample (corrections in §14.6 and §15.7; full 18-post topic audit in §15):**

- **No post with a quantified client result.** The 7 Aug testimonial says "great marketing isn't just about likes and views… meaningful results for our clients" and then shows no result. The `/testimonials` page carries real growth screenshots; none are repurposed onto Instagram.
- **No post that explains a service in detail** (what is included, deliverables, timelines, who it is for) *in the recent grid* — the 6 Jun Reel lists three deliverables but no timeline or buyer fit.
- **No standalone offer post in the recent grid** — but **Revision 4 correction:** a **6 Jun 2026 Reel** (9 s, 39/0) is an explicit launch-package post ("starts at RM1,500/month", three deliverables listed, DM CTA), and a 24 May Reel offers the free consult. The offer has been published; it is simply not pinned, not resurfaced and not visible in the truncated grid (§14.2, §14.6).
- **No post with a specific, measurable CTA** — no DM keyword, no link, no "book the 30-min consult here".

The single most telling artefact is a **real comment** on the 5 Jul "smallest tweaks" Reel (10 likes / 4 comments):

> "Okay great marketing. Now show me the product where can I get it"

A follower is literally asking for the offer — despite a launch-package Reel having been published five weeks earlier. The problem is therefore **not absence of the offer but absence of a permanent surface for it** (companion §7.10). §15.5 reads this as a decision-stage buyer arriving at an awareness-stage grid. Buyer-alignment in one sentence (Lecture 9, feedback; Lecture 1, needs alignment / marketing myopia).

---

## 4. Caption anatomy

**Voice.** Distinctive and consistent in tone: lowercase openings, intimate first person, soft emojis (🫶🏼, 🧸, 🦢, 💭, 🌷, 🚀, 😯, 👀), "gen z boss" framing, warmth over corporate polish. This is the account's clearest asset — and it matches the locked bio line "marketing doesn't have to be boring or repetitive".

**Structural weaknesses:**

1. **Hooks are buried.** The Sunway lecture caption runs ~150 words of narrative before any point of value, and has no CTA at all. Instagram truncates captions after roughly 125 characters, so the first line decides whether the rest is read.
2. **CTAs are generic.** "Send us a DM to book your free consultation today!", "request our packages", "Get in touch for your free consultation now", "Send us a message!", "Save this post" — five different vague invitations, no mechanism, no keyword, no link, no offer specificity. None is measurable.
3. **Register is inconsistent across posts.** Some captions are fully lowercase ("being a gen z boss… i wouldn't have it any other way"), others are careful sentence case. Per the header decision, lowercase captions are a legitimate voice choice — but mixing the two rules *within the same feed* reads as unpolished.
4. **Hashtag hygiene.** Real errors in the copy include `#CreativeAgecy` (misspelt), `#marketinginkl` (missing separator), and `#socialmediaa`. Sets range from 5 to 8 tags, alternating between buyer-facing (`#MarketingForSMEs`, `#BusinessOwnerMY`, `#DigitalMarketingMY`) and peer-facing (`#genzboss`, `#advertisingagency`, `#agency`) — i.e. no consistent target. One 2026 secondary source reports a 5-hashtag cap; several posts here exceed that, but this is **not** confirmed from a Meta primary source, so verify in-app before treating it as a violation. (Some apparent truncations such as `#digitalmarketingagen cy` are mirror rendering artefacts, not typos — do not "correct" those.)
5. **Handle consistency.** The founder is tagged as `@_joannafrancis` in captions; confirm this is the single canonical personal handle before cross-linking.
6. **One unsupported statistic.** The 29 Sep post asserts "Meta's performance data confirms that creative strategy accounts for 56% to 70% of total campaign performance". No primary Meta source was located; secondary blogs support only a narrower 56% sales-lift figure and a separate 70% framing. This is a credibility risk on a post whose whole argument is about rigour.

**One thing done well:** the 31 Jul podcast Reel is a **co-created post** with `@zhechambers.my` (81 s, 39/1), which places the same asset into a second follower graph — the clearest reach tactic in the sample (Lecture 9, message source; Lecture 7 slide 24).

---

## 5. Aesthetic and voice (low confidence)

No images were directly inspected; the following is inferred from captions, automated CDN image descriptions and the website.

- Founder selfies and candid people imagery; genuine on-set BTS; warm/evening-lit lifestyle still-lifes; editorial product shoots; monthly photo dumps.
- Text-led graphics and testimonial tiles; square and 4:5 crops dominate.
- Soft/cute emoji system and lowercase, confessional copy — "human, not robotic" is executed in the caption voice more convincingly than in the visual system.
- Website uses italic serif romantic copy ("Your Marketing Match made in Heaven") with stock lifestyle photography — a **different** visual register from the Instagram captions. Lecture 9 slide 22 (IMC: clear, consistent, compelling) flags this as tone adaptation drifting into a different promise.

Do not claim an exact palette, typography, custom Reel covers or grid layout without a logged-in visual review. §13.3 expands this with four automated asset descriptions, a cross-channel register comparison and a proposed (clearly illustrative) colour system.

---

## 6. What the posts get right

1. **A genuinely differentiated voice.** In a category full of "we drive results" agencies, "marketing doesn't have to be boring" is memorable and ownable (Lecture 7 slide 29: brand as perception, cognitive shortcut; L7 slide 32: beliefs-and-values positioning).
2. **People outperform everything else by roughly 3×.** Corrected in Revision 5: across the 18-post corpus the founder topic averages **65.7 likes** versus **21.2** for all other topics combined (~3.1×), and generates **57% of all comments**. The earlier "~4× / ~49 vs ~12" figures came from the overlapping-tag 12-post sample (§15.3, §15.7). This is still the clearest A/B signal available.
3. **Local cues are present** (`#klagency`, `#marketingagencykl`, `#DigitalMarketingMY`, `#MarketingForSMEs`, Sunway, Malaysian collaborators) — useful for a Malaysian SME target, even if inconsistently applied.
4. **Production capability is visible** — product-shot BTS, shoot dumps, set styling — which makes an intangible service partly tangible (Lecture 7 slide 23).
5. **Authority signals** — Sunway AUSMAT guest lecture, a podcast interview, a founder story — build credibility beyond the grid.
6. **Emotional and moral appeals** are used confidently (Lecture 9 slide 15); the faith post (61/9) is the sample's second-highest engagement.
7. **At least one collaboration post** extends reach into another audience.

---

## 7. What the posts get wrong, ranked

| # | Problem | Evidence |
|---|---|---|
| 1 | **Proof is absent from the grid** despite real growth screenshots on `/testimonials` | No quantified result in **18** posts; the single proof post (7 Aug, 8/0) shows no number (§15.3) |
| 2 | **Buyer misalignment** — 56% of posts sit at awareness, with no decision-stage furniture | "Okay great marketing. Now show me the product where can I get it"; §15.5 |
| 3 | **Cadence** — burst-and-silence, 54- and 43-day gaps with a 6-day median inside bursts, no fixed slot system | §2, §13.1, §14.2 |
| 4 | **No offer architecture** — the one explicit offer is a 9 s June Reel with no pin, Highlight or link; no service explainer with timeline/buyer fit | §3, §14.6 |
| 5 | **Generic, unmeasurable CTAs** — five variants of "DM us", no keyword or link | §4 |
| 6 | **Caption hygiene** — buried hooks, mixed register, real hashtag typos, no consistent target | §4 |
| 7 | **Unsupported "Meta 56–70%" claim** on the most data-oriented post | No primary Meta source located |
| 8 | **No repeatable series or custom covers** — every post is a one-off, so nothing compounds; type and topic are never planned independently | §2, §13.2.1, §13.2.3 |
| 9 | **Faith content carries decoding risk** in multi-faith Malaysia — authentic and high-engagement, but the audience it attracts may not be the buyer | Lecture 9 slides 6–7 (encoding / noise) — a judgement call, not a rule |
| 10 | **Confidentiality discipline is unproven** — shoot/client content appears without a visible clearance protocol | See §8.9 of the profile-top teardown |

---

## 8. Diagnosis through MKW1120

| Lecture | Lens | Finding |
|---|---|---|
| L9 s6–7 | Communication process / noise | The 56–70% stat and generic CTAs introduce noise; the "show me the product" comment is decoded feedback that the promise never landed |
| L9 s8, s20 | Feedback | Real comments exist but are not used as a feedback loop; no post responds to the buyer's actual question |
| L9 s10, s15 | 5As / AIDA / appeals | Posts cluster at awareness and emotional appeal; almost nothing at desire/action or rational appeal — quantified in §15.5 |
| L9 s22 | IMC — clear, consistent, compelling | Four voices across IG, Threads, website and LinkedIn; even within IG, five different CTAs |
| L7 s23–24 | Intangibility / inseparability | BTS and founder content are the right physical evidence, but proof and offer are missing |
| L7 s29, s32 | Brand as perception / positioning levels | Strong beliefs-and-values positioning; weak attribute and benefit positioning |
| L6 s10, s34, s38–43 | Segmentation / positioning / value propositions | Accessible "same for less" position exists (RM1,500) but is buried in a podcast caption |
| L5 s30–35 | High-involvement buyer decision | A B2B buyer researching the agency finds brand mood but no deliverables, pricing page, process or case study |
| L4 s10–12 | Marketing information system | No evidence of internal data being used to evaluate post performance; "WHERE DREAMS MEET DATA" is not demonstrated on the grid |
| L1 s6 | Needs alignment / marketing myopia | Content optimised for self-expression rather than the buyer's information need |

---

## 9. Recommendations

**P0 — cheap, do this week**

1. Fix `#CreativeAgecy`, `#marketinginkl`, `#socialmediaa`; pick one hashtag set per post (buyer-facing or peer-facing, not both).
2. Put the **hook in the first 125 characters** and the CTA in the last line. One CTA per post, with a measurable mechanism: `DM "AUDIT"` or a link to the free consult.
3. Replace or qualify the "Meta 56–70%" claim; if no primary source can be produced, remove the number.
4. Confirm the canonical founder handle and use it consistently.

**P1 — next 30–60 days**

5. **Build three repeatable series** rather than one-off posts:
   - *Founder-led Reel*: one buyer problem → one fix → one CTA, 20–40 s. This is their best-performing format (55–81 likes).
   - *Proof carousel*: three cleared/anonymised or fully owned case studies with one number each — subject to the confidentiality tiers in §8.9 of the profile-top teardown (own-account tests, spec work and aggregate counts are clearance-free substitutes).
   - *Offer explainer*: one service per post, what is included, who it is for, entry price (only if RM1,500 is still current), and the free 30-min consult.
6. **Set two separate targets — one per axis (§13.2.4).** Do not collapse them into a single "content mix" number.
   - **Type target (the container):** of **2–3 feed posts per week**, roughly 2 Reels + 1 carousel; a single image at most once a fortnight and never the week's only post; plus the Stories rhythm in §8.2–8.8 of the profile-top teardown.
   - **Topic target (the subject):** roughly 40% buyer-problem education / 30% proof / 20% BTS-culture / 10% offers, applied **across** all types. In practice this means proof must also appear as a carousel and a Reel, not always as a single image. Reuse their own TikTok scripts for the education topic. **§15.6 makes this operational** on the 18-post corpus, with the hard-offer/soft-CTA distinction and confidentiality-safe proof substitutes.
7. **Design a consistent Reel cover template** (dark wordmark system, one short title, matching the avatar) so the grid reads as a series — the palette roles, 60/30/10 rules and cover-template spec are in §13.4.
8. **Systematise collaborations**: one co-created Reel per month with a complementary Malaysian business, as the `@zhechambers.my` post did.
9. **Answer the comment.** Publish "what we sell, what it costs, how to buy" — but first **resurface the 6 Jun launch-package Reel** (pin it, add it to a Highlight, link it from the bio); the content already exists (§14.6).
10. Keep casting/hiring off the client-facing grid; use a separate labelled surface.

**P2 — measurement discipline**

11. Assign each post one 5As/AIDA objective before publishing; log reach, saves, shares, profile visits, DMs, consults booked and wins.
12. Monthly feedback ritual: which pillar produced DMs, not just likes; drop the bottom format, double the top one. Quarterly competitor benchmark.
13. Do not treat mirror like counts as official analytics — pull Instagram Insights in a logged-in session.

---

## 10. Confidentiality guardrail

The marketing is done **for clients**, so client information must remain confidential. Any proof post, quote, shoot still or client tag needs written clearance and anonymisation, or must use fully owned substitutes (own-account experiments, spec work for a fictional brand, aggregate capability counts, sector-level rounded outcomes). No client name, logo, handle, packaging, raw dashboard or unreleased campaign should appear in a public post. See §8.9 of the profile-top teardown for the three-tier clearance system.

---

## 11. Verify in a logged-in session before finalising

- Full post history after 29 Sep 2026, and the **true** current cadence.
- Which three posts are **pinned** (the first three mirror items are older than the fourth, consistent with pins but unconfirmed).
- Whether custom Reel covers exist; exact visual system, palette, typography and grid layout.
- Official Insights: reach, impressions, saves, shares, profile visits, link taps, DMs, consultations.
- Whether any post has been deleted, archived or is a paid/dark post not shown in mirrors.
- Whether the 5-hashtag cap reported by a secondary 2026 source is enforced on this account.
- Client clearances for any results or shoot imagery currently published.
- **Revision 3 items:** confirm the type × topic cross-tab against the full grid; a `CLIPS` asset made from stills may be a photo dump rather than a Reel, which changes the type count.
- **Revision 2 items:** a full 3-column grid screenshot; the real brand palette/hex codes from the logo file or brand guide; whether any custom Reel covers exist; contrast checks on white-on-image type; a 32–40 px thumbnail legibility test; and the CDN-vs-mirror date offset (§13.3, §13.5).

---

## 12. Sources (Revision 1 — additional sources in §13.6, §14.7, §15.8, §16.6 and §17.6)

**Post surfaces**
- [Imginn posts](https://imginn.com/destined.digital/) (chunks 0–1) · [Imginn Reels](https://imginn.com/reels/destined.digital/) · [Pixnoy posts](https://www.pixnoy.com/profile/destined.digital/) (chunks 0–2)
- Dated post pages: [DYjRFxgmuxN](https://imginn.com/p/DYjRFxgmuxN/) (20 May 2026, 8/0) · [Dbb-pYOyjkg](https://imginn.com/p/Dbb-pYOyjkg/) (31 Jul 2026, 39/1, co-created with `@zhechambers.my`) · [Db29rxlj_o_](https://imginn.com/p/Db29rxlj_o_/) (10 Aug 2026, 19/0, 11 s Reel) · [DaaVx-yh_JT](https://imginn.com/p/DaaVx-yh_JT/) (5 Jul 2026, 10/4, 17 s Reel, includes the "show me the product" comment) · [DY8upBvSYYs](https://imginn.com/p/DY8upBvSYYs/) · [Dd24JguMT4u](https://imginn.com/p/Dd24JguMT4u/) · [DX4J3S0EpZG](https://imginn.com/p/DX4J3S0EpZG/) · [DcJM9P5l_yx](https://imginn.com/p/DcJM9P5l_yx/) · [Dbu_0ZEibcY](https://imginn.com/p/Dbu_0ZEibcY/) · [DbdnTqNKVfy](https://imginn.com/p/DbdnTqNKVfy/) · [DbCtry4Erk3](https://imginn.com/p/DbCtry4Erk3/) · [DaRd--hOQVY](https://imginn.com/p/DaRd--hOQVY/)

**Owned website**
- [sitemap.xml](https://www.destined-digital.com/sitemap.xml) · [testimonials](https://www.destined-digital.com/testimonials) · [services](https://www.destined-digital.com/services) · [whydestined](https://www.destined-digital.com/whydestined) · [home](https://www.destined-digital.com/)

**Platform mechanics (secondary sources, verify in-app)**
- Caption truncation ~125 characters and a reported 5-hashtag cap: [Fuxux](https://www.fuxux.com/blog/instagram-character-limit) · [Postlen](https://postlen.app/en/blog/instagram-character-limits)
- Meta 56–70% claim: secondary blogs only ([LA Factory](https://lafactory.com/creative-is-the-new-targeting/), [Hunchads](https://hunchads.com/blog/advantage-plus-get-creative-get-results), [Flighted](https://flighted.co/blog/7-meta-ads-creative-strategies-that-work)); **no primary Meta source located**

**Course material:** MKW1120 Lectures 1–10, from the lecture PDFs originally uploaded as gitignored working files under `workspace/uploads/MKW1120/`. Slide references were verified in the earlier extraction pass; the PDFs themselves are not part of the repository.

---

## 13. Deep dive (Revision 2) — posting frequency, content variety, aesthetic & colour scheme

Added 8 November 2026 at the user's request. §2, §3 and §5 touched these four dimensions only briefly; this section gives each a proper pass.

**New evidence layer.** Pixnoy embeds each post thumbnail as a proxy URL whose `o=` parameter is base64 for the original signed Instagram CDN URL. Decoding it exposes an `efg` tag naming the media class: `FEED.best_image_urlgen.C3` (single image), `CAROUSEL_ITEM.best_image_urlgen.C3` (carousel frame) or `CLIPS.best_image_urlgen.C3` (Reel). Four of those signed assets were also readable through an automated image reader, which returned machine-generated descriptions and CDN `Published Time` values. These descriptions are **weak corroboration, not pixel inspection** — they cannot establish a colour palette. Signed URLs expire, so they are not reproducible verbatim. No official brand palette, style guide or hex codes were located on the owned website or in its Squarespace JSON.

### 13.1 Posting frequency

**What the mirror actually shows (corrected in Revision 4).** The 12-post grid sample suggested 0.56 posts/week and a zero-post June. Adding the six older Reels exposed by the Reels tab gives **18 posts over 203 days (10 Mar → 29 Sep 2026) = 0.62 posts/week, ≈2.7 posts/month**.

| Month | Posts in combined observed corpus |
|---|---|
| March 2026 | 1 |
| April 2026 | **0** |
| May 2026 | 6 |
| June 2026 | **2** |
| July 2026 | 5 |
| August 2026 | 3 |
| September 2026 | 1 |

Seventeen inter-post gaps, median **6 days**, mean ≈11.9: 54, 16, 1, 4, 2, 4, 6, 1, 26, 3, 16, 10, 0, 7, 3, 7, 43 days.

Two findings sharpen the diagnosis:

1. **April has zero posts; June has two** (5 and 6 Jun), and a "snippet of the last bits of June" was published on 2 July. Client work and shoots clearly continued; publishing stopped and restarted. This is a scheduling/operations failure, not a lack of material.
2. **Median gap is 6 days while the two longest are 54 and 43 days.** Inside a burst the account sustains near-daily-to-weekly output. The failure is two discontinuities, not a uniformly slow rate. The problem is *continuity*, not *volume*.

*Earlier versions of this section said June 2026 had no posts and that a 33-day gap ran 30 May → 2 Jul. Both were artefacts of the truncated grid; see §14.6.*

**Date caveat.** CDN timestamps are GMT while the report uses MYT: the "industries" asset is stamped 16 Aug 2026 13:06 GMT (≈21:06 MYT) but the mirror labels the post 17 Aug. Treat all mirror dates as ±1 day. The mirrors also stop at 29 Sep 2026 while the website and Threads show Oct/Nov activity, so **the true current cadence is unknown** — this is a lower bound on a stale sample, not a live measurement.

**What 2026 guidance suggests (secondary commercial blogs, not Meta rules).**

| Source | Suggested cadence |
|---|---|
| [Kontentino](https://www.kontentino.com/blog/how-often-to-post-on-instagram/) | 3–5 feed posts/week; 4–7 Reels/week; 2–5 Stories/day; "2–3 feed posts/week is plenty" if Reels also run |
| [Hijack Social](https://www.hijacksocial.com/blog/how-often-to-post-on-instagram) | 3–5 Reels/week; 2–3 carousels/week; **"the maximum cadence you can maintain at consistent quality for 90 days"**; 3×/week for 60 days for sub-1K accounts |
| [Spiral Reach](https://www.spiralreach.com/digital-marketing-blogs/how-often-should-you-post-instagram-data-backed-guide/) | 3–5 Reels/week; 2–4 feed posts/week; daily Stories |
| [Shadowphone](https://www.shadowphone.io/blog/instagram-posting-schedule-2026) | 3–5 feed posts/week; 2–4 Reels/week; batch one day/week; keep 2–3 weeks scheduled |
| [Conbersa](https://www.conbersa.ai/learn/what-is-instagram-best-practices) | 3–5 Reels + 2–3 carousels/statics/week; cites 2× reach for ≥3 posts/week |

They disagree by a factor of two on Reels (2–4 vs 4–7/week) and on feed posts (2–3 vs 3–5/week). None is a platform rule; none is validated against this account's Insights. Their three consistent points are worth taking: **consistency beats intensity**, **choose a cadence sustainable for 90 days**, and **hold a 1–2 week content buffer built by batching**.

**Recommendation — a floor, not a quota.** §9 already proposes 2–3 feed posts/week. Do not raise that number until it has been held for 90 days. Instead add three controls:

| Control | Target | Rationale |
|---|---|---|
| Maximum silence | **No gap >14 days** on the feed | Directly targets the two observed 54- and 43-day gaps without inflating volume |
| Rolling buffer | **1 week of posts ready at all times**, batched in one production day | Removes the "no material" excuse; the 2 July June-dump proves material existed while publishing lagged |
| Story floor | 2–3 Story days/week (companion §8.2–8.9), clearance-free tiers only | Keeps the account present between feed posts without adding feed posts |

Measure **posts per rolling 4-week window** and **reach per post**. If reach per post falls as frequency rises, the constraint is hook quality (§4), not cadence. Do not set a cadence from a blog's average; set it from this account's own Insights after 4 weeks.

### 13.2 Content variety — two independent axes

The word "variety" hides two different questions. Keeping them apart changes the diagnosis.

| Axis | Question | Values in this audit | Reported in |
|---|---|---|---|
| **A. Content type** (format / container) | *How* is the post packaged? | Single image (`FEED`), carousel (`CAROUSEL_ITEM`), Reel (`CLIPS`); Stories/Highlights are a separate surface (companion §8) | §2, §13.2.1 |
| **B. Topic** (content pillar / subject) | *What* is the post about? | Founder/people, brand manifesto, BTS/process, social proof, offer/service, education | §3, §13.2.2 |

They are **orthogonal**: a Reel can carry any of the six topics, and any topic can be packaged as any of the three types. A target such as "2 Reels + 1 carousel a week" is a **type** target; "40% educational" is a **topic** target. Several 2026 secondary frameworks silently mix the two — e.g. "40% Reels, 30% carousels, 20% Stories, 10% feed posts" ([Flowshorts](https://flowshorts.app/blog/instagram-marketing-strategy)) is a type mix, while "40% educate / 30% engage / 20% promote / 10% entertain" ([Scale Growth](https://scalegrowth.digital/resources/social/instagram-content-ideas/)) is a topic/objective mix. Quoting both as "the ideal content mix" without naming the axis is how a plan ends up with three Reels all about the same thing.

#### 13.2.1 Axis A — content type

> **Scope warning (Revision 4):** the tables below use the **12-post grid sub-sample only**. §14.2 is the authoritative 18-post type distribution — 12 Reels (**67%**), 3 carousels, 3 single images.

Decoded CDN `efg` tags classify all 12 dated posts:

| Date | Post | `efg` class | Type | Likes / comments |
|---|---|---|---|---|
| 3 May | Gen Z boss | `CAROUSEL_ITEM` | Carousel | 55 / 7 |
| 19–20 May | Heart behind our work | `CAROUSEL_ITEM` | Carousel, 3 frames | 8 / 0 |
| 30 May | Crowded-market manifesto | `FEED` | Single image | 18 / 2 |
| 2 Jul | June photo dump | `CLIPS` | Reel | 7 / 0 |
| 5 Jul | Smallest tweaks | `CLIPS` | Reel, 17 s | 10 / 4 |
| 21 Jul | Sunway AUSMAT lecture | `CAROUSEL_ITEM` | Carousel | **81 / 5** |
| 31 Jul | Christ as business partner | `CLIPS` | Reel | **61 / 9** |
| 31 Jul | Podcast / RM1,500 | `CLIPS` | Reel, 81 s | 39 / 1 |
| 7 Aug | Client testimonial | `FEED` | Single image | 8 / 0 |
| 10 Aug | Product-shot BTS | `CLIPS` | Reel, 11 s | 19 / 0 |
| 17 Aug | Industries we've worked with | `FEED` | Single image | 20 / 1 |
| 29 Sep | Meta 56–70% "save this post" | `CLIPS` | Reel | 8 / 0 |

| Type | n | Share | Mean likes | Range |
|---|---|---|---|---|
| Single image | 3 | 25% | **15.3** | 8–20 |
| Carousel | 3 | 25% | **48.0** | 8–81 |
| Reel | 6 | 50% | **24.0** | 7–61 |

*Small mirror sample; likes are not official analytics, and these are correlations, not causal effects. The carousel mean is lifted by one 81-like outlier; the 8-like "heart behind our work" carousel sits at the same floor as the weakest Reel.*

**Verdict on axis A: type variety is high, type systematisation is low.** All three feed types are in use and Reels make up half the 12-post sub-sample — **two-thirds of the full 18-post corpus** (§14.2) — so "add more formats" is the wrong advice. What is missing is a rule for which type carries which job, a repeatable series, and a cover template: every thumbnail is a `best_image_urlgen` auto-frame.

#### 13.2.2 Axis B — topic variety

> **Superseded for counts (Revision 5):** this is the 12-post grid sub-sample, retained as a worked example of the method. The authoritative 18-post topic distribution is **§15.3**; the corrected cross-tab is **§15.4**.

§3 used overlapping pillar tags (13 tags across 12 posts). Here each post gets **exactly one dominant topic** so the distribution is countable:

| Topic | Posts | Share | Mean likes | What the topic is doing |
|---|---|---|---|---|
| Founder / people / values | #1, #6, #7 | 25% | **65.7** (55, 81, 61) | The only reliably high-performing subject |
| Brand identity / manifesto | #2, #3 | 17% | 13.0 (8, 18) | States the vibe, not the offer |
| BTS / process / culture | #4, #5, #10 | 25% | 12.0 (7, 10, 19) | Makes an intangible service visible, but earns little response |
| Offer / service / price | #8, #11 | 17% | 29.5 (39, 20) | Only two posts; price appears in just one caption |
| Social proof / results | #9 | 8% | 8.0 | A testimonial with **no number in it** |
| Education / industry insight | #12 | 8% | 8.0 | One abstract stat post with an unverified claim |

*§3's "founder / person / values" row counted 5 posts at mean 49 because it also tagged the brand-identity carousel (#2, 8 likes) and the podcast Reel (#8, 39 likes). The strict partition here counts 3 at mean 65.7. Both readings say people-centred content leads; the denominators differ, so do not compare the two numbers directly.*

**Verdict on axis B: topic variety is skewed, not absent.** Six topics are present, but **founder + BTS = 6 of 12 posts**, while proof and education get one post each. There is no quantified client result, no service explainer, no standalone offer post, and no buyer-problem education. Topics cluster at awareness and emotional appeal, with almost nothing at desire/action (Lecture 9 slides 10, 15). This is the gap §3 and §7 already identified — but it is a **topic** gap, and changing the type mix will not close it.

#### 13.2.3 The cross-tab — where the two axes meet

> **Superseded for counts (Revision 5):** this cross-tab is a **12-post sub-sample**, retained as a worked example. The rebuilt 18-post cross-tab is **§15.4** — the central finding (carousels carry only founder + brand) survives unchanged.

| Topic ↓ / Type → | Single image | Carousel | Reel | n |
|---|---|---|---|---|
| Founder / people | — | #1 (55), #6 (81) | #7 (61) | 3 |
| Brand identity / manifesto | #3 (18) | #2 (8) | — | 2 |
| BTS / process / culture | — | — | #4 (7), #5 (10), #10 (19) | 3 |
| Social proof / results | #9 (8) | **—** | **—** | 1 |
| Offer / service / price | #11 (20) | **—** | #8 (39) | 2 |
| Education / industry insight | — | **—** | #12 (8) | 1 |
| **Total** | **3** | **3** | **6** | **12** |

**9 of 18 cells are empty.** Three findings only appear when the axes are crossed:

1. **Carousels — the type with the highest mean (48 likes) — carry only founder and brand topics.** Proof, offer, education and BTS have **never** been given the format best suited to explanation and saves.
2. **The two commercial topics (proof + offer) are 3 of 12 posts, and 2 of those 3 are single images**, the type with the lowest ceiling (8–20 likes). The commercial message is being carried by the least capable container.
3. **BTS is locked to one type** (all three BTS posts are Reels); the founder topic is the only one spread across two types. Topics have become welded to formats, which is why the grid feels repetitive even though it uses three types and six subjects.

This is the precise reason to separate the axes: **fixing type variety alone produces more Reels about the same founder/BTS subjects; fixing topic variety alone produces more proof posts that are still single images.** The mismatch lives in the cells, not in either marginal total.

#### 13.2.4 Two separate targets

| Axis | Observed (mirror) | Proposed target | Guardrail |
|---|---|---|---|
| **A — type** | 3 single / 3 carousel / **12 Reels** (17/17/**67%**) across 18 posts (§14.2) | 2 Reels + 1 carousel per week; single image ≤ fortnightly, never the week's only post | No gap >14 days, rolling 1-week buffer (§13.1) |
| **B — topic** | Founder 3, BTS **5**, brand 2, offer **5**, proof 1, education **2** across 18 posts (§15.3) | 40% buyer education / 30% proof / 20% BTS-culture / 10% **hard** offers (§9, §15.6) | Every recurring topic must appear in **≥2 types** within a 4-week cycle; no topic welded to one format |

Each calendar slot is then one **(type, topic) pair** — the distinction becomes operational rather than decorative:

| Slot | Type | Topic | Brief |
|---|---|---|---|
| Tue | Reel | Founder / buyer education | One buyer problem → one fix → one CTA, 20–40 s |
| Thu | Carousel | Proof **or** service explainer | 3 frames, one cleared/owned number or one deliverable list |
| Sat (optional) | Single image | Offer | `What we're booking` card; pinned only |
| Mon / Wed / Fri | Stories | Retention / culture | Companion §8.8–8.9, green tier only |

One series name, one cover template and one measurable CTA per slot; keep casting/hiring off the client-facing grid. **Caveat:** the generic 2026 mixes cited in §13.6 conflict with each other by a factor of two, and none is a Meta rule. Both targets above are hypotheses built from this sample's empty cells; review them at 4 weeks against saves, DMs and consults, not likes.

### 13.3 Aesthetic & colour scheme — what can and cannot be claimed

**Evidence actually available (all low confidence).**

| Artefact | Automated reading | What it legitimately supports |
|---|---|---|
| 3 May "Gen Z boss" (CDN 3 May 12:58 GMT) | "2 women staring into camera and on the top there is a text" | People-first portrait photography with a text overlay |
| 30 May manifesto (CDN 30 May 04:10 GMT) | A graph/diagram about growing a brand through social media management, branding, content creation and community engagement (machine output partly garbled) | At least one text/diagram-led graphic exists |
| 21 Jul Sunway lecture (CDN 21 Jul 04:59 GMT) | "A group of students listen to a woman giving them instructions and a phone on a small laptop" | Candid documentary event photography |
| 17 Aug industries (CDN 16 Aug 13:06 GMT) | "the words 'industries we've worked with' is written in white on the image" | White type placed over imagery — a contrast risk to test |
| Profile avatar (earlier auto-description) | Dark "DESTINED digital" wordmark | A dark wordmark is the one recurring brand device visible |
| Owned website | Italic serif romantic copy ("Your Marketing Match made in Heaven"), stock lifestyle photography; `Destined.png` social logo returned only "a pretty basic graphic" | A **different** visual register from the Instagram captions |
| Every thumbnail's `best_image_urlgen` tag | Auto-generated frames | No evidence of custom Reel covers (inference, not proof) |

Four signed CDN assets returned `403 URL signature mismatch`; the descriptions above are machine-generated text, sometimes mixed-language, and **cannot establish a palette, typography, exact colours, grid layout or cover design**.

**What this adds up to.** At least three visual registers coexist — candid people/documentary photos, text-led graphic tiles, and editorial product/BTS stills — with no visible unifying device beyond the dark wordmark. The **verbal identity is more consistent than the visual identity**: lowercase confessional captions, soft emojis (🫶🏼, 🧸, 🦢, 💭, 🌷) and the locked "marketing doesn't have to be boring" line are far more recognisable than any treatment on the grid. That is an IMC problem (Lecture 9 slide 22: clear, **consistent**, compelling), and it extends across channels:

| Surface | Register |
|---|---|
| Instagram bio / captions | Lowercase, warm, anti-boring, teddy-bear emoji |
| Threads bio | "Marketing agency based in MY 💌✨" — functional, location-led |
| Website | "WHERE DREAMS MEET DATA." / "Your Marketing Match made in Heaven." — romantic italic serif |
| LinkedIn | "Where strategy meets authenticity. No fluff. Just marketing that works." — corporate |

Four voices for one brand. Tone adaptation between platforms is legitimate; four different *promises* is drift.

**Colour-specific findings — deliberately narrow:**

1. **No official palette exists in any accessible source.** The Squarespace `?format=json-pretty` exposes the site title, timezone (`Asia/Kuala_Lumpur`), social accounts and a logo asset URL, but no colour/tweak values. Do **not** state hex codes as observed.
2. White-on-image type appears on at least one asset. Any text-over-photo template needs a documented contrast rule — WCAG **4.5:1 for normal text, 3:1 for large text** ([Postquick](https://www.postquick.ai/blog/how-to-design-an-instagram-grid-theme-in-2026-color-palette-strategy), [GetKoro](https://getkoro.app/blog/color-psychology-in-instagram-ad-design)) — plus a scrim or solid block behind the type.
3. Thumbnail legibility: companion §7.1 advises checking the wordmark at roughly **32–40 px** and keeping critical elements in the **inner ~80% / centre safe zone**. Fine italic serif from the website is a poor choice at that size.
4. A grid is judged as a **3-column preview first**; a vertical centre safe zone matters because Instagram crops feed previews ([Postquick](https://www.postquick.ai/blog/how-to-design-an-instagram-grid-theme-in-2026-color-palette-strategy)).

### 13.4 A proposed colour system — illustrative, NOT observed

The table below is a **placeholder framework to be replaced by the client's real brand guide values**. None of these hex codes was sampled from a Destined Digital asset.

| Role | Share | Placeholder hex | Use |
|---|---|---|---|
| Ink (near-black) | 30% | `#111827` | Wordmark, headings, body type |
| Warm off-white | 60% | `#FAF7F2` | Backgrounds, negative space |
| Mid neutral | — | `#D6CEC3` | Dividers, photo tint, card fills |
| Signature accent | 10% | `#C2410C` | **Only** the CTA, one key number, series label |
| Support grey | — | `#6B7280` | Secondary type, captions |

**Rules to adopt once real values exist:**

- **Five colours maximum**, structured as dominant / secondary / accent, with a near-black reserved for type legibility ([Graphic Design Eye](https://graphicdesigneye.com/instagram-color-palettes/)). Define *your* white and *your* black explicitly — one template using pure white and another creamy white is the most common cause of an accidentally mismatched grid ([Postquick](https://www.postquick.ai/blog/how-to-design-an-instagram-grid-theme-in-2026-color-palette-strategy)). Document HEX, RGB and CMYK so the same colour survives screen and print ([Walk Production](https://www.walkproduction.com/blog/brand-tone-of-voice/)).
- **60/30/10 per post and across the grid**: ~60% neutral background, ~30% brand colour, ~10% accent reserved for the single element that needs attention. Using the accent on three things stops it being an accent.
- **One consistent edit style** (temperature / contrast / saturation) and one neutral background tone is the fastest route to cohesion without redesigning every post ([Postquick](https://www.postquick.ai/blog/how-to-design-an-instagram-grid-theme-in-2026-color-palette-strategy), [ToolsInsta](https://toolsinsta.com/guides/instagram-grid-planning)).
- **3–5 Reel cover templates** (Light / Dark / Urgent): fixed wordmark corner, ≤5-word title, series label, one accent underline; vary the imagery, keep the structure ([Techlasi](https://techlasi.com/savvy/best-practices-for-instagram-reels-covers/)). This directly fixes the auto-generated-frame finding in §2/§5.
- **Carry the same system into Reels covers, Stories and Highlight covers**, not just the grid — otherwise the profile reads as three different accounts ([ToolsInsta](https://toolsinsta.com/guides/instagram-grid-planning)). Keep this consistent with the five Highlight labels in companion §7.9.
- **Test before rollout**: contrast checker, dark and light backgrounds, greyscale legibility, 3-column grid preview, and the 32–40 px thumbnail test. Avoid rigid rainbow/checkerboard grid gimmicks; they are high-maintenance and can date quickly.

### 13.5 Priority, and what these four areas cannot fix

| Area | Effort | Priority | First move |
|---|---|---|---|
| Posting frequency | Low (scheduling) | **P0** | No gap >14 days; rolling one-week buffer; batch one day/week |
| Content variety — **type and topic separately** | Medium (planning) | **P1** | Set a type target and a separate topic target; fill the empty type × topic cells |
| Aesthetic / covers | Medium-high (needs real brand assets) | **P1–P2** | One-page visual system + 3 cover templates |
| Colour scheme | High (needs the brand guide) | **P2** | Extract real hex values from the logo/guide, then apply 60/30/10 + contrast checks |

**None of the four fixes the offer gap.** A perfectly regular, beautifully colour-coded grid whose only explicit offer is a 9-second Reel from June will keep producing comments like *"Okay great marketing. Now show me the product where can I get it"*. Confusing a type target with a topic target is the fastest way to fix neither. Frequency and aesthetics are **multipliers on the message, not substitutes for it** (Lecture 9 slide 22, IMC; Lecture 1 slide 6, needs alignment). All proof imagery and any client-facing shoot stills remain subject to the three-tier confidentiality constraint in companion §8.9.

**Verify in a logged-in session before finalising this section:** full 3-column grid screenshot including Oct/Nov posts; the real brand palette/hex values from the logo file or brand guide; whether custom Reel covers exist; contrast on white-on-image type; 32–40 px thumbnail legibility; the CDN-vs-mirror date offset; and official Insights to replace every mirror like count.

### 13.6 Additional sources for §13

**Posting frequency** (secondary 2026 blogs; figures conflict — heuristics, not Meta rules): [Kontentino](https://www.kontentino.com/blog/how-often-to-post-on-instagram/) · [Hijack Social](https://www.hijacksocial.com/blog/how-often-to-post-on-instagram) · [Spiral Reach](https://www.spiralreach.com/digital-marketing-blogs/how-often-should-you-post-instagram-data-backed-guide/) · [Shadowphone](https://www.shadowphone.io/blog/instagram-posting-schedule-2026) · [Conbersa](https://www.conbersa.ai/learn/what-is-instagram-best-practices)

**Content mix / pillars** (secondary, mutually inconsistent): [Scale Growth Digital](https://scalegrowth.digital/resources/social/instagram-content-ideas/) · [Flowshorts](https://flowshorts.app/blog/instagram-marketing-strategy) · [Spunk.pics](https://spunk.pics/blog/instagram-content-strategy-guide-2026) · [Venture Media](https://www.venturemedia.io/post/instagram-marketing-strategy-2026-what-works-now) · [InfluenceFlow](https://influenceflow.io/resources/instagram-content-calendar-strategy-a-2026-guide-to-planning-scheduling-and-scaling/)

**Grid / colour / covers** (secondary design guidance): [Postquick — 60/30/10, contrast, safe zones](https://www.postquick.ai/blog/how-to-design-an-instagram-grid-theme-in-2026-color-palette-strategy) · [ToolsInsta — grid planning, filter consistency](https://toolsinsta.com/guides/instagram-grid-planning) · [Graphic Design Eye — ≤5 colours](https://graphicdesigneye.com/instagram-color-palettes/) · [Techlasi — Reel cover templates](https://techlasi.com/savvy/best-practices-for-instagram-reels-covers/) · [GetKoro — contrast and CTA hierarchy](https://getkoro.app/blog/color-psychology-in-instagram-ad-design) · [Walk Production — identity systems, HEX/RGB/CMYK](https://www.walkproduction.com/blog/brand-tone-of-voice/)

**Primary/owned evidence:** [Pixnoy posts](https://www.pixnoy.com/profile/destined.digital/) (chunks 0–2, `o=` parameters decoded to signed CDN URLs) · [Imginn posts](https://imginn.com/destined.digital/) and [Reels](https://imginn.com/reels/destined.digital/) · [Squarespace site JSON](https://www.destined-digital.com/?format=json-pretty) (timezone, social accounts, logo asset URL; **no colour values**) · automated reads of four signed Instagram CDN image URLs (machine-generated descriptions; URLs expire).

**Revision 4 additions (full list in §14.7):** [Imginn Reels tab](https://imginn.com/reels/destined.digital/) (chunks 0–1) · six newly dated post pages (`DZPEN_qyCfS`, `DZMnNg0ElBr`, `DYydxvCgce7`, `DYudFl6yj_g`, `DYjuLLSSK-9`, `DVsR8I6l-eg`) · [Metricool 2026 study](https://metricool.com/press-release-instagram-study-2026/) · [Wavevision / Buffer format comparison](https://www.wavevision.io/blog/instagram-carousel-posts-vs-reels-performance-comparison-2026-data) · [TryUnlockDM / Socialinsider](https://www.tryunlockdm.com/blog/instagram-reels-vs-carousels-2026) · [HopperHQ Reel specs](https://www.hopperhq.com/blog/instagram-reel-size/).

**Revision 5 additions (full list in §15.8):** B2B content-mix and buyer-journey sources — [BrandRoad](https://brandroad.in/blog/instagram-growth-b2b-brands-2026), [1into2](https://www.1into2.com/instagram-marketing-strategies-for-b2b-brands/), [Komet Media](https://www.kometmedia.com/blogs/instagram-growth-playbook-for-b2b-saas), [GrowWithSakib](https://growwithsakib.com/content-mapping-buyer-journey/), [Infuse](https://infuse.com/glossary/content-marketing/).

**Course material:** MKW1120 Lectures 1, 4, 5, 7 and 9 as referenced in §8 and §15.5.

---

## 14. Content type deep dive (Revision 4)

Added 8 November 2026 when the user asked to discuss **type first**. This is now the **authoritative type analysis**; §2, §13.2.1 and the 12-post tables in §13.2 are a labelled sub-sample. Topic variety is deliberately left for the next discussion — §14.5 flags only where the added posts change it.

### 14.1 Why the corpus grew from 12 to 18

The grid mirrors are truncated (a "View more" control on Pixnoy). The [Imginn Reels tab](https://imginn.com/reels/destined.digital/) lists **12 Reels** in reverse-chronological order; six of them — 10 Mar, 20 May, 24 May, 26 May, 5 Jun and 6 Jun 2026 — appear nowhere in the 12-post grid list. Their individual post pages give exact "Posted On" dates, captions, and `duration_s` values from the signed CDN download URLs. The observed corpus is therefore **18 posts spanning 10 Mar → 29 Sep 2026 (203 days)** — still a lower bound, not an exhaustive history.

Every one of the 12 Reels-tab thumbnails carries `CLIPS.best_image_urlgen.C3`, which independently confirms the `efg` decoding used in §1 and §13.2.

### 14.2 The 12 Reels, individually

| Date | Shortcode | Duration | Likes / comments | What it is | In 12-post grid? |
|---|---|---|---|---|---|
| 29 Sep 2026 | `Dd24JguMT4u` | — | 8 / 0 | "Meta 56–70%" creative-strategy claim, "save this post" | Yes |
| 10 Aug 2026 | `Db29rxlj_o_` | **11 s** | 19 / 0 | Behind an "effortless" product shot | Yes |
| 31 Jul 2026 | `DbdnTqNKVfy` | — | **61 / 9** | Founder faith / values | Yes |
| 31 Jul 2026 | `Dbb-pYOyjkg` | **81 s** | 39 / 1 | Podcast clip, why packages start at RM1,500 (co-created) | Yes |
| 5 Jul 2026 | `DaaVx-yh_JT` | **17 s** | 10 / 4 | "Smallest tweaks" — includes the "show me the product" comment | Yes |
| 2 Jul 2026 | `DaRd--hOQVY` | — | 7 / 0 | "Snippet of the last bits of June" photo dump | Yes |
| **6 Jun 2026** | `DZPEN_qyCfS` | **9 s** | 39 / 0 | **Launch-package Reel: "starts at RM1,500/month", account manager / designer / editor, DM CTA** | No |
| **5 Jun 2026** | `DZMnNg0ElBr` | **25 s** | 19 / 3 | "A day in the life of an Account Manager" | No |
| **26 May 2026** | `DYydxvCgce7` | **11 s** | 6 / 1 | Word-search "upgrade your socials" + "chat with our team" | No |
| **24 May 2026** | `DYudFl6yj_g` | **16 s** | 21 / 0 | "Your brand is our privilege", free-consult CTA | No |
| **20 May 2026** | `DYjuLLSSK-9` | **21 s** | 37 / 4 | Team introduction | No |
| **10 Mar 2026** | `DVsR8I6l-eg` | **19 s** | **59 / 0** | B2B messaging-clarity education, "send us a dm" | No |

*Durations come from the CDN `duration_s` field on nine post pages; three are unavailable. Dates are mirror-provided "Posted On" values and may be ±1 day across UTC/MYT.*

**Corrected type distribution (18 posts):**

| Type | Posts | Share of posts | Likes | Share of likes | Mean likes | Comments |
|---|---|---|---|---|---|---|
| Single image (`FEED`) | 3 | 17% | 46 | 8.9% | **15.3** | 3 |
| Carousel (`CAROUSEL_ITEM`) | 3 | 17% | 144 | 28.0% | **48.0** | 12 |
| Reel (`CLIPS`) | **12** | **67%** | 325 | 63.1% | **27.1** | 22 |
| **Total** | **18** | 100% | **515** | 100% | 28.6 | **37** |

Read the shares, not just the means: carousels generate **28% of likes and 32% of comments from 17% of posts**; single images generate **9% of likes from 17% of posts**. The carousel mean is still inflated by the 81-like Sunway outlier, so treat this as an efficiency signal, not a causal claim. Reels are **9–81 s**, with nine known durations clustered at **9–25 s**; the 81 s podcast clip is the sole outlier.

### 14.3 What each type is for — external 2026 evidence

| Type | Platform job | Evidence (secondary, not Meta primary) |
|---|---|---|
| **Reel** | Discovery / reach beyond followers | [Buffer analysis of 52M posts](https://www.wavevision.io/blog/instagram-carousel-posts-vs-reels-performance-comparison-2026-data): 30.81% reach rate, ≈2.25× single images and 1.36× carousels. [Metricool 2026 study of 24.3M posts](https://metricool.com/press-release-instagram-study-2026/): >4× the interactions of single-image posts; average watch time 8.5 s. Reel shares up ~67% YoY. |
| **Carousel** | Authority / saves / depth | Metricool: **9× more saves** than single-image posts. Buffer: 6.90% median engagement rate by reach vs 3.31% for Reels (≈109% more engagement per person reached). [Socialinsider 2026 benchmarks via TryUnlockDM](https://www.tryunlockdm.com/blog/instagram-reels-vs-carousels-2026): ~0.55% ER for carousels vs ~0.50–0.52% Reels vs ~0.33% static. Instagram can re-serve a carousel with a later slide as its cover. |
| **Single image** | One legible message / pinned card | Metricool: reach **−21.96%**, interactions **−25.41%**, engagement **−45.98%** YoY — the fastest-declining format. |
| **Stories** | Retention (separate surface) | Companion §8; out of scope for this feed/Reels teardown. |

**Caveat:** these are commercial studies and blog summaries that disagree with each other; none is a Meta rule, and this account has ~396 followers, well below the 1–5K bracket where Socialinsider still found Reels ahead (9.78% reach vs 8.80% carousels vs 7.00% images). Use them as directional reasoning, not benchmarks.

**Implication for Destined Digital:** the Reel-heavy mix is *directionally right* — they are already using the platform's discovery format as their default. The type-level problem is not "not enough formats"; it is that (a) the weakest, fastest-declining type carries the commercial posts, (b) the highest-value type (carousel) is never used for proof, offer or education, and (c) none of the 12 Reels has a designed cover.

### 14.4 The actual type-level problems

These can all be fixed **without changing a single topic** — which is why it was worth separating the axes.

1. **No custom Reel covers.** All 12 Reels-tab thumbnails are `CLIPS.best_image_urlgen.C3` (auto-generated frame). The same mirror renders `video_user_uploaded_thumbnail` / `video_user_selected_thumbnail` on unrelated accounts' posts, so the tag does distinguish an uploaded cover from a picked frame — medium confidence, verify in-app. Result: a grid of 12 unrelated frames with no series label, no title and no wordmark.
2. **Short, unstructured clips.** 9–25 s dominates, but there is no repeatable hook → value → CTA structure across clips; the 81 s podcast is a one-off.
3. **Single images carry the commercial load.** The three singles are the manifesto (18/2), the unquantified testimonial (8/0) and the "industries / request packages" post (20/1) — precisely the buyer-facing messages, in the format 2026 data says is declining fastest.
4. **Carousels are under-used and mis-assigned.** 3 of 18, all founder/brand (Gen Z boss, heart behind the work, Sunway). None for proof, offer, education or BTS, despite carousels being the save/authority format.
5. **No type-level series or cover template**, so nothing compounds: twelve Reels, twelve separate productions.
6. **Production specs are unverifiable** from mirrors — 1080×1920 / 9:16, H.264/AAC, captions-on for mute viewing, safe zones. These are recommendations, not observations.

### 14.5 A type architecture (proposal)

| Type | Job | Weekly slot | Structure / spec | Metric to watch |
|---|---|---|---|---|
| **Reel** | Discovery | 2/week | 1080×1920, 9:16, MP4/H.264 + AAC, 30 fps; 9–30 s; hook in first 1–2 s; captions on. **Uploaded cover 1080×1920** with all key elements inside the **centre 1080×1080**, because the profile grid crops to 3:4 (1080×1440). Keep clear of UI bands: top ~14%, bottom ~35%, sides ~6% ([HopperHQ](https://www.hopperhq.com/blog/instagram-reel-size/), [Reap](https://reap.video/blog/instagram-reels-size), [Somake](https://www.somake.ai/blog/instagram-reel-size-guide), [MakeMoonshot](https://makemoonshot.co/blog/reel-cover-size-safe-zone)) | Reach, watch time, shares, follows |
| **Carousel** | Authority / saves | 1/week | 1080×1350 (4:5) or 1080×1080; 3–6 frames; one idea per frame; slide 1 = hook, last slide = CTA + handle | Saves, swipe-through, completion, profile visits |
| **Single image** | One offer / pinned card | ≤1 per fortnight | One legible message, wordmark, text contrast ≥4.5:1; never the week's only post | DMs, link taps |
| **Cover system** | Recognition | — | 3–5 templates (Light / Dark / Urgent), ≤5-word title, fixed wordmark corner, one accent underline; carry into Reels covers, Stories and the five Highlight covers in companion §7.9 | 3-column grid coherence, thumbnail legibility at 32–40 px |

**Topic note — now resolved in §15 (Revision 5):** the six added Reels are roughly 3 offer/CTA, 2 BTS/culture and 1 education, giving the 18-post distribution **BTS 5, offer 5, founder 3, brand 2, education 2, proof 1**. §15 confirms those counts, rebuilds the type × topic cross-tab and sets the topic target. The earlier §13.2.2/§13.2.3 tables remain labelled 12-post sub-samples.

### 14.6 Corrections this pass supersedes

| Earlier claim | Corrected finding | Source |
|---|---|---|
| 3 single / 3 carousel / 6 Reels (25/25/50) | **3 / 3 / 12 (17/17/67)** across 18 posts | §14.2 |
| June 2026 had **0** posts | June had **2 Reels** (5, 6 Jun); **April** is the zero month | §14.2 |
| A **33-day** gap 30 May → 2 Jul | 30 May → 5 Jun → 6 Jun → 2 Jul = **6 / 1 / 26 days**; longest gaps are **54 days** (10 Mar → 3 May) and **43 days** (17 Aug → 29 Sep) | §13.1, §14.2 |
| Reels run **11–81 s** | **9–81 s** (9 s launch-package Reel) | §14.2 |
| "No standalone offer post; price buried in one podcast caption" | A **6 Jun 2026 Reel** states "starts at RM1,500/month", lists three deliverables and ends with a DM CTA; a 24 May Reel offers the free consult | §14.2 |
| "No buyer-problem education" | A **10 Mar 2026 Reel** (59/0, 19 s) teaches B2B messaging clarity; it predates the visible grid by months | §14.2 |
| "No custom covers (low-confidence inference)" | **12/12** Reel thumbnails are auto-generated frames; medium confidence | §14.4 |

**What does not change:** burst-and-silence is still the cadence problem (median 6-day gaps inside bursts, two 40–55-day silences); no post in the observed corpus contains a quantified client result; hashtag typos, five vague CTAs, the unsupported "Meta 56–70%" claim and the "show me the product" comment all stand. Client-clearance tiers (companion §8.9) still apply to any proof or shoot imagery.

**What does change:** the offer is not absent — it is **impermanent**. That reframes the fix from "write an offer post" to **"give the offer a permanent surface"**: pin the 6 Jun Reel, place it in a Highlight, and link it from the bio. This is exactly the conversion-layer argument in companion §7.10, and it makes the type discussion actionable without touching topics.

### 14.7 Sources added in Revision 4

**Primary mirror evidence:** [Imginn Reels tab](https://imginn.com/reels/destined.digital/) (chunks 0–1) · individual post pages [`DZPEN_qyCfS`](https://imginn.com/p/DZPEN_qyCfS/) (6 Jun), [`DZMnNg0ElBr`](https://imginn.com/p/DZMnNg0ElBr/) (5 Jun), [`DYydxvCgce7`](https://imginn.com/p/DYydxvCgce7/) (26 May), [`DYudFl6yj_g`](https://imginn.com/p/DYudFl6yj_g/) (24 May), [`DYjuLLSSK-9`](https://imginn.com/p/DYjuLLSSK-9/) (20 May), [`DVsR8I6l-eg`](https://imginn.com/p/DVsR8I6l-eg/) (10 Mar).

**Format performance (secondary, mutually inconsistent):** [Metricool 2026 Instagram study](https://metricool.com/press-release-instagram-study-2026/) · [Wavevision / Buffer 52M-post comparison](https://www.wavevision.io/blog/instagram-carousel-posts-vs-reels-performance-comparison-2026-data) · [TryUnlockDM / Socialinsider](https://www.tryunlockdm.com/blog/instagram-reels-vs-carousels-2026) · [Futuristic Marketing carousel guide](https://futuristicmarketingservices.com/Blogs/graphic-designing/instagram-carousel-design-guide/) · [r/InstagramMarketing discussion](https://www.reddit.com/r/InstagramMarketing/comments/1ucdpbl/carousels_are_quietly_the_most_underrated_format/).

**Reel specs, covers and safe zones (secondary):** [HopperHQ](https://www.hopperhq.com/blog/instagram-reel-size/) · [Reap](https://reap.video/blog/instagram-reels-size) · [Somake](https://www.somake.ai/blog/instagram-reel-size-guide) · [Hanna-Eng](https://www.hanna-eng.com/guides/format-reels-instagram/) · [MakeMoonshot](https://makemoonshot.co/blog/reel-cover-size-safe-zone).

All figures are mirror-derived; no official analytics, no pixel inspection and no Meta primary source. Verify the full grid, covers, durations and Insights in a logged-in session.

---

## 15. Topic variety deep dive (Revision 5)

Added 8 November 2026 when the user asked to move from type to topics. This is the **authoritative topic analysis on the full 18-post corpus**. §13.2.2 and §13.2.3 are retained as labelled 12-post sub-samples that demonstrate the method. **Content type stays separate throughout (§14)** — topic is *what a post is about*, type is *how it is packaged*.

### 15.1 Method and definitions

- **One dominant topic per post**, no overlapping tags, so the six topic rows sum to exactly 18. §3's older pillar table used overlapping tags (13 tags across 12 posts) and is not comparable.
- The six topics: **Founder / people / values** · **Brand identity / manifesto** · **BTS / process / culture** · **Social proof / results** · **Offer / service / price** · **Education / industry insight**.
- Inside *Offer*, distinguish a **hard offer** (price **and** deliverables **and** how to buy in one post) from a **soft CTA** ("DM us", "chat with our team", "free consult") or a **price rationale** (a podcast clip explaining why packages cost what they do). A tag count of five offer posts can look healthy while only one is actually complete — this is the single most useful distinction in this section.
- All likes/comments are mirror-derived, not official analytics; dates are ±1 day across UTC/MYT. Topic labels are analyst judgements from captions, not Instagram metadata.

### 15.2 Full topic inventory (18 posts, chronological)

| Date | Post | Type | Topic | Offer sub-type | Likes / comments |
|---|---|---|---|---|---|
| 10 Mar | B2B messaging clarity | Reel | **Education** | — | **59 / 0** |
| 3 May | "Gen Z boss" | Carousel | Founder | — | 55 / 7 |
| 19–20 May | "Heart behind our work" | Carousel | Brand | — | 8 / 0 |
| 20 May | Team introduction | Reel | BTS | people-centred | 37 / 4 |
| 24 May | "Your brand is our privilege" | Reel | Offer | soft CTA | 21 / 0 |
| 26 May | Word-search "upgrade your socials" | Reel | Offer | soft CTA | 6 / 1 |
| 30 May | Crowded-market manifesto | Single | Brand | — | 18 / 2 |
| 5 Jun | Day in the life of an Account Manager | Reel | BTS | people-centred | 19 / 3 |
| **6 Jun** | **Launch package RM1,500/month** | Reel | **Offer** | **hard offer** | 39 / 0 |
| 2 Jul | "Last bits of June" photo dump | Reel | BTS | — | 7 / 0 |
| 5 Jul | "Smallest tweaks" | Reel | BTS | — | 10 / 4 |
| 21 Jul | Sunway AUSMAT lecture | Carousel | Founder | — | **81 / 5** |
| 31 Jul | "Christ as my business partner" | Reel | Founder | — | **61 / 9** |
| 31 Jul | Podcast: why packages start at RM1,500 | Reel | Offer | price rationale | 39 / 1 |
| 7 Aug | Client testimonial | Single | **Proof** | unquantified | 8 / 0 |
| 10 Aug | Product-shot BTS | Reel | BTS | — | 19 / 0 |
| 17 Aug | "Industries / request our packages" | Single | Offer | soft CTA | 20 / 1 |
| 29 Sep | "Meta 56–70%" creative stat | Reel | Education | unverified claim | 8 / 0 |

### 15.3 Distribution and performance

| Topic | n | Share of posts | Likes | Mean likes | Share of likes | Comments | Share of comments |
|---|---|---|---|---|---|---|---|
| **Founder / people / values** | 3 | 16.7% | 197 | **65.7** | **38.3%** | **21** | **56.8%** |
| Offer / service / price | 5 | 27.8% | 125 | 25.0 | 24.3% | 3 | 8.1% |
| BTS / process / culture | 5 | 27.8% | 92 | 18.4 | 17.9% | 11 | 29.7% |
| Education / industry insight | 2 | 11.1% | 67 | 33.5 | 13.0% | 0 | 0% |
| Brand identity / manifesto | 2 | 11.1% | 26 | 13.0 | 5.0% | 2 | 5.4% |
| **Social proof / results** | **1** | **5.6%** | 8 | **8.0** | **1.6%** | **0** | **0%** |
| **Total** | **18** | 100% | **515** | 28.6 | 100% | **37** | 100% |

**Seven readings:**

1. **Founder is the engine.** 17% of posts produce 38% of likes and **57% of comments**. Mean 65.7 vs **21.2** for all other topics combined (318 likes / 15 posts) ≈ **3.1×**, not the "~4×" from the 12-post overlapping-tag sample.
2. **Correction:** *"every post above 50 likes is about a person"* no longer holds. Four posts clear 50 likes — 81, 61, 59, 55 — three founder and one **education** (10 Mar B2B messaging, 59/0). But that education post drew **zero comments**, whereas the three founder posts drew 21 between them. Education can buy attention; people buy conversation.
3. **Proof is the weakest topic and the biggest gap.** One post, 8 likes, 0 comments, and it contains no number — while `/testimonials` holds real growth screenshots. Client confidentiality (companion §8.9) constrains direct reuse, making this the hardest gap to close; clearance-free substitutes are not optional.
4. **Offer is not scarce, it is thin.** Five posts (28%) but only **one hard offer** (6 Jun: price + three deliverables + DM CTA). Three are soft CTAs, one is a price rationale inside a podcast clip. Across all five, **3 comments total**, no DM keyword, no link, no measurable CTA — and only one offer post exists after 31 Jul.
5. **BTS is the second conversation driver** (11 comments, 30% of all comments) despite a low 18.4-like mean. Its two best posts — team intro (37/4) and day-in-the-life (19/3) — are both **people-centred**: the founder effect leaking into the BTS topic.
6. **Education is polarised and silent.** 59/0 and 8/0, both zero comments; the latter carries an unsupported "Meta 56–70%" claim. "WHERE DREAMS MEET DATA" is demonstrated by neither.
7. **Brand manifesto is saturated.** Two posts, 5% of likes. No new manifestos are needed.

### 15.4 Type × topic cross-tab, rebuilt for 18 posts

| Topic ↓ / Type → | Single image | Carousel | Reel | n |
|---|---|---|---|---|
| Founder / people | — | 55, 81 | 61 | 3 |
| Brand identity / manifesto | 18 | 8 | — | 2 |
| BTS / process / culture | — | — | 7, 10, 19, 37, 19 | 5 |
| Social proof / results | 8 | **—** | **—** | 1 |
| Offer / service / price | 20 | **—** | 39, 21, 6, 39 | 5 |
| Education / industry insight | — | **—** | 59, 8 | 2 |
| **Total** | **3** | **3** | **12** | **18** |

**9 of 18 cells are still empty** — the same count as the 12-post sub-sample, but with different contents and much better evidence:

- **Carousels still carry only founder + brand.** With 18 posts observed, not one carousel has been used for proof, offer, education or BTS. The format with the highest mean engagement has never carried a commercial topic.
- **Three of six topics are welded to one type:** BTS 5/5 Reels, Education 2/2 Reels, Proof 1/1 single image.
- **Proof sits in the weakest type**, and BTS/education sit only in the type with the widest performance variance.
- **Offer has no carousel**, so a service explainer (deliverables, timeline, who it is for, price) has never been built in the format that earns saves.

The mismatch is therefore a *topic* problem as much as a type problem: there is no rule saying a commercial topic must appear in a save-worthy type. Fixing type variety alone gave more Reels about BTS; fixing topic variety alone would give more proof posts that are still single images. **The fix lives in the cells** (§13.2.4 guardrail: every recurring topic in ≥2 types per 4-week cycle).

### 15.5 Buyer-journey coverage (5As / AIDA, MKW1120 Lecture 9)

| Stage | What the buyer needs | Topics that serve it | Corpus | Verdict |
|---|---|---|---|---|
| **Aware / Attention** | Name the problem; see a human | Founder, Brand, BTS | **10 / 18 (56%)** | Over-served |
| **Appeal / Interest** | Demonstrate expertise | Education | 2 / 18 (11%) | Thin; one claim unverified |
| **Ask / Consideration** | Method, comparison, deliverables, process | Service explainer, education | **0 dedicated** | Missing |
| **Act / Decision** | Price, how to buy, measurable CTA, proof | Offer, Proof | 5 tagged / **1 hard offer** / 0 measurable CTA | Weak |
| **Advocate / post-purchase** | Cleared results, client story, UGC | Proof | 1 / 18, no number | Missing |

Secondary 2026 B2B guidance agrees on the shape of the gap: educational content for awareness, comparisons and case studies for consideration, pricing/testimonials/demos for decision ([Infuse](https://infuse.com/glossary/content-marketing/), [GrowWithSakib](https://growwithsakib.com/content-mapping-buyer-journey/), [FanSpicy](https://fanspicy.com/insights/types-of-content-marketing-a-2026-strategy-guide/)); GrowWithSakib's audit framing argues **decision-stage gaps convert existing attention fastest** and should be fixed before adding more awareness content. [Komet Media](https://www.kometmedia.com/blogs/instagram-growth-playbook-for-b2b-saas) and [1into2](https://www.1into2.com/instagram-marketing-strategies-for-b2b-brands/) make the same case for customer-proof carousels and a weekly case-study habit.

**Bottom line:** the feed is a top-of-funnel machine with almost no bottom-of-funnel furniture. The *"Okay great marketing. Now show me the product where can I get it"* comment is a **decision-stage buyer arriving at an awareness-stage grid** (Lecture 9 slides 10, 15; Lecture 5 slides 30–35 on high-involvement B2B search; Lecture 1 slide 6, needs alignment).

### 15.6 The topic target, made operational

§13.2.4 already separates the **type target** (2 Reels + 1 carousel/week) from the **topic target**. Here is the topic side, applied to an illustrative 4-week cycle of 12 posts at 3/week:

| Topic | Current (18 posts) | Target | First move |
|---|---|---|---|
| Buyer-problem education | 2 (11%) | **~40% (5)** | Turn the 10 Mar messaging Reel into a repeatable carousel series; reuse their own TikTok scripts; primary sources only |
| Proof / results | 1 (6%) | **~30% (3–4)** | One number per post, cleared/anonymised/owned; if clearances are unavailable use the green-tier substitutes in companion §8.9 (own-account experiments, spec work, aggregate counts, method-not-metrics) |
| BTS / culture | 5 (28%) | **~20% (2)** | Keep only the people-centred variants that earned comments |
| **Hard** offers | **1 of 5 tagged** | **~10% (1)** | Price + deliverables + who it's for + one measurable CTA (`DM "AUDIT"` or the consult link). **Pin, Highlight and link the 6 Jun Reel** rather than reinventing it |
| Founder | 3 (17%) | Fold into education/proof as the **presenter** | Founder-led Reel: one buyer problem → one fix → one CTA |
| Brand manifesto | 2 (11%) | 0–1 | No new manifestos |

Two caveats. (1) The 40/30/20/10 split is §9's **hypothesis**, not an industry standard — 2026 B2B guides conflict ([BrandRoad](https://brandroad.in/blog/instagram-growth-b2b-brands-2026) 40/25/20/15; [1into2](https://www.1into2.com/instagram-marketing-strategies-for-b2b-brands/) 40/30/20/10; [Scale Growth](https://scalegrowth.digital/resources/social/instagram-content-ideas/) 40/30/20/10 educate/engage/promote/entertain; [ProMentor](https://promentordigitalsolutions.com/instagram-marketing-for-small-businesses-what-actually-works-in-2026/) 70/20/10). Validate at 4 weeks against **saves, DMs and consults**, not likes. (2) A 30% proof target is ambitious under the confidentiality constraint; the clearance mechanisms in §8.9 (written permission, cleared-client list, anonymisation checklist, "Shared with permission; data redacted" footer) are what make it achievable, and clearance-free substitutes keep the slot filled when they are not.

### 15.7 Corrections superseded in this pass

| Earlier claim | Corrected finding | Where |
|---|---|---|
| "Every post above 50 likes is about a person" (§3, §6, §13.2.2) | **3 of 4**; the fourth is the 10 Mar **education** Reel (59/0) | §15.3 |
| "People outperform corporate copy by ~4× / ~49 vs ~12" | **~3.1× / 65.7 vs 21.2** across 18 posts | §15.3 |
| Topic distribution (12-post): founder 3, BTS 3, brand 2, offer 2, proof 1, education 1 | **founder 3, BTS 5, offer 5, brand 2, education 2, proof 1** | §15.3 |
| "No buyer-problem education" | One 10 Mar Reel exists (59/0); it earns attention but no conversation | §14.6, §15.3 |
| "No standalone offer post" | One **hard offer** (6 Jun) plus three soft CTAs and one price rationale | §14.6, §15.3 |
| "9 of 18 cells empty" (12-post cross-tab) | Still 9 of 18, but different cells; carousels still only founder + brand | §15.4 |
| "40/30/20/10" as a bare ratio | Retained, but now operational: hard vs soft offers, proof substitutes, presenter role for founder | §15.6 |

**Unchanged:** no quantified client result anywhere in the 18 posts; hashtag typos; five vague CTAs; the unsupported Meta stat; the 54- and 43-day silences; the confidentiality tiers. **Reframed:** offer scarcity → offer *impermanence and incompleteness*; "no proof" → one proof post with no number, blocked mainly by clearance rather than by data availability.

### 15.8 Sources added in Revision 5

**Buyer-journey / content mapping (secondary):** [Infuse — content marketing glossary](https://infuse.com/glossary/content-marketing/) · [GrowWithSakib — content mapping to the buyer journey](https://growwithsakib.com/content-mapping-buyer-journey/) · [FanSpicy — types of content marketing 2026](https://fanspicy.com/insights/types-of-content-marketing-a-2026-strategy-guide/) · [Dummies — content across the buyer journey](https://www.dummies.com/article/how-can-content-marketing-educate-customers-throughout-the-buyer-journey/).

**B2B topic mixes (secondary, mutually inconsistent):** [BrandRoad](https://brandroad.in/blog/instagram-growth-b2b-brands-2026) · [1into2](https://www.1into2.com/instagram-marketing-strategies-for-b2b-brands/) · [Komet Media](https://www.kometmedia.com/blogs/instagram-growth-playbook-for-b2b-saas) · [ProMentor](https://promentordigitalsolutions.com/instagram-marketing-for-small-businesses-what-actually-works-in-2026/) · [Scale Growth Digital](https://scalegrowth.digital/resources/social/instagram-content-ideas/).

**Primary evidence:** the 18 post pages listed in §12 and §14.7. **Course material:** MKW1120 Lectures 1 (s6), 5 (s30–35), 7 (s29, s32), 9 (s10, s15, s22), plus the IMC consistency argument in §8.

All secondary sources are practitioner/commercial guides with conflicting ratios; none is a Meta rule. All engagement figures are a mirror sample; no official analytics, no pixel inspection. Confirm topic labels, pins, clearances, saves, DMs and consults in a logged-in session.

---

## 16. Twenty golden static / carousel post ideas (Revision 6)

The client asked to move on to **posts, specifically statics**: "Give me 20 golden ideas for static posts/carousels." This section answers that on the **content type** axis only.

### 16.1 What "static" and "golden" mean here

**Static = the two non-video feed containers** (Revision 3 terminology): `FEED` (a **single image**, one frame) and `CAROUSEL_ITEM` (a **carousel**, two or more frames). Reels (`CLIPS`) are a different surface and Stories/Highlights are a separate surface entirely; neither is in scope here. **Type (the container) and topic (the subject) stay orthogonal** — the `Type` and `Topic` columns below are independent axes, not a blended "content mix". The topic labels are shown only so the buyer-journey gaps from §15.5 are visible.

**"Golden" is a five-part test**, not a compliment:

1. It earns a **save** — a checklist, framework, comparison or recap someone wants back (§14.5: carousels are the authority / saves slot).
2. It is grounded in **this account's own evidence** — the 18-post corpus, not generic 2026 advice.
3. It fills a **measured gap** — the missing consideration stage, the empty Offer × Carousel cell, the numberless proof post.
4. It is **clearance-free (green tier, companion §8.9)** — no client names, logos, quotes, results, dashboards, screenshots, packaging or unreleased work.
5. It has **one specific CTA** and one job per post — not a manifesto, not a vague "thoughts?".

**A note on effort.** The client's low-effort correction (§8.12) applied to **24-hour Stories**. A permanent feed post is a different surface: one design pass is justified because the asset stays on the grid. The `Lift` column still flags which ideas **reuse an existing asset** so the batch stays small — build one 4:5 master once and reuse it for all fourteen carousels. These twenty are a **menu, not a 4-week calendar**; the rhythm stays §14.5's **1 carousel/week and ≤1 single/fortnight**.

### 16.2 Why statics are where the leverage is

| Type | Posts (18) | Mean likes | Mean comments | What §14–§15 found |
|---|---|---|---|---|
| **Reel** (`CLIPS`) | 12 (67%) | 27.1 | 1.8 | Dominates the grid; auto-generated covers; discovery, not depth |
| **Carousel** (`CAROUSEL_ITEM`) | **3 (17%)** | **48.0** | 4.0 | Highest mean likes, but **only founder + brand topics** ever used it |
| **Single image** (`FEED`) | 3 (17%) | 15.3 | 1.0 | Weakest; used as filler rather than identity |

Three gaps make statics the highest-return fix: **9 of 18 type × topic cells are empty**; there is **no dedicated consideration-stage post** (§15.5); and **no post in the corpus contains a quantified client result**. Founder topics average **65.7 likes vs 21.2 for everything else** — so the founder belongs *as the presenter*, not as another manifesto. The single hardest evidence point remains the *"Okay great marketing. Now show me the product where can I get it"* comment: a decision-stage buyer arriving at an awareness-stage grid. A carousel is the cheapest permanent place to answer it.

*External 2026 guidance points the same way but disagrees on magnitude:* [Metricool](https://metricool.com/press-release-instagram-study-2026/) reports carousels earning ~9× the saves of single images and single-image reach down ~22% YoY, while [Adpicto](https://www.adpicto.com/en/blog/instagram-carousel-best-practices-2026) says ~35% more saves and [Krumzi](https://www.krumzi.com/blog/15-instagram-carousel-ideas-that-actually-drive-engagement-in-2026) ~22%; [Flockx](https://flockx.io/blog/instagram-carousels-2026) claims 5× the save rate. None is a Meta rule and none is Destined Digital analytics; all are secondary, mutually inconsistent benchmarks. Our own 18-post sample has only **3 carousels and 3 singles**, so the 48.0 vs 15.3 gap is directional, not proof.

### 16.3 The twenty ideas

| # | Golden idea | Type | Topic | Why it earns the slot | Lift |
|---|---|---|---|---|---|
| **S1** | **"Your reach isn't the problem — your offer is"** (6 slides: 3 diagnosis questions, what to check, recap) | `CAROUSEL` | Education | Converts the 10 Mar education Reel (59/0) into a save-worthy container and opens the missing consideration stage | 5–8 slides |
| **S2** | **"The 3 questions we ask before any ad spend"** | `CAROUSEL` | Education | Own method, one question per slide, zero research; checklist is the most-saved layout | 5–8 slides |
| **S3** | **"5 things to fix on a small business profile before spending on ads"** | `CAROUSEL` | Education | Geography-free pre-flight checklist with an explicit "save this" CTA | 5–8 slides |
| **S4** | **"What 'full-service' actually includes"** (one service per slide, who it is for, what is not included) | `CAROUSEL` | Offer | Fills the empty Offer × Carousel cell and answers "where can I get it" | 5–8 slides |
| **S5** | **"The launch package: what you get, what you don't, who it's for"** | `CAROUSEL` | Offer | Gives the 6 Jun hard offer a **permanent, pinnable** surface; verify the RM1,500 price is still current first | 5–8 slides |
| **S6** | **"We rewrote our own caption. Here's what changed"** (before / after) | `CAROUSEL` | Proof | Own-account experiment is green-tier proof with no client data | 5–8 slides |
| **S7** | **"One post, three hooks: which would make you stop?"** | `CAROUSEL` | Proof | Shows the method on an **existing** own post; no new shoot | Reuse + slides |
| **S8** | **"12 reviews this quarter: what people mentioned most"** | `CAROUSEL` | Proof | Rounded aggregate **only** — no names, quotes, logos or exact metrics | 5–8 slides |
| **S9** | **"Spec work: how we'd launch a fictional brand in 5 posts"** | `CAROUSEL` | Proof | §8.9 spec-work substitute demonstrates capability without exposing client work | 5–8 slides |
| **S10** | **"Method, not metrics: the 4 steps of our audit"** | `CAROUSEL` | Proof | Decision-stage process explainer with zero confidential data | 5–8 slides |
| **S11** | **"The 8-point profile audit checklist (save this)"** | `CAROUSEL` | Education | Checklist + recap slide is the strongest save trigger; one measurable CTA (`DM "AUDIT"`) | 5–8 slides |
| **S12** | **"Posting daily is hurting you. Do this instead"** | `CAROUSEL` | Education | Contrarian **hook, not a title** — opens a curiosity gap on slide 1 | 5–8 slides |
| **S13** | **"Anatomy of a caption that gets a reply"** (annotated own caption) | `CAROUSEL` | Education | The source asset already exists; annotation is the whole production job | Reuse + slides |
| **S14** | **"Founder note: the mistake we made in year one"** (one photo + long caption) | `FEED` | Founder | Founder topics average 65.7 vs 21.2 likes; one human note, **not** another brand manifesto | Reuse |
| **S15** | **"A day in 6 frames" (11am → 2pm)** | `CAROUSEL` | BTS | Photo-led carousel of own team; people-centred posts carry **57% of all comments**; adapts the client's own §8.13 idea #2 to feed | Reuse |
| **S16** | **"We're booking [month]"** | `FEED` | Offer | Single images are for identity and announcements, not reach; one card, one CTA | 1 card |
| **S17** | **One-line method card** (one own line on a plain card) | `FEED` | Brand | Keeps the grid intentional between carousels; nothing new to design | 1 card |
| **S18** | **"Meet [name]"** | `FEED` | BTS | One phone photo + caption; staff consent captured once; no client material | Reuse |
| **S19** | **"New checklist is live — swipe"** (points to S11) | `FEED` | Brand | Useful as a pointer; use sparingly because singles are ≤1 per fortnight | 1 card |
| **S20** | **"The question we get most"** | `FEED` | Education | One Q, one-line A, pointer to the `FAQ` Highlight (companion §7.9) | 1 card |

**Axis check:** 14 `CAROUSEL` + 6 `FEED` — roughly the 2:1 ratio implied by §14.5's 1 carousel/week and ≤1 single/fortnight. Topics are approximately **7 education, 5 proof, 3 offer, 2 BTS, 2 brand, 1 founder**, close to §15.6's 40/30/20/10 hypothesis with the founder folded in as presenter. That is a *topic* observation, not a new type target; validate at four weeks against **saves, DMs and consults**, not likes.

### 16.4 Golden build spec — build once, reuse fourteen times

| Rule | Spec | Why |
|---|---|---|
| Canvas | **1080×1350 (4:5)**; keep every slide in one orientation; text inside the 3:4 grid crop safe zone | Tall portrait takes the most feed space; the grid trims ~6% of width ([Carouselli](https://carouselli.com/blog/instagram-carousel-best-practices), [xcarousel](https://xcarousel.com/blog/instagram-carousel-best-practices), [Vucifer](https://www.vucifer.com/blog/instagram-carousel-design)) |
| Slide 1 | A **hook, not a title** — a specific number, a mistake frame or a counterintuitive claim; never a logo or "Introduction" | It is the only slide most people see ([Carouselli](https://carouselli.com/blog/instagram-carousel-best-practices), [CreatorFlow](https://creatorflow.so/blog/instagram-carousel-posts-guide/)) |
| Length | **5–8 slides**, one idea per slide, ≤25–40 words per slide | Guides conflict (4–6, 5–8, 8–10, 8–12); 5–8 is a practical compromise for completion ([Flockx](https://flockx.io/blog/instagram-carousels-2026), [Krumzi](https://www.krumzi.com/blog/15-instagram-carousel-ideas-that-actually-drive-engagement-in-2026)) |
| Last slide | **Recap / summary + one specific CTA** + handle | The recap is the most save-friendly slide; saves and DM-sends are the strongest Feed-side signals ([xcarousel](https://xcarousel.com/blog/instagram-carousel-best-practices)) |
| System | One type pairing, one accent, fixed wordmark corner across all slides | §13.4's hex codes are **illustrative, NOT observed** — no official DD palette was found and no pixels were inspected |
| Caption | Adds context, does not repeat the graphic; one CTA; no unverified stats | The unsupported "Meta 56–70%" claim and the hashtag typos stay out |
| Single images | One legible message, contrast ≥4.5:1, readable at 32–40 px thumbnail | §14.5: never the week's only post |

### 16.5 What is deliberately excluded

Generic 2026 "static post idea" lists lean heavily on **screenshots of wins, review screenshots, customer-before-and-after cards, UGC reshares, DM screenshots and client quote graphics** ([Postoria](https://postoria.io/blog/ideas-for-static-posts), [Socialz](https://socialz.ai/blog/instagram-post-ideas), [Hyperwrite](https://www.hyperwriteai.com/articles/b2b-social-media-content-ideas), [AiGrow](https://models.aigrow.me/instagram-post-ideas/)). **None of those appear above.** Under the client's confidentiality constraint (companion §8.9) they are Amber or Red: they need written permission, anonymisation and a cleared bank first. S6–S10 are the green-tier substitutes — own-account experiments, spec work, aggregate counts and method-not-metrics. Once a cleared-client list exists, a cleared case-study carousel can replace S9 without changing the format.

Also excluded: new brand manifestos (§15.6), geography claims (§7.4 makes "who we serve" conditional, not "where we are"), exact pricing beyond a verified current rate, and any claim about official analytics, saves, reach, pins, exact visuals or the full post history. The mirror sample stops at 29 Sep 2026 and is incomplete.

### 16.6 Sources added in Revision 6

**Carousel craft / specs (secondary):** [Carouselli — 12 rules for 2026](https://carouselli.com/blog/instagram-carousel-best-practices) · [CreatorFlow — sizes, templates and 12 tips](https://creatorflow.so/blog/instagram-carousel-posts-guide/) · [Krumzi — 15 carousel ideas](https://www.krumzi.com/blog/15-instagram-carousel-ideas-that-actually-drive-engagement-in-2026) · [xcarousel — best practices that hold up in 2026](https://xcarousel.com/blog/instagram-carousel-best-practices) · [Vucifer — sizes, slide counts, layouts](https://www.vucifer.com/blog/instagram-carousel-design).

**Static-post idea banks (secondary):** [Postoria — 100 static post ideas](https://postoria.io/blog/ideas-for-static-posts) · [Hyperwrite — 50+ B2B social ideas](https://www.hyperwriteai.com/articles/b2b-social-media-content-ideas) · [Socialz — 50+ Instagram post ideas](https://socialz.ai/blog/instagram-post-ideas) · [Avenuez — 2025/2026 organic guide](https://avenuez.com/blog/2025-2026-instagram-organic-social-media-guide-for-brands/) · [AiGrow — 50+ post ideas](https://models.aigrow.me/instagram-post-ideas/).

**Format benchmarks (secondary, mutually inconsistent):** [Metricool 2026 study](https://metricool.com/press-release-instagram-study-2026/) · [Adpicto](https://www.adpicto.com/en/blog/instagram-carousel-best-practices-2026) · [Mean CEO — carousel statistics](https://blog.mean.ceo/instagram-carousel-engagement-statistics/) · [Flockx](https://flockx.io/blog/instagram-carousels-2026) · [r/InstagramMarketing](https://www.reddit.com/r/InstagramMarketing/comments/1ucdpbl/carousels_are_quietly_the_most_underrated_format/).

**Primary evidence:** the 18 post pages in §12 and §14.7; §14 (type) and §15 (topic) of this document; companion §8.9 (confidentiality tiers), §7.9 (Highlights), §7.4 (geography), §8.13 (the client's four ideas). **Course material:** MKW1120 Lectures 9 (AIDA / 5As, IMC), 5 (buyer decision process), 7 (services, positioning), 1 (needs alignment).

*All secondary sources are practitioner or commercial guides with conflicting slide counts and save multipliers; none is a Meta rule and none is Destined Digital analytics. All engagement figures are a mirror sample; no official analytics, no pixel inspection, no exhaustive post history. Recommendations are proposals, not observed changes. Confirm pins, clearances, current pricing, saves, DMs and consults in a logged-in session.*

---

## 17. The client's proposal skeleton — five slots (Revision 7)

The client is drafting **their own proposal** and listed:

1. **3 pinned posts**
2. **before and after; brainstorming to final product**
3. **gen z lifestyle / advertising memes**
4. **aesthetic / comfy shoots and work life** *(reading "work like" as work life / what the work looks like)*
5. **still thinking...**

This section is a **thinking aid**, not a finished proposal and not a recommendation to publish. It records the skeleton, separates two things that are currently mixed, reads #2–4 against the 18-post corpus, and proposes a fifth.

### 17.1 One structural fix before writing it up

**Item 1 is a placement; items 2–4 are content series.** The three pinned posts are a **profile surface** — a fixed first row answered in companion §7.11–§7.13. The other three are **recurring feed/Story series**. Presenting all five as one numbered list of equal "types" will read as if pinning is a content pillar. Split the proposal into two short sections: **profile setup** (name, links, three pins, five Highlights) and **recurring series** (#2–#5).

**Also keep the two axes separate** (Revision 3, §0, §13.2): **type** = the container (`FEED` single, `CAROUSEL_ITEM`, `CLIPS` Reel, Story); **topic** = the subject (founder, BTS, proof, offer, education). Each series can be rendered in more than one type. For example, "brainstorming to final product" is a **topic** (process/method) that could be a carousel, a Reel or a Story sequence. Use two columns in the proposal table; never one blended "content mix" number.

### 17.2 Reading the four against the evidence

| Item | What it actually is | Topic axis | What it does well | Watch out |
|---|---|---|---|---|
| **1 — 3 pinned posts** | Placement / conversion layer | — | Answers who / what / why-trust before a scroll; ~10 min, no new assets (companion §7.13) | Not a content series; keep it in a separate section |
| **2 — before / after, brainstorm → final** | Process reveal / transformation | Method + BTS | Shows **how you work**; the closest thing to the **0 dedicated consideration-stage posts** (§15.5); strong as a save-worthy carousel | If the "final product" is **client work**, it needs written clearance. Use own / spec / fictional-brand work otherwise ([Zolyp](https://www.zolyp.com/social-media-for/marketing-agencies), [Agorapulse](https://www.agorapulse.com/blog/instagram-content-creation/content-tips-for-social-media-agencies-on-instagram/)) |
| **3 — gen z lifestyle / advertising memes** | Brand voice / culture | Brand + BTS | Matches the locked bio line "marketing doesn't have to be boring or repetitive"; shareable; people-centred posts carry **57% of all comments** (§15.3) | **Awareness only** — the corpus is already **56% awareness** (10/18). Agency memes are often **peer-facing**, not buyer-facing. Don't let casting/model drift follow (§6.6 / Threads topic tags), and don't let this become the dominant series |
| **4 — aesthetic / comfy shoots & work life** | BTS / culture | BTS | Strongest engagement lever: founder/people **65.7 vs 21.2 mean likes**; green tier with staff consent; phone-only, low effort | "Aesthetic" risks becoming a grading/design pass — 2026 raw lo-fi beats produced (§8.13). BTS is already **5/18 (28%)** against a ~20% hypothesis; no client products, logos, screens or dashboards in frame |

### 17.3 What the four leave out

All four sit at the **top of the funnel**. Three buyer questions have no recurring home:

- **"What do you sell and how do I buy it?"** — decision stage: **1 hard offer**, impermanent, and the *"show me the product where can I get it"* comment still unanswered in the grid (§14.6, §15.5).
- **"Did it work?"** — proof: **1 numberless proof post**, **0 quantified client results** in 18 posts (§15.3, §15.7).
- **"Teach me something I'll save."** — education: **2/18 (11%)**, one of them carrying an unverified stat (§15.3).

§15.6's **40% education / 30% proof / 20% BTS / 10% hard offer** is a **hypothesis, not an industry standard** — 2026 B2B guides conflict, though most agree on education + proof + BTS as the three pillars ([BrandRoad](https://brandroad.in/blog/instagram-growth-b2b-brands-2026) 40/25/20/15, [1into2](https://www.1into2.com/instagram-marketing-strategies-for-b2b-brands/) 40/30/20/10, [Komet Media](https://www.kometmedia.com/blogs/instagram-growth-playbook-for-b2b-saas) four pillars, [Chrysales](https://www.chrysales.com/post/instagram-b2b-lead-generation-89181) proof / teaching / personal). In MKW1120 terms (Lecture 9 AIDA / 5As, Lecture 5 high-involvement B2B search), #2–4 cover **Attention / Appeal**; **Ask, Act and Advocate** have no recurring series. Treat that as a gap to fill, not a quota to obey.

### 17.4 A fifth slot — recommendation

**My pick for #5: "Proof / results — clearance-safe".** Reasons: it is the **largest measured gap** (0 quantified results; 30% hypothesis), it is the series that **converts**, it is **distinct from #2** (process shows *how*, proof shows *what it achieved*), and it keeps the pinned proof slot (companion §7.13) supplied with fresh material. Use green-tier versions until written permission exists:

| Green-tier version (no clearance) | Example |
|---|---|
| Own-account experiment | "We rewrote our own caption. Here's what changed" (§16 S6) |
| Spec / fictional-brand work | "How we'd launch a fictional brand in 5 posts" (§16 S9) |
| Aggregate counts, no identifiers | "12 reviews this quarter: what people mentioned most" (§16 S8) |
| Method-not-metrics | "The 4 steps of our audit" (§16 S10) |
| Once cleared | An anonymised case study with **one number** + "Shared with permission; data redacted" (§8.9, §8.13) |

**Runners-up, if you would rather use one of these:**

| Candidate | Fills | Ready-made ideas |
|---|---|---|
| **Save-worthy education / checklists** | The 40% education target; saves, shares, search | §16 S1–S3, S11–S13 |
| **What we do / how to start** (services + offer) | Decision stage; the "show me the product" comment | §16 S4, S5; already pinned slot 2 under §7.13 |
| **Client-review series** | Advocate stage | §8.13 cleared bank — **needs written clearance first** |

**If the proposal has room for a sixth**, add **save-worthy education/checklists** alongside proof: the two together cover Ask/Act/Advocate without adding more awareness content. That gives the proposal a clean split — **one profile setup + two culture/process series + two buyer-facing series**.

### 17.5 Guardrails for the write-up

- **Confidentiality (§10, companion §8.9):** no client name, logo, handle, quote screenshot, dashboard, packaging or unreleased work in #2 or #4 without written permission; staff consent captured once; no raw client analytics.
- **Low effort:** #3 and #4 should stay phone-only and unpolished (§8.12–§8.13); "aesthetic" is a *feel*, not a production step.
- **Don't over-weight BTS/memes:** awareness 10/18 and BTS 5/18 are already the two largest buckets.
- **Separate axes, menu not calendar:** state the **type** and **topic** of each series in separate columns; the §14.5 rhythm (2 Reels + 1 carousel/week, ≤1 single/fortnight, 2–3 Story days) is where cadence lives — don't turn this list into a 4-week calendar.
- **Evidence limits:** 18 mirror posts, no official analytics, no exhaustive history, no exact visuals, no observed palette. Every number above is a mirror-derived sample; the 40/30/20/10 split is a hypothesis to validate at four weeks against saves, DMs and consults, not likes.

### 17.6 Sources added in Revision 7

**B2B pillar / buyer-journey guidance (secondary, mutually inconsistent):** [BrandRoad — B2B Instagram growth 2026](https://brandroad.in/blog/instagram-growth-b2b-brands-2026) · [1into2 — B2B Instagram strategies](https://www.1into2.com/instagram-marketing-strategies-for-b2b-brands/) · [Komet Media — B2B SaaS playbook](https://www.kometmedia.com/blogs/instagram-growth-playbook-for-b2b-saas) · [UseVisuals — four-pillar structure](https://usevisuals.com/blog/b2b-saas-instagram-strategy-2026) · [Chrysales — proof / teaching / personal](https://www.chrysales.com/post/instagram-b2b-lead-generation-89181).

**Agency before/after and client permission:** [Zolyp — social media for marketing agencies](https://www.zolyp.com/social-media-for/marketing-agencies) · [Agorapulse — agency content tips and NDA caveat](https://www.agorapulse.com/blog/instagram-content-creation/content-tips-for-social-media-agencies-on-instagram/) · [Crescitaly — rights and consent register 2026](https://blog.crescitaly.com/meta-muse-instagram-creator-rights-opt-out-checklist-2026/).

**Primary evidence:** the 18 post pages in §12 / §14.7; §14 (type), §15 (topic), §16 (static ideas) and companion §7.11–§7.13 (pins), §8.9 (confidentiality), §8.12–§8.14 (Stories). **Course material:** MKW1120 Lectures 9 (AIDA / 5As, IMC), 5 (buyer decision process), 7 (services, positioning).

*All external sources are practitioner guides with conflicting ratios; none is a Meta rule or Destined Digital analytics. Recommendations are proposals, not observed changes. The client-review clearance decision (§8.13), the "product poster" scope question, the saved-Highlight-cover date caveat (§8.7/§8.10) and the public-GitHub privacy question all remain open.*

---

*Desk research from publicly accessible sources only. All engagement figures are a mirror sample, not official analytics; visual conclusions are low-confidence inferences. No client-confidential material is included. Recommendations are proposals, not observed changes. Revision 2 (§13) adds decoded CDN media tags, automated asset descriptions and secondary 2026 design/frequency guidance; Revision 3 separates content type from topic variety (§13.2); Revision 4 expands the corpus to 18 posts and adds the type deep dive (§14); Revision 5 rebuilds topic variety on the same 18 posts (§15); Revision 6 adds twenty golden static / carousel ideas and a build-once spec (§16); Revision 7 records the client's proposal skeleton and a recommended fifth series (§17). All of it remains to be verified in a logged-in session.*
