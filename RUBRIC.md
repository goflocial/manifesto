# The Flocial Rubric

**Draft v0.1 · October 2026 · CC BY-SA 4.0 · Open for public comment**

An optional module, for flocial networks that bring outside organizations in: how they decide which ones a
community sees, and in what order. Outside
organizations here means businesses, news organizations, nonprofits, congregations and apps.

Built on four commitments from the [Manifesto](MANIFESTO.md):
- **#19** Outside voices come in by invitation.
- **#20** Standing is earned by conduct.
- **#18** Each community writes its charter.
- **#22** Let others check.

---

## 1. Two axes, kept apart

| | **Conduct** | **Fit** |
|---|---|---|
| Question | *Does this organization behave well?* | *Does it suit this community?* |
| Who decides | The rubric, applied by an independent scorer | The community, through its private [Community Charter](COMMUNITY-CHARTER.md) |
| Visibility | Public, with the evidence linked | Private to the community · never shared with providers |
| Judges beliefs? | **Never.** Conduct only. | Yes, if the community wants. That's its right. |
| Can money change it? | **Never.** | **Never.** |

This split resolves the hardest problem in the brief. A news outlet, a congregation or an advocacy nonprofit
is scored on **how it operates**:
- honesty
- transparency
- safeguarding
- accountability

