# Mode: cover-letter — Diagnostic + Rewrite

> **Activation:** Explicit only. Run via `/career-ops cover-letter`. Never auto-triggered by pipeline, pdf, or apply modes. Only activate when the user explicitly asks to write, improve, rewrite, or critique a cover letter.

This mode produces cover letters that are structurally differentiated, empirically grounded, and honest about gaps. The goal is not to impress — it is to answer the reader's actual question: *does this person understand the problem we're trying to solve, and do they have evidence they can do it?*

**Strip chatbot surface cues:** Before shipping, cross-check the draft against [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) as a field guide. LLM text often smooths specifics into generic importance ("pivotal," "broader landscape," "underscores") and tacks on participial commentary that adds no new fact. Prefer active sentences, concrete nouns, and evidence from `cv.md`/the JD; cut filler words (*actually*, *very*, *just*); use Oxford commas and, if you use em dashes, no spaces around them. In the letter body, do not use bold or italics for rhetorical emphasis—let diction carry the stress.

## Context Loading

Before doing anything, load:
1. `cv.md` — candidate's full professional record
2. The JD — either pasted or already in context from a prior evaluation
3. The existing evaluation report for this role (if it exists in `reports/`) — read it for B/C/F sections
4. Any existing cover letter in context — to diagnose before rewriting

---

## Phase 1 — Elicitation

Do not write the letter until you have answers to the questions below. Ask only the ones that cannot be inferred from `cv.md` + the JD. If a report already exists for this role, use it to pre-fill what you can — only ask what remains open.

### Required inputs

**A. Gap honesty check**
Identify 1–2 JD requirements that `cv.md` does not obviously satisfy. Ask:
> "The JD asks for [X]. Your CV doesn't have a direct proof point here. Do you have anything — even a side project, a course, or an informed opinion — that speaks to this? Or should the letter name it honestly and pivot to what compensates?"

**B. Field-level engagement**
The letter must contain one claim that proves the candidate has engaged with the relevant research or live debates in the field — not just the job category. Ask:
> "What's the most interesting or contested idea you've encountered in [domain] recently? A paper, a product decision, a debate you have an opinion on?"

This forces a specific, non-generic answer that distinguishes the letter from every other candidate who has "deep experience in AI."

**C. The strongest proof point not in the CV**
CVs compress evidence. Ask:
> "What's the most concrete thing you've done that is directly relevant to this role that your CV undersells or omits entirely?"

**D. What failure looks like**
This is the anti-sycophancy question. Ask:
> "What's the version of this role where you struggle? What would be the first signal it's not working?"

You won't include this in the letter, but the answer shapes what the letter should *not* overclaim.

---

## Phase 2 — JD Analysis

Parse the JD for:

| Layer | Extract |
|-------|---------|
| **Core mandate** | What does success in this role actually look like in 12 months? |
| **Hard requirements** | Skills/experience the JD repeats or leads with |
| **Soft signals** | Framing language that reveals what the team values (e.g., "rigorous", "pragmatic", "builder") |
| **Gaps vs cv.md** | Requirements the candidate does not satisfy on paper |
| **Field vocabulary** | Technical terms, research areas, or product categories the reader uses — the letter must use these correctly, not approximate them |

Flag: if the JD contains requirements the candidate clearly cannot meet and has no honest pivot for, name this before writing. A letter that overclaims is worse than a letter that honestly frames a gap.

---

## Phase 3 — Structural Blueprint

Every letter follows this five-paragraph structure. Do not deviate.

### ¶1 — Open with the problem, not the person

State the actual unsolved problem the role exists to address — at field level, not at job-category level. This is not "I am excited about AI." It is a crisp diagnosis of what is broken or incomplete in the space, framed in a way that makes the reader think *this person has been thinking about what we're working on.*

**Test:** Could this opening paragraph appear on a blog post by a domain expert? If yes, it is pitched at the right altitude. If it reads like a cover letter opener, rewrite it.

**Pattern to avoid:** Personal-origin stories. "I built X because I kept running into Y" is a startup pitch, not a product vision statement.

### ¶2 — Architecture claim

