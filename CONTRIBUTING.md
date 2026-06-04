# Contributing to Eternaldad

**Eternaldad is built by single fathers, for single fathers.**

This repository exists to collect, test, and share the systems that work in real households under real pressure. If you have a system that works, we want to hear about it.

---

## What We're Looking For

### ✅ Systems That Fit

We accept contributions that are:

- **Tested in a real household** — You have lived this. You have data. You know what works and what breaks.
- **Specific, not generic** — Not "spend less money." The exact number, the exact method, the exact outcome.
- **Honest about the limits** — What worked for you might not work for everyone. Say so. Name the conditions where your system holds and where it doesn't.
- **Grounded in evidence** — Research that backs the claim. Or a household story that proves it. Or both.
- **Written in the Budget Dad voice** — Authoritative without arrogance. Direct without dismissal. Specific without condescension.

### ❌ What We Don't Accept

We do **not** accept contributions that:

- Are generic or theoretical — "You should try meal planning" without the specific system
- Make claims without evidence — Research citations or household proof required
- Use vague language — "Comprehensive," "transformative," "game-changing," hedged conditionals ("might," "could," "maybe")
- Blame or shame — Single fathers. No judgment. No "you should have" or "you need to understand"
- Are self-promotional — Your system, yes. Your product or paid service, no (unless pre-approved by the maintainer)
- Lack specificity — No names, no numbers, no real moments from real households

---

## How to Contribute

### Step 1: Check If Your Idea Fits