Whether a community shares its views is the community's call, made privately, and never by the platform
[E26](EVIDENCE.md#E26) [E43](EVIDENCE.md#E43).

---

## 2. Gates first

A gate is disqualifying. **Gates are never averaged away by good scores elsewhere.**
- An organization that fails a gate isn't listed.
- If it's already listed, it's suspended pending appeal.
- Each gate is about conduct, never about belief.

| Gate | Fails if the organization… | Evidence that counts |
|---|---|---|
| **G1 Data** | sells, rents or brokers personal data, or shares it for advertising outside the transaction | privacy policy, regulator findings, credible reporting |
| **G2 Children** | targets advertising or unsolicited contact at minors, or markets age-restricted products to them | practices, enforcement actions |
| **G3 Deception** | has an unremedied legal finding or regulator enforcement for deceptive or unfair practices in the last 3 years, or uses fake reviews or fake urgency | court and regulator records [E17](EVIDENCE.md#E17) |
| **G4 Hidden money** | has paid relationships it doesn't disclose (sponsored content, affiliate deals, paid endorsements) | [E41](EVIDENCE.md#E41) |
| **G5 Harm to people** | organizes or incites violence or harassment against people (conduct, not opinion) | documented actions |
| **G6 Safeguarding** | serves children with no safeguarding policy, or has an unremedied safeguarding failure | policy documents, findings |
| **G7 Anonymity** | won't disclose who owns or controls it | registrations, disclosures |

**Remedy path:** a provider that fails a gate can be listed again after showing the practice has ended and
the people harmed were made whole.

---

## 3. Then grades: the conduct score

Six universal dimensions, each scored **0–4**:

| Dimension | 0 | 2 | 4 |
|---|---|---|---|
| **D1 Privacy & data** | collects broadly, unclear purpose | collects only what it needs, but with weak controls | minimal collection, clear deletion, never shares beyond the transaction |
| **D2 Honesty & disclosure** | hidden fees, vague claims | mostly clear | all-in pricing, plain-language terms, funding and ownership disclosed |
| **D3 Safety & children** | no policies | basic policies | safe defaults, safeguarding, a clear reporting route |
| **D4 Fairness & give-back** | extractive terms | standard terms | fair to workers and customers, gives back to communities (in kind or in money) |
| **D5 Accountability** | ignores complaints | responds | public corrections or complaint process, outside audits, remedies people |
| **D6 Category conduct** | | | from the category module below |

**Score** = the mean of D1 to D6, reported with a **confidence level**:

| Evidence behind a criterion | Effect |
|---|---|
| Independently verified (audit, certification, court record) | Full confidence |
| Public documentation | Normal confidence |
| Self-attestation only | Scored, but **capped at 3** until verified, and marked "self-reported" |
| Unknown | Marked "unknown". It lowers confidence and **is not treated as bad**. |

**Display bands:**

| Band | Score |
|---|---|
| **Exemplary** | 3.5 and above |
| **Strong** | 2.75 and above |
| **Fair** | 2.0 and above |
| **Developing** | below 2.0 |

The exact score, every piece of evidence and the confidence are one tap away.

---

## 4. Category modules (D6), built on standards that already exist

We don't reinvent standards. Each module adapts an established one, and **leaves out anything about belief**.

| Category | Built on | D6 checks | Explicitly *not* scored |
|---|---|---|---|
| **News & journalism** | Journalism Trust Initiative (CEN CWA 17493) · Trust Project indicators [E43](EVIDENCE.md#E43) | ownership and funding disclosed · corrections policy that is followed in practice · news, opinion and sponsored content labelled · named authors and sourcing · published ethics policy | political lean, editorial positions |
| **Nonprofits** | Charity Navigator Accountability & Finance · Candid transparency [E43](EVIDENCE.md#E43) | financial filings public · independent board · program results reported · donor privacy · fundraising cost disclosed | cause or ideology |
| **Faith organizations** | ECFA standards for financial accountability, plus safeguarding [E43](EVIDENCE.md#E43) | independent board oversight · audited or reviewed finances · honest fundraising · safeguarding (background checks, two-adult rule) · members free to give or leave without pressure | doctrine, theology, worship, membership requirements |
| **Businesses** | B Lab B Impact Assessment areas [E43](EVIDENCE.md#E43) | fair treatment of workers · honest pricing and returns · customer data practices · community impact | size, industry (beyond the gates) |
| **Apps & digital services** | Consumer Reports Digital Standard · Mozilla *Privacy Not Included* [E43](EVIDENCE.md#E43) · the [Flocial self-assessment](FRAMEWORK.md#self-assessment-checklist-for-the-aligned-tier) | security, privacy, respect for wellbeing · **Flocial Verified status** | |

**Where adopting the Manifesto counts.** A provider that is **Flocial Verified** (independently scored
against the Framework):
- earns up to the full 4 on D6 for apps, or a +0.5 bonus on D5 for other categories
- gets the Flocial Verified badge

A pledge alone (the **Aligned** tier) earns the "self-reported" treatment above and no more. This is how
adopters rank higher **because their conduct is verified** [E42](EVIDENCE.md#E42).

---

## 5. Ranking, equitably

When someone browses or an AI assistant suggests a provider, the order works as follows.

1. **Eligible.** Only providers that pass every gate *and* that the community's organizers haven't removed.
2. **Relevant.** It matches what the person asked for.
3. **Fit.** A 0–1 private fit score from the community's [Community Charter](COMMUNITY-CHARTER.md), with reasons.
4. **Combined.** `0.5 × conduct (scaled 0–1) + 0.5 × fit`.
   - The community can move this balance anywhere from "conduct only" to "fit first".
   - **Fees, bids and commissions never enter this number.**
5. **Fair exposure.** Providers within **0.05** of each other count as tied. Tied providers **rotate** across
   views, so tiny score differences don't produce winner-take-all exposure [E39](EVIDENCE.md#E39).
6. **Tie-breaks.** Within a tie: run by members, then local, then small or independent providers first.
7. **Organizer picks.**
   - Organizers can pin ("backed") or remove any provider.
   - Pins are labelled "chosen by your community".
   - Removals stay private to the community.
8. **Give-back offers.**
   - Providers can offer the community's pool a larger share back.
   - Offers are **shown openly next to the provider**. They never change its rank.
   - A community can choose to sort by give-back if it wants to.

**Balance option** (from [E24](EVIDENCE.md#E24)): a community can ask to also see a highly rated provider that
*doesn't* match its charter on a topic such as news or opinion, labelled "a well-rated voice from another
perspective".

---

## 6. Who scores, and how money stays out

- **A seal names what it covers.** Verification is for a named product or feature, never a whole company: a
  seal reads, for example, *"Flocial Verified: customer community"*, and may only be shown with that product.
- **Independent steward.** The standard is owned and run by a body separate from any scored network
  [E40](EVIDENCE.md#E40). See the movement kit.
  - **Interim:** until it exists, the team that drafted this manifesto runs the scoring. Every score page
    says who scored it and any money that team earns from the providers it scores, and that an independent
    steward will take this over.
    [E41](EVIDENCE.md#E41)
- **Humans decide, and AI assists.**
  - AI may collect public evidence and draft scores, and the drafts are labelled.
  - A trained human reviewer confirms every gate decision and every score.
  - Providers see their full scoring file.
- **Appeals.**
  - Providers can appeal within 30 days.
  - A second reviewer, who didn't score the original, decides.
  - Outcomes are published.
- **Re-scoring.** Every year, and whenever something significant happens (an enforcement action, an acquisition, a
  report of serious harm).
- **No pay-to-score.**
  - Verification fees, if any, are flat, recover costs only, and are waived for nonprofits, congregations and
    small businesses.
  - Fees never depend on the outcome. A paying provider and a free one get the same review.
- **Free listings.**
  - Nonprofits, congregations, public-interest news and small independent businesses are listed free.
  - The rubric applies identically to free and paid listings.
- **Open versions.**
  - The rubric is versioned in public.
  - Changes go through 30 days of public comment.
  - Every score names the rubric version it used.

## 7. Guarding against gaming
- **Self-attestation is capped** until it's verified.
- **Rotation of near-ties** removes the incentive to chase tiny score gains.
- **Random audits** of providers that score Strong or above.
- **Permanent removal** for fabricated evidence.
- **Published dashboards** showing rank against fees paid, so anyone can check that the correlation is
  about zero.

---

### Open questions for v0.2
1. Weights: should D3 (safety and children) count double for providers that serve children?
2. How should international organizations be scored where the standards above don't apply?
3. What is the minimum evidence needed for very small providers, like a cousin's bakery, without
   burdening them?
4. Should communities be able to add their own D7 dimension, kept private to them?
