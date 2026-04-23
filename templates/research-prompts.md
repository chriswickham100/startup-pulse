# Research Prompts — Menlo Ventures Portfolio Project
*Paste these into Claude when conducting research. Replace [BRACKETS] with specifics.*

---

## PROMPT 1 — Initial Draft (use after gathering raw notes)

```
I'm researching [COMPANY NAME] for a personal investment research project. 
Below are my raw notes gathered from their website, Crunchbase, LinkedIn, and press.

Please draft a completed 1-pager using the template I'll paste below.
- Use ONLY information that is clearly supported by the notes I've provided.
- Where information is missing, write "[NOT FOUND — needs research]" so I know what to follow up on.
- Do not hallucinate funding amounts, team names, or metrics.
- Keep "My Take" blank — I'll fill that in myself.
- After the 1-pager, list 3–5 follow-up questions a VC associate would want answered.

---
RAW NOTES:
[Paste your notes here — website copy, Crunchbase data, LinkedIn headcount, job posts, press quotes]

---
TEMPLATE:
[Paste the full 1pager-template.md content here]
```

---

## PROMPT 2 — Gap Finder (use after first draft)

```
Here is a draft 1-pager for [COMPANY NAME]. 

Please do the following:
1. Identify the 3 most important gaps or weaknesses in what we know.
2. For each gap, suggest the most likely source where I could find that information (e.g. specific SEC filing type, LinkedIn search, a particular journalist who covers this space, etc.)
3. Flag any claims in the draft that seem like they might be outdated or unreliable.
4. What would a Series A investor ask in their first meeting that this 1-pager can't answer?

---
DRAFT 1-PAGER:
[Paste draft here]
```

---

## PROMPT 3 — Competitive Landscape Builder

```
I'm researching [COMPANY NAME], which operates in [DESCRIBE THEIR SPACE IN 1-2 SENTENCES].

Please help me map their competitive landscape:
1. Who are the 4–6 most direct competitors (at similar or adjacent stages)?
2. For each competitor, note: approximate stage/funding, key differentiator, and one thing [COMPANY] does better or worse.
3. Who are the most dangerous potential entrants — large companies (Google, Salesforce, etc.) that could move into this space?
4. What is the most defensible moat this company could build?
5. Is this market winner-take-all, or likely to support multiple players?

Base your response on general knowledge of this space. Flag anything you're uncertain about.
```

---

## PROMPT 4 — Opportunity Angle (for founder/competitor research)

```
I'm evaluating whether to reach out to work with [COMPANY NAME] or potentially start something adjacent or competitive.

Based on this 1-pager, please help me think through:
1. What are the 2–3 biggest unsolved problems their customers still have?
2. What does their GTM motion suggest about where they're weakest?
3. If I were building a competitor, what would I do differently and why?
4. What is the most realistic way someone with a background in [YOUR BACKGROUND] could add value to this company or its space?
5. What's one niche or geography they're clearly underserving?

---
1-PAGER:
[Paste final 1-pager here]
```

---

## PROMPT 5 — Periodic Refresh (use every 3–6 months)

```
I have an existing 1-pager for [COMPANY NAME] last updated on [DATE].
Here is what has changed since then (paste new notes):

[NEW NOTES — new funding, headcount change, product launches, press, etc.]

Please:
1. Update only the sections that have new information.
2. Note clearly what changed and when.
3. Flag if anything in the old version now appears wrong or outdated.
4. Update the "Interest level" and "Next action" if the new info warrants it.

---
EXISTING 1-PAGER:
[Paste existing 1-pager]
```

---

## PROMPT 6 — Cross-Portfolio Pattern Finder (use after 5+ 1-pagers)

```
I have completed 1-pagers for the following Menlo Ventures portfolio companies:
[List company names and their sectors]

Based on these profiles, help me identify:
1. What themes or thesis areas does Menlo seem most convicted on right now?
2. Are there any sectors where they have overlapping bets? What does that suggest?
3. Across these companies, what founder profiles or team backgrounds appear most common?
4. Which of these companies seems to have the strongest near-term traction signal?
5. What gaps exist in their portfolio that might represent opportunity for a new company?

---
[Paste all 1-pagers, or summaries of each]
```

---

## TIPS FOR GATHERING RAW NOTES (before running Prompt 1)

**30-minute research checklist per company:**

- [ ] Company website — read homepage, About, Blog (last 3 posts), Pricing page
- [ ] Crunchbase — funding rounds, investors, headcount, founding date
- [ ] LinkedIn — current headcount, growth rate, key team members, open roles (filter by department)
- [ ] Google: `"[Company Name]" site:techcrunch.com OR site:venturebeat.com` — last 12 months
- [ ] Google: `"[Company Name]" review` — G2, Trustpilot, App Store
- [ ] SimilarWeb or Semrush (free tier) — monthly traffic estimate
- [ ] Wayback Machine — how has the homepage/messaging changed in 12 months?
- [ ] SEC EDGAR search — any Reg CF or Reg A filings?

**What to paste into Claude:**
Paste raw text excerpts from all of the above — don't summarize yet.
The more raw material you give Claude, the less it will fill in gaps with guesses.
Always note your source next to each excerpt (e.g. "LinkedIn, April 2026").
```

---
*Prompts v1.0 — Menlo Ventures Portfolio Research Project*