Before you write anything, open a **Discussion** in the [Eternaldad Discussions](https://github.com/budgetdad/Eternaldad/discussions) section.

Title: **"Idea: [Your System Name]"**

Example:
> "Idea: The Sunday Prep Block — How I batch cook 5 meals in 2 hours for $12 total"

In your post, include:
- **One-sentence summary** of the system
- **Who it's for** — age of children, household income range, specific situation it solves
- **The core problem it addresses** — What was broken before you built this system?
- **One proof point** — A specific number or outcome from your household

The maintainers will respond within 48 hours with feedback. This prevents you from writing 2,000 words on something that's outside the scope.

### Step 2: Write Your System

If your idea is approved, create a **new file** in the `/systems` directory.

**File naming convention:**
```
systems/[CATEGORY]/[SYSTEM-NAME].md
```

**Examples:**
- `systems/budgeting/envelope-method.md`
- `systems/meal-planning/sunday-batch-cook.md`
- `systems/discipline/boundary-framework.md`
- `systems/routine/5-30am-morning-block.md`

**File structure:**

```markdown
# [System Name]

## Who This Is For
- Age of children (or "any age")
- Household income range / specific financial pressure
- Specific situation it addresses (e.g., "work-from-home single dad," "managing four children under 10," "first month post-divorce")

## The Problem This Solves
**Specific household moment.** Not abstract. Real.

Example: "It was 6:47am. Kennedy had three minutes before the school van arrived and was still in bed. I had already woken him twice. I was running late for my 7am call with a client. We were both frustrated. Something had to change."

## The System (Step by Step)

### Step 1: [Exact Action]
**What you do:** [Specific instruction]
**Why it works:** [The mechanism — the research or household proof that explains why]
**What happens:** [The real outcome from your household]

### Step 2: [Exact Action]
[Repeat for each step]

## The Evidence

### Household Results
- **Metric:** [Specific, measurable outcome]
- **Timeline:** [How long it took to see results]
- **Proof:** [Real number or specific event that proves it worked]

Example:
- **Metric:** Morning departure time (target: on time 100% of school days)
- **Timeline:** 3 weeks to establish
- **Proof:** Kennedy has been on time or early for 24 consecutive school days

### Research That Confirms This

[Citation format: Author (Year), Publication, finding]

Example: "Dweck (2019) confirms that effort-specific acknowledgement produces sustained behavior change better than outcome praise."

## Where It Works Best

- [Condition 1]
- [Condition 2]
- [Condition 3]

## Where It Breaks Down

Be honest about the limits.

- [What situation makes this system fail?]
- [What won't this solve?]
- [What alternative might work better for X situation?]

## What I Tried First (That Didn't Work)

Show the journey. This builds trust.

Example: "I tried a sticker chart for a week. Kennedy responded to the novelty, but by week two it was background noise. This system works because it connects his action directly to a household outcome he understands and values."

## The Real Moment That Proved It

End with a specific, real event that shows the system working.

Example: "Thursday morning. Kennedy woke up on his own at 6:15am. He got himself ready without being told. He was sitting on the couch at 6:55am. When the van arrived, he put on his shoes without me asking. That is the system working."

## Questions? 

Drop them in the Discussions section. We'll refine this together.

---

**Author:** [Your name or username]  
**Household:** [Number of children, ages, location if relevant]  
**Last updated:** [Date]  
**Status:** Tested and working since [date] — [time period]
```

### Step 3: Research & Citations

Every claim needs backing.

**If you're citing research:**
1. Use the confirmed Budget Dad citation set (see [Budget_Dad_Brand_Voice.js](./Budget_Dad_Brand_Voice.js) for the full list)
2. Include: Author (Year), Publication, specific finding
3. Link to the source if available

**If you're using household evidence:**
1. Be specific — name the child if relevant, give the exact time/date/situation
2. Include a measurable outcome — not "it worked better" but "24 consecutive school days on time" or "$42 saved per week"
3. Show the before and after — what changed when you implemented the system

**If you're combining both:**
This is strongest. Principle confirmed by research. System tested in your household. Proof point demonstrated.

### Step 4: Submit a Pull Request

1. **Create a branch** from `main` — name it `systems/[system-name]`
2. **Add your file** to the `/systems` directory following the structure above
3. **Open a PR** with:
   - **Title:** "Add: [System Name] — [One-line description]"
   - **Description:** 2–3 sentences on what this system does and who it's for
   - **Link to Discussion:** Reference the Discussion where this was approved

### Step 5: Review & Refinement

- Maintainers will review for voice, specificity, and evidence
- You may be asked to:
  - Add more specific examples
  - Include research citations
  - Clarify which conditions the system works under
  - Adjust language to match the Budget Dad voice
- This is collaborative, not adversarial. We're building this together.

### Step 6: Merge & Celebrate

Once approved, your system goes live in the repository. It's now part of the collective knowledge of Eternaldad.

---

## The Budget Dad Voice — Contributor Checklist

Before you submit, make sure your contribution:

- [ ] **Opens with a real household moment** — Not abstract. A specific time, a named child, what actually happened.
- [ ] **Names the problem clearly** — What was broken? What were you doing before?
- [ ] **Gives step-by-step system** — Specific enough to implement tonight.
- [ ] **Includes proof** — A real number, a real outcome, a real moment that proves it works.
- [ ] **Cites research or explains why** — Why does this system work? What's the mechanism?
- [ ] **Is honest about limits** — Where does this system break? What won't it solve?
- [ ] **Uses the right language** — Specific numbers, named children, exact times. No "comprehensive" or "holistic." No "you should."
- [ ] **Shows the journey** — What you tried first that didn't work. This builds trust.
- [ ] **Ends with proof** — A real moment when the system worked. The dispensary version for your system.

---

## Types of Contributions We Want

### 1. Systems (Most Important)

New frameworks for:
- Budgeting and financial management
- Meal planning and nutrition
- Discipline and boundaries
- Morning and evening routines
- Work-from-home management
- Medical preparedness
- School communication
- Co-parenting systems
- Teen conversations
- Child-appropriate responsibility
- Household decision-making
- Time management
- Stress management

### 2. Real Household Stories

Moments that illustrate a principle:
- The specific time a boundary held (or broke)
- The number that proved the system works
- The child's response when the system was implemented
- The before/after of a real situation

### 3. Research Confirmations

If you find research that backs a Budget Dad principle, share it:
- The citation (full, verifiable)
- How it connects to a system in the repository
- A one-paragraph summary of the finding

### 4. Tool Templates

Spreadsheets, checklists, or templates that implement a system:
- Budget tracking sheets
- Meal planning templates
- Discipline logs
- Routine checklists
- Medical preparedness lists

(Submit these as `.xlsx`, `.csv`, or `.md` files in a `/templates` directory)

### 5. Documentation Improvements

- Clearer explanations of existing systems
- Better examples
- Additional research citations
- Links between related systems
- Index or navigation improvements

### 6. Questions & Discussions

If you don't have a full system yet but you have a question or a challenge:
- Open a **Discussion** (not an Issue)
- Describe the problem you're facing
- Ask for help or suggestions
- Share what you've tried

The community will help you build the system.

---

## What Happens to Your Contribution

### Attribution
Your contribution will include:
- Your name or username
- A link to your GitHub profile
- A note about your household (age of children, location if relevant, timeline of how long you've used the system)

### Maintenance
- If a system becomes outdated, we'll work with you to update it
- If a system is superseded by a better one, we'll keep both and note the difference
- You retain the right to update your own contributions anytime

### Visibility
- Your system will be featured in the main repository
- It may be adapted for products (with full credit and compensation negotiated)
- It will be part of the collective knowledge of single fathers building better systems

---

## Code of Conduct

All contributors are expected to follow the [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

In short:
- **Be respectful** — We are all doing hard things
- **Be specific** — Vague criticism helps no one
- **Be honest** — Say what works and what doesn't
- **Assume good intent** — Questions come from wanting to understand, not wanting to attack

---

## Questions?

- **About the process?** Open a Discussion: ["Questions About Contributing"](https://github.com/budgetdad/Eternaldad/discussions)
- **About a specific system?** Comment on the relevant Pull Request or Discussion
- **About the voice or standards?** Read [Budget_Dad_Brand_Voice.js](./Budget_Dad_Brand_Voice.js) or ask in Discussions

---

## The Mission

**Eternaldad exists because single fathers deserve systems built by single fathers.**

Every contribution makes it easier for the next single father to find the system that works for his household, test it, and build from there.

Thank you for being part of this.

---

**"A boundary that collapses under pressure tells them something equally important. And they remember it longer."**

— Mwebe Morgan, Budget Dad