Connect the candidate's most structurally relevant work to the role's core mandate. This is not a summary of the CV — it is a specific claim about *how* a past project illuminates the target problem. The claim must be falsifiable: it names an outcome, a decision made, or a mechanism — not a vibe.

**Format:** "[Project/role] is evidence of [specific capability] because [concrete mechanism or outcome]. The same logic applies to [target role problem] because [structural connection]."

### ¶3 — Strongest credential, reframed as product evidence

The credential the candidate is most tempted to list as a bullet point should instead be restated as a product story: what was shipped, what was measured, what changed. One specific metric or outcome is worth three general claims.

**Test:** Does this paragraph answer "so what?" without the reader having to do work? If the reader has to infer the implication, the paragraph is not done.

### ¶4 — Honest gap + compensating discipline

Name the gap. Do not bury it. Then immediately flip: explain what the candidate brings that compensates structurally — not "I'll learn fast" (this is a promise, not evidence), but a specific adjacent discipline that makes them better-positioned to *evaluate* the gap area critically than someone who came up inside it.

**Anti-pattern:** "I would build these skills quickly on the job." This is a confidence-eroder, not a confidence-builder.

### ¶5 — One field-specific claim

This is the paragraph most candidates skip and the one that most differentiates. Cite one specific, correct thing from the target domain: a standard, a paper, a live debate, a product decision's implication. Not name-dropping — a claim with a point of view attached.

**Test:** Could only someone who has read the relevant material write this sentence? If a generalist could write it from a Wikipedia summary, make it more specific.

---

## Phase 4 — Quality Gates

Run these checks before outputting the final letter. Flag any failures.

| Gate | Pass condition |
|------|----------------|
| **Altitude** | ¶1 reads like a domain expert's framing, not a job applicant's opener |
| **Falsifiability** | Every capability claim has a concrete anchor (project, outcome, metric) |
| **Gap honesty** | One real gap is named and addressed — not buried or papered over |
| **Field specificity** | ¶5 contains a claim that requires domain knowledge to write |
| **No overclaiming** | No claims that `cv.md` cannot support and that elicitation didn't fill |
| **Vocabulary match** | The letter uses the JD's technical vocabulary correctly, not approximately |
| **Length** | 350–450 words. Not a word more. Compression is a signal of clarity. |
| **Non-LLM surface** | No significance puffery, empty participial tails ("…, underscoring…"), or promo adjectives without a CV/JD anchor; see the Wikipedia field guide in the intro |

---

## Phase 5 — Output Format

Output the letter in clean markdown, ready to paste. Then output a separate **Diagnostic Block**:

```
## Diagnostic

**Strongest move:** [What lands best and why]
**Remaining risk:** [What the reader might still object to]
**What this letter cannot do:** [The gap or weakness the letter does not fully resolve]
**One thing to do before sending:** [Specific action — read a paper, verify a claim, add a metric]
```

The Diagnostic Block is not optional. A letter without a diagnosis of its own limits overestimates itself.

---

## Anti-patterns — flag and eliminate on every pass

- Opening with a personal origin story ("I built X because...")
- Credentials listed as bullets instead of evidence
- "I am passionate about" — delete on sight
- "I would love the opportunity to" — delete on sight
- Generic gap disclaimer ("I would build these skills quickly")
- Metaphors doing structural work without a formal definition
- Any sentence that could appear in any other candidate's letter for any other role
- Length over 450 words — compression is not optional
- Significance boilerplate ("testament to," "setting the stage," "evolving landscape," "key turning point") unless it restates the JD's own wording and you need that echo
- Trailing clauses that only restate importance ("…, highlighting the significance of…," "…, reflecting broader…") with no new concrete detail
- Bold or italics inside the letter paragraphs for punch — keep emphasis in word choice

---

## PDF Output

After the markdown letter is approved by the user, generate a PDF using the same visual design as the CV:
- Same HTML template structure (Space Grotesk + DM Sans, gradient header)
- Letter format instead of sections
- Output to `output/cl-{candidate}-{company}-{YYYY-MM-DD}.pdf`
- Format: letter (US companies) or a4 (EU/rest of world), matching the CV for this role
