# The Community Charter and the AI fit-check

**Draft v0.1 · October 2026 · CC BY-SA 4.0**

A Community Charter is how a community (a book club, a team, a congregation, a workplace, a street, a
family) says, in its own words, who it's for, how its members treat each other, and what it values. People
read it. An AI assistant, if the community uses one, reads it too ([Manifesto #18](MANIFESTO.md)).

A charter is adopted by the community's **organizers**: the people it trusts to look after it. Each platform
can call that role whatever suits it. Where the host has power over members (an employer, a school, a
government), some organizers should be members chosen by members [E51](EVIDENCE.md#E51).

Post the norms where everyone can see them: when a large community showed its rules to newcomers, their
participation rose by 70% and rule-breaking fell [E50](EVIDENCE.md#E50).

**Four rules that never bend:**
1. **It belongs to the community.** Organizers adopt it with input from members. Every member can read it,
   and any member can add a personal note on top.
2. **It's never used to target anyone.** It shapes what *the community* chooses to see, and it is never a
   profile for advertisers [E38](EVIDENCE.md#E38).
3. **What's private stays private.** A community can post its norms for everyone, but its values and red
   lines are never shown to providers and never sold.
4. **It informs, and people decide.** The AI explains fit, and people choose what comes in.

---

## Part 1: The template (for people)

> **Who we are:** *(our community, in a sentence or two)*
>
> **How we treat each other:** *(the norms every member agrees to)*
> - e.g. *Disagree with ideas, not people.*
> - e.g. *What's shared here stays here, unless the person who shared it says otherwise.*
> - e.g. *Newcomers are welcomed by name.*
>
> **What we care about:** *(up to 7, most important first)*
> 1. e.g. *We look out for each other, especially our oldest and youngest.*
> 2. e.g. *We buy local and support businesses run by our own members.*
> 3. e.g. *We want news that separates reporting from opinion.*
> 4. …
>
> **Lines we don't cross:** *(hard limits, and anything that crosses them is hidden from us)*
> - e.g. *No gambling or alcohol promotions.*
> - e.g. *Nothing aimed at children.*
>
> **What we're looking for right now:** *(optional, temporary)*
> - e.g. *A venue for 80 people in June.*
>
> **Other perspectives:** *(choose one)*
> - ☐ Only show us voices that match our values
> - ☐ Occasionally show us a well-rated voice from another perspective, labelled as such
>
> **Conduct vs fit:** *(slider)*
> Conduct only ◀━━━━━●━━━━━▶ Fit first
>
> **Who can change this charter:** *(organizers / any member / by vote)*
>
> **Adopted:** *(date)* · **Last reviewed:** *(date)*

Communities can start from a blank page or from examples. Example charters are only examples, never defaults.

---

## Part 2: The schema (for AI assistants)

```yaml
flocial_community_charter: "0.1"
community:
  name: "Maple Street Neighbours"
  kind: neighbourhood     # club | team | school | congregation | nonprofit | workplace | business | public_body | neighbourhood | family | other
norms:                    # how members treat each other, which every member may see
  - "Disagree with ideas, not people."
  - "What's shared here stays here, unless the person who shared it says otherwise."
  - "Newcomers are welcomed by name."
values:                   # ordered, most important first, as free text plus optional tags
  - text: "We look out for each other, especially our oldest and youngest."
    tags: [mutual_aid]
    weight: 1.0
  - text: "We buy local and support businesses run by our own members."
    tags: [local, member_owned]
    weight: 0.8
  - text: "We want news that separates reporting from opinion."
    tags: [news_standards]
    weight: 0.7
red_lines:                # hard filters: providers matching any are hidden
  - text: "No gambling or alcohol promotions."
    tags: [gambling, alcohol]
  - text: "Nothing aimed at children."
    tags: [targets_minors]
seeking:                  # optional, expires
  - text: "Venue for the block party, 80 people, June"
    expires: 2027-06-30
perspective_balance: occasional   # off | occasional
conduct_vs_fit: 0.5               # 0 = conduct only, 1 = fit first
governance:
  editors: organizers             # organizers | members | vote
  adopted: 2026-10-03
  reviewed: 2026-10-03
privacy:
  share_with_providers: false     # fixed, and can't be changed
  use_for_targeting: false        # fixed, and can't be changed
```

---

## Part 3: The fit-check (for communities that let outside organizations in)

This part applies only when a community lets outside organizations in: brands, newsrooms, causes, apps or
local businesses. Many communities never will, and their charter is just the first two parts.

### Inputs
- The community's charter, plus the asking member's personal note if they have one.
- The provider's **public** profile and its **published rubric file**: scores, evidence and confidence
  ([Rubric](RUBRIC.md)).
- What the person asked for.

### What the AI produces
1. **A fit band:** *Strong fit · Some fit · Mixed · Poor fit · Not enough information*.
   - Shown in words, with no unexplained number.
   - The 0–1 value behind it is used only for ordering ([Rubric §5](RUBRIC.md#5-ranking-equitably)).
2. **Reasons, each tied to a charter line and a piece of evidence.**
   - e.g. *"Matches 'buy local': independently owned, based in Decatur (source: state business registry)."*
   - e.g. *"Unclear on 'news that separates reporting from opinion': no published corrections policy found."*
3. **Conflicts with the community's red lines, stated plainly.** Providers that cross a red line are hidden.
   If asked, the AI says why.
4. **The provider's conduct band**, as the rubric gives it, never re-scored by the AI.
5. **If balance is on:** at most one clearly labelled suggestion from another perspective, and only providers
   rated Strong or Exemplary qualify.

### What the AI must never do
- **Act on its own.** It never subscribes, buys, follows, joins or contacts a provider without a person's
  tap.
- **Leak the charter.** It never reveals the charter's values or red lines, or a member's personal note, to a
  provider, or uses them to build a profile.
- **Guess beyond the charter.** It never infers sensitive traits (religion, politics, health) beyond what
  the community wrote.
- **Recommend unasked.** It never volunteers recommendations, and answers when asked
  ([Manifesto #11](MANIFESTO.md)).
- **Override the rubric.** It never overrides gates or conduct scores, never upgrades anyone's conduct
  because they fit, and never takes money into account.
- **Pretend to know.** It never hides uncertainty: "not enough information" is a valid answer.

### Audit and accountability
- **Visible fit checks.** Every fit check is logged *within the community*, so organizers can see why
  something was suggested.
- **Disagreement is reported.** Members can flag "this doesn't fit us", and organizers can refine the charter.
- **Only aggregates leave the community.** Aggregate, anonymous counts, like "added by a few communities",
  may be shown to providers. Any count under a minimum threshold (three, say) is shown as "a few".

### Members disagree, and that's fine
A charter is a community's shared ground, and it leaves room for each member's own view. Any member can keep a
**personal note**:
- It adjusts their own fit checks.
- It is visible only to them.
- It can never override the community's red lines where children are concerned.
