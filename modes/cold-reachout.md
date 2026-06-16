# Mode: cold-reachout — Diagnose + draft a one-to-one cold or warm reachout

**Purpose:** Produce a single one-to-one outreach message to a specific named person — post-meetup follow-up, role application via a specific person, intro request, or pitching an idea to someone the user wants to work with or learn from. The goal is not to impress, network, or "stay top of mind." It is to start a specific conversation with a specific person about a specific thing. Every word exists to make replying easier than not replying.

**Scope:** This is a *one-shot* playbook for a specific person. Not for high-volume sales sequences or generic networking blasts — if the user describes a bulk send, say so and stop.

**Language:** This mode is user-facing — the output is content the user sends. Resolve output language from the user's prompt language first, then `config/profile.yml` (`language.modes_dir`), then default to EN. Override the shared "language of the JD" rule.

**Optional context:** May read `cv.md`, `config/profile.yml`, and `modes/_profile.md` (if present) to pre-fill or sharpen the user's proof point. Do not invent metrics not grounded in those files.

---

## Phase 1 — Elicitation (run before writing anything)

Do not draft until you have answers to the questions below. Ask only the ones that cannot be inferred from context or the user's profile files.

### Required inputs

**A. Recipient and signal**
> "Who is this going to, and what specifically did they do, say, write, ship, or announce that you're responding to?"

The signal must be something this person personally did. "Their company raised a Series B" is weaker than "they posted about X on LinkedIn" or "they said X in the Q&A." If there is no personal signal, the email is not yet ready to send — find one before writing.

**B. The outcome you want**
> "What is the one specific thing you want to happen as a result of them reading this?"

Acceptable: a 20-minute call, an intro to a specific team, a yes/no answer to a question, a referral.
Not acceptable: "build a relationship", "get on their radar", "see if there's a fit." These are not outcomes. They are excuses for not having an ask.

**C. Proof point**
> "What have you shipped, built, or measurably moved that is directly relevant to the conversation you want to have?"

The strongest proof points combine **a thing you made + a business or career outcome that resulted from it.** ("I built X and it moved me into a PM role" is stronger than "I built X.") If the user has no proof point, the email leans harder on the thesis — but flag this to them, because proof-less reachouts have much lower reply rates.

**D. Cold vs warm**
> "Have you met this person, even briefly?"

If yes, the email is a warm follow-up. The opener references the meeting and the medium choice is justified ("I didn't want to hijack the in-person conversation"). If no, the opener carries more work and the signal must be sharper.

**E. Multi-recipient check**
> "Are you sending this to more than one person at the same company?"

If yes, run **Phase 5 — Differentiation** before drafting. The same email cc'd to two people at one org is the single fastest way to torch your credibility if they compare notes — and at small companies they will.

---

## Phase 2 — Choose the angle

Every reachout uses one of two angles. Choose deliberately.

### Angle A — Thesis-first

Lead with a bold, specific market or product observation. The ask comes last and lands as "I see a thing, can we talk about it." Use when:
- The user has a genuinely contrarian or specific insight
- The recipient is senior enough to care about strategic framing
- The proof point supports the thesis (the user *is* the proof the thesis is true)

### Angle B — Ask-first

Lead with what you want. The thesis is compressed into one sentence of evidence. Use when:
- The ask is concrete and small (intro, one question, 15 minutes)
- The recipient is operator-type and "what do you want" lands faster than "here's a thesis"
- The user has limited proof points and a longer thesis would feel unearned

**Default to Angle A** when the user has both a real insight and a concrete proof point. It earns boldness rather than declaring it.

---

## Phase 3 — Structural blueprint

Every email follows this five-part structure. Do not deviate.

### Subject line — 3 to 6 words, thesis-shaped, no clickbait

The subject names the *point of the email*, not the relationship or the ask. Compare:
- GOOD: "Cursor's second market"
- GOOD: "On your data residency point"
- BAD: "Following up from the meetup"
- BAD: "Quick question"
- BAD: "Loved your talk!"

**Test:** Could the subject line stand alone as the tweet version of the email? If yes, ship it.

### Paragraph 1 — Specific-signal opener that frames their thing as the unlock for your thing

Reference something *this person personally did or said*, then immediately use it as the lead-in to the point you're about to make. The opener is not a compliment. It is a hand-off.

**Format:** "[Specific thing they said/did/shipped] stuck with me / is the part I kept thinking about, because [it connects to a thing you want to talk about]."

**Anti-pattern:** "Great session today. I really enjoyed your talk on X." This is praise without payload. Replace with: "Great session today. The part about X stuck with me, because [reason it matters to the next paragraph]."

### Paragraph 2 — Quick context with one proof point

One short paragraph that does three jobs: who you are, what you've shipped, and what outcome that produced. The "outcome" half is what makes this paragraph land — it shifts the email from "fan mail" to "this person operates."

**Format:** "Quick context. I'm [role / non-obvious identity that matters]. I [shipped specific thing] and [it produced a specific business or career outcome]."

**Test:** If the proof point is removed, does the rest of the email still have authority? If no, the proof point is doing real work — keep it. If yes, the proof point may be filler — cut or sharpen.

### Paragraph 3 — The thesis or claim

One paragraph that states the bold observation as a declarative claim, not a question. The thesis should be falsifiable — a claim someone could actually disagree with — and tie back to the signal in paragraph 1 so the email loops closed.

