# The Flocial Framework

**Draft v0.1 · October 2026 · CC BY-SA 4.0**

This document is for people who build things. The [Manifesto](MANIFESTO.md) says *what* a flocial network
commits to. This framework says *how*.

Each of the 22 principles is broken into:
- **Why:** the evidence, linked to the [Evidence Ledger](EVIDENCE.md)
- **Do:** patterns that keep the principle
- **Don't:** anti-patterns that break it
- **Measure:** how you'd know you're keeping it
- **Example:** what keeping it can look like in practice

A self-assessment checklist at the end gives each principle one yes-or-no question. Builders who want the
**Aligned** tier publish their answers.

**Measures are about flourishing and safety, never attention held.**
- If a measure would reward keeping people in the app longer, it's the wrong measure.
- Measure in aggregate, and privately.
- Never collect more data to measure flourishing than the flourishing is worth.

---

## I. Time: give attention back

### 1. Every feed ends
- **Why:**
  - Infinite scroll and autoplay were among the features a jury found negligently designed
    [E01](EVIDENCE.md#E01).
  - The settlement adds scrolling prompts and an autoplay off-switch [E05](EVIDENCE.md#E05).
- **Do:**
  - Paginate by a natural unit (since your last visit, this week).
  - Finish with a clear end state that sends the person back to their day.
  - Make autoplay off by default.
  - Make "load more" a deliberate choice that is never triggered automatically.
- **Don't:**
  - infinite scroll
  - autoplay of the next item
  - "you might also like" after the end
  - pull-to-refresh tuned like a slot machine (variable rewards)
- **Measure:**
  - Share of sessions that reach the end state.
  - Median session length should be stable or falling as satisfaction rises.
- **Example:** Open it and you see what’s new since you last looked, eleven posts from the people you follow. After the eleventh, that’s everything, so you can put the phone down without wondering what you missed.
- **In other settings:** Public forums and work channels end too. Show what’s new since the last visit, then stop.

### 2. Quiet by default
- **Why:**
  - Push notifications engineered to pull users back were part of the K.G.M. case
    [E01](EVIDENCE.md#E01).
  - Courts and the settlement now impose notification curfews [E04](EVIDENCE.md#E04)
    [E05](EVIDENCE.md#E05).
- **Do:**
  - Turn alerts on only for what people would want to be interrupted for, such as direct messages and group
    announcements.
  - Batch everything else into digests.
  - Use quiet hours by default.
  - Say who and where, never the content.
  - Unsubscribe in one tap.
- **Don't:**
  - "someone liked your post" pings
  - re-engagement notifications ("you haven't posted in a while")
  - red badges counting non-urgent items
  - content previews in alerts
  - streaks
- **Measure:**
  - Notifications per active person per week, which should go down over time.
  - Share of notifications people act on.
  - Opt-out rate.
- **Example:** Alert emails never include message text, and each post is sent at most once. Unread messages get at most one summary, after a wait. Posting alerts are off until people turn them on, every email has one-click unsubscribe, and quiet hours hold overnight.
- **In other settings:** In a workplace, quiet hours respect time off [E54](EVIDENCE.md#E54), and fewer interruptions mean less stress [E53](EVIDENCE.md#E53). In a chat added to another site, alerts still say who, and leave the what for later.

### 3. Order by time or by the people you choose, never by what holds attention
- **Why:**
  - Facebook weighted emoji reactions at five likes to keep people engaged. Internally, posts drawing
    angry reactions were linked to misinformation and toxicity [E10](EVIDENCE.md#E10).
  - Algorithmic recommendations were at issue in K.G.M. [E01](EVIDENCE.md#E01).
- **Do:**
  - Default to newest first.
  - If you must rank, rank by people's stated preferences [E26](EVIDENCE.md#E26) or by agreement across
    groups that usually disagree [E23](EVIDENCE.md#E23) [E24](EVIDENCE.md#E24).
  - Explain any ranking in plain words, and let people turn it off.
- **Don't:**
  - optimize for clicks, comments, watch time or "meaningful interactions" defined as reactions
  - inject content from outside the person's chosen circle
- **Measure:** whether people can explain why they see what they see (a survey), and the share using a feed in
  chosen order.
- **Example:** Newest first, and every post gets the same chance to be seen.
- **In other settings:** For a civic consultation, rank by agreement across divides [E55](EVIDENCE.md#E55). For a customer community, rank by what members say helped.

## II. Closeness: close ties come first

### 4. Closeness over audience
- **Why:**
  - Well-being rises with composed messages from close ties, more than with likes or broadcast browsing
    [E21](EVIDENCE.md#E21).
  - Social comparison was among the effects reported in Meta's own studies [E08](EVIDENCE.md#E08)
    [E09](EVIDENCE.md#E09).
  - Inner circles are small whatever the platform [E31](EVIDENCE.md#E31).
- **Do:**
  - Use invite-only spaces.
  - Make reactions private between the two people involved.
  - Make composing a message the easiest action.
  - Use small group threads.
- **Don't:**
  - follower counts
  - public like counts
  - "most popular" lists
  - beauty filters
  - public view counts
- **Measure:**
  - Share of activity that is composed messages versus one-tap reactions.
  - The number of people with at least one meaningful exchange per week.
- **Example:** Each post goes to the group it was meant for. There are no follower counts and no public tallies of likes.
- **In other settings:** An open community can let anyone read, but reach still isn’t scored and popularity isn’t public.

### 5. People introduce people
- **Why:**
  - New Mexico's jury found Meta concealed what it knew about child sexual exploitation on its platforms
    [E03](EVIDENCE.md#E03).
  - The settlement restricts discovery by suspicious adults [E05](EVIDENCE.md#E05).
- **Do:**
  - Grow membership only through a member who knows the person, in that member's own words.
  - Make "don't ask again" permanent.
  - Never match people across separate communities.
- **Don't:**
  - "people you may know"
  - contact-list upload for matching
  - messages from strangers
  - public search of people
- **Measure:**
  - Unsolicited contact attempts, which should be zero by design.
  - Share of invitations sent by someone who knows the person.
- **Example:** You decide who can message you. Someone new joins a group when a member introduces them, in their own words, and “No thanks” is final.
- **In other settings:** In public spaces, strangers may reply in the open, but private messages still need an invitation.

### 6. Pause before sending, and disagree in private
- **Why:** a prompt before posting cut offensive tweets by 6%, and the effect persisted
  [E22](EVIDENCE.md#E22).
- **Do:**
  - Detect heated language as the person writes, on the device if possible.
  - Offer a calmer rewrite, and leave the final word with the sender.
  - Give conflict a private place with structure. Everyone writes before anyone reads, anyone can pause, and
    agreements are small and specific.
  - Route abuse to real help, never to "mediation".
- **Don't:**
  - quote-posting someone you know to an audience
  - public pile-ons
  - silent removal without explanation
  - an AI that judges who is right
- **Measure:**
  - Share of prompted messages that were revised.
  - Disputes resolved, as reported by the people involved.
- **Example:** Before a reply sends, there’s a moment to reread it. Disagreements stay between the people involved, and everyone has their say before anyone answers. Abuse goes to real help, never to mediation.
- **In other settings:** Customer and civic communities move a heated thread into a smaller, calmer conversation.

### 7. Success is measured off-screen
- **Why:**
  - Close relationships predict survival and later-life wellbeing [E29](EVIDENCE.md#E29)
    [E30](EVIDENCE.md#E30).
  - Close relationships are one of the six domains of flourishing [E28](EVIDENCE.md#E28).
- **Do:**
  - Build features whose success is something that happens offline, like a call or a shared meal.
  - Make "go do the thing" the end of the flow.
- **Don't:** count time in the app as success, or reward daily streaks.
- **Measure:**
  - Gatherings organized.
  - People who joined in person.
  - Self-reported closeness, on a short validated scale, surveyed occasionally and privately.
- **Example:** The proudest moment is a nudge to put the phone down and meet up, with simple tools that turn a plan into a tee time or a book club night.
- **In other settings:** Count meetups held, questions resolved and neighbours who met.

## III. Dignity and safety: protect people without surveilling them

**Built for every age.** Every principle in this pillar applies to people of every age and confidence online:
- **Do:** readable type and simple steps. Help from someone you trust comes through delegated access that is
  logged, limited and revocable, never a shared password. Add extra checks before money moves or a new contact is
  trusted.
- **Don't:** make the safest choice the hardest one to find, or treat older adults as an afterthought.
- **Why:** older adults lose more to online fraud than any other age group [E49](EVIDENCE.md#E49).

**When the host has power.** Where the host has power over its members (an employer, a school, a government):
- **Do:** keep private messages and notes out of the host's reach, and publish what the host can and can't see.
  Make some organizers members chosen by members, with a say in the rules and in how they're enforced
  [E51](EVIDENCE.md#E51).
- **Don't:** use the community to monitor members' activity, sentiment or productivity.
- **Why:** monitored workers report more stress and poorer mental health [E52](EVIDENCE.md#E52).

### 8. Smallest circle by default, with consent you can see and take back
- **Why:**
  - Privacy is information staying in the context where it was shared [E32](EVIDENCE.md#E32).
  - Defaults set to the highest privacy are now law for children in places [E19](EVIDENCE.md#E19)
    [E20](EVIDENCE.md#E20).
- **Do:**
  - Give every category of data its own audience setting.
  - Start sensitive categories at "only me" or the closest circle. That covers health, money, travel, location and
    anything about a child.
  - Log every widening of an audience, and make every widening revocable.
  - Make audience limits hold everywhere a post can travel, from search and alerts to exports and staff tools.
- **Don't:**
  - "public" as a default
  - re-sharing that crosses an audience boundary
  - data-sharing "partners"
- **Measure:** the share of sensitive items that ever leave their default circle, and how long a revocation
  takes to apply.
- **Example:** Who can see a post holds everywhere it travels and is checked regularly. Photos follow their post’s audience, and “only me” stays private even from admins. Sensitive categories (health, money, travel, children) each have their own setting and start in the smallest circle, and every widening is recorded.
- **In other settings:** At work, private notes stay private from managers. In a civic forum, personal details stay with the person.

### 9. People name people
- **Why:** turning biometric identification on by default violates contextual integrity
  [E32](EVIDENCE.md#E32). Children's codes forbid nudging children to weaken their privacy
  [E20](EVIDENCE.md#E20).
- **Do:**
  - Only people identify people.
  - Any face recognition is opt-in for oneself, never for children, never matched across communities, and
    never used for training.
  - Tags never widen who can see something.
  - Anyone can remove a tag of themselves, and nobody is notified.
- **Don't:**
  - automatic face tagging
  - "is this you?" prompts that are really consent-farming
- **Measure:** tags removed by the person tagged, and whether any of them were reported.
- **Example:** “People in your community name people.” A tag keeps a photo with the same audience, and anyone can quietly take themselves out of one.
- **In other settings:** Staff directories and event photos follow the same rule, so people are identified only when they say yes.

### 10. Safety includes safety from the people closest to you
- **Why:** most technology-enabled abuse uses ordinary features, by an "adversary" who is a legitimate,
  logged-in member [E18](EVIDENCE.md#E18).
- **Do:**
  - Let people block someone close without that person being notified.
  - Let people hide from the tree or from particular branches.
  - Offer quiet exits.
  - Never use live location.
  - Show a safety check before sensitive information is shared with a household member.
  - Provide routes to real help.
  - Design for estrangement, divorce and custody situations.
- **Don't:**
  - "X has left the group" announcements
  - readable last-seen or read-receipt data
  - location history
- **Measure:** whether the safety tools are used (aggregate only), and whether people can find them in testing.
- **Example:** Quiet removal from photos, blocking anyone without them being told, routes to crisis lines, and location that is off by default and never live.
- **In other settings:** Workplaces and clubs need quiet blocking too, and a route to help outside the group.

### 11. AI serves human connection and never stands in for it
- **Why:**
  - Settlements and lawsuits over chatbot "companions" and teen suicides [E15](EVIDENCE.md#E15)
    [E16](EVIDENCE.md#E16).
  - Research on AI simulations of the dead [E35](EVIDENCE.md#E35).
- **Do:**
  - The AI only sees what the user can see.
  - It drafts, and the person sends.
  - It recommends only when asked, and discloses any commercial interest.
  - It says plainly that it is an AI.
  - It sends people in crisis to humans.
- **Don't:**
  - AI personas that pose as friends
  - romantic or companion modes for minors
  - synthetic voices of real people, living or dead, without their consent
  - "griefbots" of anyone who didn't consent while alive
  - AI that sends messages on someone's behalf
- **Measure:** share of AI drafts a person edited before sending, and actions the AI took without a tap, which
  should be zero.
- **Example:** An AI assistant drafts, and posts, sends or shares only when you tap. It says it’s a machine, and it recommends things only when asked.
- **In other settings:** Support bots and assistants say they are machines, and hand over to a person when asked.

## IV. Children: protected by design, growing into their own story

### 12. Protection built in, without surveillance
- **Why:**
  - The settlement floor [E05](EVIDENCE.md#E05).
  - Design codes [E19](EVIDENCE.md#E19) [E20](EVIDENCE.md#E20).
  - EFF's warning about surveillance-based protection [E06](EVIDENCE.md#E06).
- **Do:**
  - Use the safest defaults.
  - Have no stranger contact by design, which removes most of the need to monitor.
  - Let guardians see *who* a child talks to, and leave *what* was said to the child.
  - Check age in the least invasive way, and inside a trusted community wherever possible.
- **Don't:**
  - giving parents message content by default
  - mass ID collection
  - advertising to children
- **Measure:** unsolicited adult contact with minors, which should be zero, and whether children understand
  their settings.
- **Example:** Guardians see who a child talks to, and the conversation stays the child’s. A child’s location stays private, and children see no offers.
- **In other settings:** Schools, teams and youth programmes start every child at the safest settings.

### 13. Children grow into their own story
- **Why:** sharenting [E33](EVIDENCE.md#E33), and children's rights to take part [E34](EVIDENCE.md#E34).
- **Do:**
  - Run a "coming of age" review. At 13, 16 and 18, the young person can see and contest what was posted
    about them.
  - Hand the profile over to them.
  - Let a child veto public photos of themselves.
- **Don't:** keep a permanent public archive of a childhood.
- **Measure:** completed reviews, and items the young person withdrew.
- **Example:** At 18, a young person sees everything posted about them by family, school or team, and decides what stays.
- **In other settings:** Schools and teams let former students review and remove what was posted about them.

## V. Fairness: shared value

### 14. The people are the customer
- **Why:** engagement-weighted ranking exists because attention is what gets sold [E10](EVIDENCE.md#E10).
- **Do:**
  - Choose a way of funding the community that serves its members, and say plainly what it is.
  - Make every cost visible before anyone commits to it.
  - Disclose what you earn on every commercial card.
  - Make sure no one who is invited is priced out.
- **Don't:**
  - attention-based advertising
  - selling or "partnering" data, even with consent
- **Measure:** revenue share from attention, which should be 0%, and whether the pricing pages are honest
  (user testing).
- **Example:** Prices are plain and up front. Every listing says what the community earns from it, and anyone who’s invited can take part fully, whatever they can pay.
- **In other settings:** For a business’s community, the members are still the customer. Costs are visible, and their attention is never the product.

### 15. The community shares in the value it creates
- **Why:**
  - Platform cooperativism [E36](EVIDENCE.md#E36).
  - Marketing on people's stated intentions [E38](EVIDENCE.md#E38).
- **Do:**
  - Share a published portion of what the community earns, in money or in kind, and let members decide together how it is used.
  - Make businesses run by members easy to find.
  - Explore group buying power.
  - Only show aggregates, so no one is singled out.
- **Don't:**
  - commissions paid to individuals (it turns members into salespeople for each other)
  - paying people for their data or attention
  - behavioral targeting
- **Measure:** money returned to communities, and the share of commerce with members' own businesses.
- **Example:** A share of what the community earns comes back to it, and members decide together how it’s used. Businesses run by members are easy to find. Counts under three show as “a few members”.
- **In other settings:** Where there’s no commerce, the value shared is a real say in decisions and the benefits the community creates.

### 16. Leaving is as easy as joining
- **Why:**
  - FTC v. Amazon [E17](EVIDENCE.md#E17).
  - Data portability [E37](EVIDENCE.md#E37).
- **Do:**
  - Cancel in the same number of steps it took to sign up.
  - Let people take everything with them, ready to use elsewhere.
  - Keep data available after a person stops paying.
  - Let a community split its space.
- **Don't:**
  - steps that try to talk people out of leaving
  - export formats nobody else can read
  - deleting data when someone stops paying
- **Measure:** steps to cancel compared with steps to join, and how complete the export is.
- **Example:** Your posts and history stay yours, whatever you pay. Leaving takes one step, and everything comes with you, ready to use elsewhere.
- **In other settings:** Workplaces let people keep their own contributions where they can, and public forums let anyone leave with their posts.

### 17. Promises outlive the company
- **Why:**
  - Steward ownership and golden-share structures [E44](EVIDENCE.md#E44).
  - The pattern of mission drift after acquisition.
- **Do:**
  - Write user rights into terms that survive a change of control.
  - Choose a legal structure that protects the mission (benefit corporation, steward ownership, golden
    share).
  - Publish a shutdown plan with guaranteed export and notice.
- **Don't:** treat "lock-in" as a moat.
- **Measure:** published, binding commitments.
- **Example:** A legal structure that locks in the mission, user rights written to survive a sale, and a published plan for shutting down.
- **In other settings:** Businesses and public bodies publish what happens to the community if the service ends.

## VI. Open doors: the outside world, on the community's terms

### 18. Each community writes its charter
- **Why:** intent-based terms that individuals put forward [E38](EVIDENCE.md#E38), and prosocial communities
  defined by shared values [E24](EVIDENCE.md#E24).
- **Do:**
  - Give each community a Community Charter that people and an AI assistant can read
    ([template](COMMUNITY-CHARTER.md)).
  - Keep it private.
  - Have organizers adopt it with the community's input.
  - Let any member see it.
- **Don't:** use the charter to target ads, or share it with providers.
- **Measure:** charters adopted, and fit explanations people found useful.
- **Example:** A one-page charter covers who the community is for, how members treat each other, what it won’t accept and who can change it. Anything new suggested to the community is held up against it.
- **In other settings:** Workplaces, clubs and public forums post their charter’s norms where every member can see them. Visible rules raise newcomers’ participation [E50](EVIDENCE.md#E50).

### 19. Outside voices come in by invitation
- **Why:**
  - Viewpoint-neutral design rules [E26](EVIDENCE.md#E26).
  - Existing conduct standards [E43](EVIDENCE.md#E43).
- **Do:**
  - Treat news organizations, congregations, nonprofits and businesses as guests the community adds.
  - Every guest can be muted or removed by organizers.
  - Rate conduct with the [Rubric](RUBRIC.md), and leave fit with beliefs to the community.
  - Offer a "balance" option that shows a well-rated voice from another perspective
    [E24](EVIDENCE.md#E24).
- **Don't:**
  - platform-chosen "trending" outside content
  - rating organizations on their beliefs
  - outside voices that reach in without being invited
- **Measure:** muted or removed guests, and members' sense that they understand why something appears.
- **Example:** The community’s organizers choose which outside organizations appear, and can swap or remove any of them at any time.
- **In other settings:** A chat added to a business’s site brings in no third parties the community didn’t choose.

### 20. Standing is earned by conduct
- **Why:**
  - Ethics-washing [E42](EVIDENCE.md#E42).
  - The FTC rule that paid relationships must be disclosed [E41](EVIDENCE.md#E41).
  - Fair exposure [E39](EVIDENCE.md#E39).
- **Do:**
  - Check gates first, then grades.
  - Publish the evidence behind every score, and offer appeals.
  - Rotate visibility among providers whose scores are close.
  - Keep fees and scoring strictly apart.
  - Let providers compete only on what they give back.
- **Don't:**
  - pay-to-rank
  - badges that are bought rather than earned by verified conduct
  - undisclosed affiliate relationships
- **Measure:** rank correlation between fees paid and position, which should be about zero, and how fast
  appeals are resolved.
- **Example:** Only providers that pass the gates can make an offer. Offers are shown openly, the community’s organizers choose, and rubric order is never affected.
- **In other settings:** In customer communities, the best answer rises on its merits, and members helping each other is what makes them work [E56](EVIDENCE.md#E56).

## VII. Honesty: tell the truth, including about yourself

### 21. Publish what you learn, harms included
- **Why:** Project Mercury [E08](EVIDENCE.md#E08), and the teen girls slide [E09](EVIDENCE.md#E09).
- **Do:**
  - Register your wellbeing studies before running them.
  - Publish the results either way.
  - Publish a yearly **Flocial Report** with flourishing measures [E28](EVIDENCE.md#E28), safety incidents
    and fixes.
- **Don't:** shelve research that's inconvenient, or publish only the flattering numbers.
- **Measure:** studies registered compared with studies published.
- **Example:** A yearly Flocial Report shows what was measured, and what changed when something went wrong.
- **In other settings:** Businesses and public bodies publish their Flocial Report alongside their annual report.

### 22. Let others check
- **Why:**
  - The settlement requires independent research and audits [E05](EVIDENCE.md#E05).
  - Certifiers must stay independent of what they certify [E40](EVIDENCE.md#E40).
- **Do:**
  - Give researchers access under privacy protections.
  - Accept outside audits.
  - Protect employees who raise concerns.
  - Separate the body that keeps the standard from any network scored by it.
- **Don't:**
  - grade yourself
  - non-disparagement clauses that silence safety concerns
- **Measure:** completed audits, and researcher projects.
- **Example:** An independent steward scores how it’s run, on the open rubric, in public, and researchers get safe access to study it.
- **In other settings:** Any organization hosting a community can invite independent review of how it’s run.

---

## Self-assessment checklist (for the "Aligned" tier)

Answer each question **Yes / Partly / No**, link evidence, and publish the result, gaps included.

| # | Question |
|---|---|
| 1 | Does every feed have an end state, with no infinite scroll or autoplay by default? |
| 2 | Are notifications off by default except direct messages, kept quiet overnight, and free of content previews? |
| 3 | Is the default order chronological or chosen by the person, with no ranking for attention? |
| 4 | Are follower counts and public reaction counts absent? |
| 5 | Can strangers neither message nor discover members, and does every new member come through someone who knows them? |
| 6 | Is there a prompt before heated messages, and a private, structured place for conflict? |
| 7 | Do your success metrics count offline outcomes rather than time spent in the app? |
| 8 | Do sensitive categories start in the smallest circle, with every widening logged and revocable? |
| 9 | Does no machine identify a person without their own opt-in, and never a child? |
| 10 | Can a member quietly block someone close or hide from them, without that person being notified? |
| 11 | Does the AI act only with a person's tap, never pose as a human, and never simulate anyone without consent? |
| 12 | Are children protected by safe defaults, with no stranger contact and no ads, and without giving guardians message content? |
| 13 | Can young people review and reclaim what was posted about them as they come of age? |
| 14 | Do you say plainly how the community is funded, show every cost up front, and disclose what you earn on every listing? |
| 15 | Does a share of the value the community creates come back to the community as a whole? |
| 16 | Is cancelling as easy as joining, and can people take everything with them, ready to use elsewhere? |
| 17 | Are user rights and the mission locked in so they survive an acquisition, with a published shutdown plan? |
| 18 | Can a community write its own Community Charter, and is it never used to target anyone? |
| 19 | Do outside organizations appear only by invitation, rated on conduct and never on beliefs? |
| 20 | Is ranking independent of fees, with published evidence and an appeals process? |
| 21 | Do you publish your wellbeing research and a yearly report, harms included? |
| 22 | Do you allow independent audits and researcher access, and protect people who speak up? |
