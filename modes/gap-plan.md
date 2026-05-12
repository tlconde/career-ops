# Mode: gap-plan — Dream role gap analysis from evaluation reports

**Purpose:** Read one or more evaluation reports in `reports/`, compare them to your **North Star** (dream roles) in `config/profile.yml` and your evidence base in `cv.md` (plus `modes/_profile.md` and `article-digest.md` if present), then propose a **credible, ethical** plan to close gaps—not to game applications you are not qualified for.

**Draft / advisory:** This mode synthesizes text already in reports and your profile. It is not a credential audit of employers. Treat output as a coaching brief; validate important decisions (degrees, pivots) with humans or official sources.

---

## Inputs (read before reasoning)

| Source | What to use |
|--------|-------------|
| `config/profile.yml` | `target_roles.primary`, `target_roles.archetypes` (especially `fit: primary`), `narrative`, `background`, `proof_points` |
| `cv.md` | Current experience, skills, education, public links |
| `modes/_profile.md` | User overrides for archetypes and framing (if file exists) |
| `article-digest.md` | Detailed proof points if present |
| Reports | User-specified paths, or latest evaluations by date in filename |

**Dream roles definition:** Use `target_roles.primary` strings **and** archetypes where `fit: primary` (and optionally `secondary` if the user asks for a broader plan). Map each report’s stated archetype or role family to the closest dream archetype.

---

## Scope of analysis

1. **Per report (brief):** Company, role title, score/status if present, **hard blockers** (e.g. PhD required, years of X, location), **soft gaps** (nice-to-have), and **alignment** with each dream role.
2. **Cross-report themes:** Recurring requirements that show up across “stretch” or SKIP evaluations pointing at the same dream path.
3. **Asset inventory:** From `cv.md` + profile proof points—what already supports the dream role (transferable skills, shipped work, domain depth).
4. **Gap → bridge map:** For each major gap, propose **specific, observable** bridges (not vague “learn more ML”).

### Bridge examples (illustrative only)

- **Research credibility / publications gap** (common when dream archetype is AI Researcher / Applied Scientist but reports cite “no publications” or PhD): preprint or workshop paper, reproducible blog + code, open-source benchmark contribution, collaboration with research-adjacent team, or **honest pivot** to roles titled Applied ML / Research Engineer where PhD is not universal—state which path matches the user’s timeline.
- **Product / PM signal:** shipped metrics, PRD samples, stakeholder narratives already in profile—tie to JD language from reports.
- **Depth in a subdomain** (e.g. RL): course + **portfolio artifact** with eval harness, not certificate alone.

---

## Output structure (required)

Use clear headings:

1. **North Star recap** — Dream roles and archetypes (from profile); one line each on what “good” looks like for that path.
2. **Reports reviewed** — List files and one-line each: role + verdict/blocker.
3. **Gap synthesis** — Table or bullets: *Gap* | *Evidence from report(s)* | *Relevant dream role(s)*.
4. **What you already have** — Short bullets grounded in `cv.md` / profile (no invented metrics).
5. **Plan to close gaps** — Prioritized (e.g. P0/P1/P2). For each action: **rationale**, **time horizon** (rough), **artifact or signal** (what a recruiter or HM could verify), **risk or caveat** (e.g. “PhD may remain a gate for title X at org Y”).
6. **Roles to favor meanwhile** — JD patterns that match the user’s current proof points *and* move toward the dream role (ethical targeting—no encouragement to misrepresent credentials).

**Tone:** Direct, supportive, honest about hard gates. If the gap is irreconcilable for a specific employer track (e.g. Research Scientist at a lab requiring PhD + publication record), say so and redirect to adjacent tracks.

---

## Invocation hints

- **Single report:** User pastes path or report header (e.g. after batch eval)—deep dive that report vs dream roles.
- **Multiple / latest:** User says “last 5 reports” or “all April 2026”—glob `reports/*.md`, sort by date in filename, take the slice requested.
- **One dream role focus:** If user names one primary archetype, weight the plan toward that path only.

---

## Subagent delegation (when to use)

If analyzing **more than five** report files or a full-directory sweep, the parent agent should delegate to a subagent with this file’s content plus explicit file list, then consolidate the subagent’s gap table and plan into the required output structure (see main career-ops skill for `Agent(...)` pattern).