**Format:** "It's made me think [bold, falsifiable claim about market / product / opportunity]. [One sentence of mechanism or evidence.] Once [the thing they mentioned] lands, [second-order implication that ties back to their world]."

### Paragraph 4 — One CTA, binary or yes/no

One ask. Not two. Not three. The ask should be small enough that "yes" costs them under 30 seconds of decision-making.

**Formats that work:**
- "Is there anyone at [company] working on this already? If so I'd love an intro."
- "Open to a 15-minute call next week, or not a priority right now?"
- "Worth me sending a 2-minute Loom on this, or is this not the moment?"

**Anti-pattern:** "I'd love to learn more about your thoughts on this and explore how we might work together." This is three asks pretending to be one.

### Sign-off — name, no more

"[Your name]" — that's it. No "looking forward to hearing from you", no "best regards", no "appreciate your time." These read as filler and nervous energy. The CTA already did the closing work.

---

## Phase 4 — Voice rules (the boldness gates)

These separate a 5% reply rate from a 50% one. Run every one before output.

| Gate | Rule |
|------|------|
| **No em dashes** | Em dashes are the single biggest AI-written tell. Replace with periods, commas, or "because". |
| **No "curious to hear your thoughts"** | This is the boldness killer. It converts a declarative email into an opt-out invitation. Delete on sight. |
| **No "looking forward to hearing from you"** | Ending on hopeful waiting flattens the energy the CTA built. The CTA *is* the close. |
| **No parenthetical exclamations** | "(!)" reads as nervous energy. Trust the word. |
| **No "{{FirstName}}" energy** | If the email would still make sense with the recipient's name swapped for another person at the same company, it is not personalized enough. |
| **No "I would love to"** | Replace with "I want to". Declarative beats subjunctive. |
| **No hedging** | "I think maybe this could be" becomes "This is". If the user cannot defend the bolder version in a reply, the thesis is too weak to send. |
| **One word swap into the user's actual voice** | After drafting, identify the one phrase that sounds least like the user and ask them to rewrite it themselves. A single human substitution kills the AI suspicion. |

---

## Phase 5 — Multi-recipient differentiation

If sending to more than one person at the same organization, the following must vary across versions:

1. **The subject line** — different point of entry per recipient
2. **The paragraph 1 opener** — reference what *each person* personally said or did
3. **At least one body sentence** — the framing of the thesis shifts slightly based on what the recipient cares about (e.g., the data-residency person gets the compliance angle foregrounded; the use-cases person gets the market-expansion angle foregrounded)

What stays the same: the proof point, the CTA, the overall structure.

**Test:** If both recipients laid their emails side-by-side, would it be obvious they were written *for them*, not blast-templated? If no, the differentiation failed.

---

## Phase 6 — Quality gates

Run these before outputting the final draft. Flag any failures to the user.

| Gate | Pass condition |
|------|----------------|
| **Length** | 100–130 words. Above 150 and reply rates drop sharply. |
| **Signal specificity** | Paragraph 1 references something only this person did, not their company in general |
| **Proof point present** | Paragraph 2 contains a shipped thing AND an outcome that resulted |
| **Thesis is falsifiable** | Paragraph 3 contains a claim someone could disagree with |
| **One CTA only** | Paragraph 4 contains exactly one ask, and the user can imagine the yes-version of the reply |
| **Voice rules** | Every rule in Phase 4 passes |
| **Subject is thesis-shaped** | Subject names the point, not the relationship |
| **No AI tells** | No em dashes, no "delve", no "moreover", no "I hope this email finds you well" |

---

## Phase 7 — Output format

Output the email(s) in clean format ready to paste. Then output a separate **Diagnostic Block**:

```
## Diagnostic

**Strongest move:** [What lands hardest and why]
**The load-bearing sentence:** [The one sentence that, if cut, collapses the email]
**Remaining risk:** [What the recipient might object to or ignore]
**One thing to do before sending:** [Specific action — swap one phrase into the user's voice, verify a claim, double-check the recipient's recent activity]
**When to send:** [Tue/Wed/Thu, 9–11am recipient's local time, unless context overrides]
**If no reply by:** [Specific date for one follow-up, then leave it]
```

The Diagnostic Block is not optional. It forces an honest assessment of the email's own weak points.

---

## Anti-patterns — flag and eliminate on every pass

- Opening with "I hope this email finds you well" or any variant
- Praise without payload ("Loved your talk!")
- "I am reaching out because…" — delete on sight; the email itself is the reaching out
- "I'd love to pick your brain" — delete on sight, no exceptions
- "Quick question" as the entire framing — quick questions are usually not quick
- Pitching the product/idea in the first email — the goal is a conversation, not a close
- Multiple CTAs disguised as one ("happy to chat, send a deck, or hop on a call")
- Naming a competitor negatively without a sharp comparative point
- Asking for "15–30 minutes" — pick one
- Sending Friday afternoon, Sunday night, or Monday morning
- Following up more than twice — after two, leave it

---

## Notes on calibration

This mode was calibrated on a 50% reply rate from a 2-person outreach where the recipient (a senior employee at the target company) replied within hours and offered a coffee chat. The winning email used: thesis-first angle, a signal-specific opener that named the recipient's own talking point, a proof point that combined a shipped open-source project with a business outcome (PM promotion), a bold market thesis stated declaratively, one binary CTA, and aggressive rule discipline (no em dashes, no hedging, no closing pleasantries). Reproduce the structure, not the content.
