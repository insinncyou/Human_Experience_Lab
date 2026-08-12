# Human Experience Lab — Core Knowledge v1.0

This file is reference material for Human Experience Lab. It defines shared vocabulary, quality criteria, and reusable frameworks. It does not override the GPT's behavioral Instructions.

## 1. Human Experience Framework

Human experience is the interaction between a person's goals, interpretation, emotion, motivation, behavior, social context, environment, and the systems they use.

A product is not the experience itself. It is one temporary means a person may use to make progress.

### Human Experience Loop

```text
Observation
→ Context
→ Desired progress / JTBD
→ Psychology
→ Behavior
→ Judgment and trade-off
→ Design opportunity
→ AI-era reframe
→ Principle or hypothesis
→ Validation
```

The loop is iterative. New evidence may change earlier interpretations.

### Evidence levels

- Observed: directly seen, heard, measured, or quoted
- Reported: stated by a participant but not independently verified
- Inferred: plausible interpretation based on evidence
- Assumed: currently unsupported starting belief
- Validated: tested against relevant evidence with known limits

Always label important claims at the appropriate level.

## 2. JTBD

### Definition

Jobs To Be Done examines the progress a person seeks in a specific situation. People may “hire” products, services, habits, or workarounds to make that progress.

### Five levels to distinguish

1. Feature: what the product contains
2. Action or task: what the user does
3. Functional Job: practical progress sought
4. Emotional Job: how the person wants to feel or avoid feeling
5. Social Job: how the person wants to be perceived or relate to others

Example:

- Feature: resume ranking
- Task: compare candidates
- Functional Job: identify who deserves an interview under time pressure
- Emotional Job: feel confident that a strong candidate was not overlooked
- Social Job: be seen as a fair and reliable hiring decision-maker

### Job statement

`When [situation], I want to [progress], so I can [meaningful outcome].`

Strong statements contain a meaningful situation, progress, and outcome without prescribing one solution.

### Quality checklist

- Is the situation specific enough to change behavior?
- Is the statement independent of the current product?
- Does it describe progress rather than an activity?
- Could multiple solutions compete to fulfill it?
- Is it supported by evidence or clearly labeled as a hypothesis?
- Are emotional and social dimensions considered where relevant?

### Common failure modes

- Calling product use the Job: “use Spotify”
- Rewriting a feature as a desire: “I want AI summaries”
- Over-abstracting: “I want happiness”
- Treating an interviewer's first answer as final truth
- Assuming one Job represents every user or every situation
- Asking “why” repeatedly without reconstructing context, timeline, alternatives, or constraints

### Better discovery prompts

- What changed that made the current solution inadequate?
- What was happening immediately before the choice?
- What alternatives were considered, including doing nothing?
- What anxiety or friction delayed the decision?
- What outcome would make the person say the choice worked?

## 3. Design Psychology

Psychological concepts are explanatory hypotheses, not labels to attach after a design decision.

### Attention and cognitive load

People have limited attention and working memory. Complexity depends not only on the number of elements but also on novelty, ambiguity, switching, and time pressure.

Design implications:

- Clarify hierarchy and next action
- Group related information
- Reveal detail progressively when appropriate
- Preserve context across steps
- Reduce unnecessary decisions

Risk: oversimplification can hide information needed for trust or control.

### Recognition and memory

Recognition is often easier than unaided recall. External cues can reduce memory burden.

Design implications:

- Use meaningful labels and visible options
- Preserve recent context
- Provide examples or previews

Risk: too many visible choices increase scanning and comparison cost.

### Mental models and predictability

People interpret unfamiliar systems through prior experience. Predictable patterns reduce learning effort.

Design implications:

- Reuse familiar interaction patterns when they fit
- Make system status and consequences visible
- Explain necessary departures from convention

Risk: familiarity should not prevent a clearly superior model.

### Loss aversion and risk perception

Potential losses can weigh more heavily than equivalent gains, especially under uncertainty and responsibility.

Design implications:

- Make consequences clear
- Provide reversible actions and recovery paths
- Communicate uncertainty honestly

Risk: do not exploit fear or exaggerate loss.

### Default and status quo

People may keep defaults because changing them costs attention or feels risky.

Design implications:

- Choose safe, user-benefiting defaults
- Make consequential defaults visible and editable

Risk: hidden or manipulative defaults undermine autonomy.

### Social proof and trust

Others' behavior can reduce uncertainty, but its meaning depends on relevance and authenticity.

Design implications:

- Show relevant evidence, provenance, and comparison context
- Prefer meaningful trust signals over raw popularity

Risk: fabricated urgency, inflated counts, or irrelevant testimonials are dark patterns.

### Self-efficacy and progress

People persist when they believe they can succeed and can see meaningful progress.

Design implications:

- Provide achievable steps, feedback, and recovery
- Celebrate meaningful progress without infantilizing the user

Risk: progress metrics can become coercive or distort the real goal.

### Motivation

Motivation may be intrinsic, extrinsic, social, identity-based, or situational. The same behavior can have different motives.

Design implications:

- Understand what progress matters to this person
- Avoid assuming rewards are universally motivating
- Protect autonomy, competence, and relatedness when relevant

## 4. Behavior Design

Behavior should be analyzed as a relationship among context, trigger, ability, motivation, action, feedback, and consequence.

### Behavior map

- Trigger: what prompts action now?
- Ability: can the person perform it with current time, skill, access, and energy?
- Motivation: why would the person act?
- Friction: what makes action difficult, uncertain, or costly?
- Feedback: how does the system communicate result and status?
- Reward or outcome: what immediate and delayed consequence follows?
- Habit or adaptation: what changes after repetition?

### Ethical test

Before recommending a behavioral intervention, ask:

- Does it serve the user's stated interest?
- Is it transparent enough to understand?
- Can the user refuse or reverse it?
- Does it create dependency or exploit vulnerability?
- Who benefits and who bears the cost?
- Is it accessible across different abilities and contexts?

## 5. Aesthetic Judgment

### Definition

Aesthetic judgment is the ability to decide what form, tone, rhythm, density, motion, and restraint are appropriate for a particular human context and product intent—and to explain why.

It is not identical to visual preference, trend familiarity, or brand imitation.

### Evaluation dimensions

- Context fit: appropriate to user, task, risk, environment, and culture
- Hierarchy: attention moves in the intended order
- Coherence: elements express a consistent logic and tone
- Restraint: nothing competes without purpose
- Legibility: content and actions are perceivable and understandable
- Interaction quality: feedback, timing, motion, and state changes feel intentional
- Emotional tone: experience evokes a fitting degree of calm, urgency, warmth, authority, or play
- Trust: claims, consequences, uncertainty, and system status are clear
- Accessibility: quality remains available across different abilities and conditions
- Brand meaning: expression supports the product's values without imitation

### Comparison protocol

1. Define the context and evaluation criteria.
2. Compare materially different directions.
3. Rank them and explain trade-offs.
4. Separate personal taste from contextual fit.
5. Argue against the preferred direction.
6. Remove nonessential elements.
7. State a reusable decision rule.

### Strong critique language

Prefer:

- “This hierarchy supports rapid verification under time pressure.”
- “The motion reinforces causality but may feel slow for repeated expert use.”
- “The sparse layout communicates calm, but hides evidence needed for a high-risk decision.”

Avoid:

- “It feels premium.”
- “It looks like Apple.”
- “This is cleaner.”

unless the statement is followed by observable reasons and contextual consequences.

## 6. Experience Critique

Experience Critique is a disciplined way to analyze any human-facing experience—UI, product, service, space, hospitality, advertising, or AI interaction—without collapsing observation into judgment.

### Core sequence

`Frame → Observation → Interpretation → Critical Questioning → Hypothesis → Human mechanism → Experience judgment → Generalization / Application → Knowledge capture`

Important claims must be labeled as Observed, Reported, Inferred, Assumed, or Validated. Personal preference can be recorded, but it is not evidence of contextual fit.

### Quality rules

- Start with one concrete person, moment, and available evidence.
- Ask for a plausible alternative explanation before accepting a causal claim.
- Treat psychology, behavior theory, and JTBD as explanatory lenses, not proof.
- State the design trade-off: what a direction improves, sacrifices, and could harm.
- Make Principles conditional. A single case produces a Draft principle until it is tested across relevant contexts.
- When capturing knowledge, compare the proposed principle with existing Research Notes; preserve duplicates, tensions, and boundary conditions rather than erasing them.

### Experience Principle

`When [specific context], people need/want [progress]. Therefore, the experience should [direction], while avoiding [risk or trade-off].`

## 7. Design Opportunity

A design opportunity connects a human need and a system intervention without prematurely prescribing a screen.

Structure:

`How might we help [person] make [progress] in [context] while protecting [important constraint or value]?`

Example:

`How might we help a hiring manager narrow a large candidate pool under time pressure while preserving explainability and fairness?`

## 8. AI-era Reframe

AI may summarize, predict, generate, personalize, automate, explain, or converse. Its presence introduces new questions.

### Evaluation questions

- What human Job becomes easier?
- Which decision should remain human-led?
- What uncertainty must be visible?
- How can the user inspect, correct, or override the AI?
- What happens when the AI is wrong?
- Does personalization reduce agency or shared understanding?
- What data, consent, bias, and privacy risks appear?
- Is AI necessary, or is a simpler solution better?

### Role options

- Assistant: reduces effort while the human directs
- Advisor: offers recommendations with evidence and uncertainty
- Collaborator: develops alternatives with the human
- Automator: executes bounded work with review and recovery
- Mediator: helps people coordinate or understand each other

Choose the smallest role that safely supports the Job.

## 9. Design Principles

### Purpose

A Design Principle captures a reusable decision rule derived from evidence and reflection. It is more specific than a slogan and more general than one UI solution.

### Template

`When people are [context], they need/want [human need or progress]. Therefore, the experience should [design direction], while avoiding [risk or trade-off].`

### Quality checklist

- Context is explicit
- Human need or progress is clear
- Design direction permits multiple implementations
- Trade-off or risk is acknowledged
- Evidence status is recorded
- The principle is testable or falsifiable

### Example

When people make a high-stakes choice under time pressure, they need confidence without reading every detail. Therefore, the experience should surface the decisive evidence and allow deeper inspection, while avoiding false certainty and hidden assumptions.

Status: hypothesis pending user validation.

## 10. Research Note Standard

A good note distinguishes what happened from what it might mean.

Minimum fields:

- Topic and context
- Observation
- Interpretation / hypothesis
- Job
- Relevant mechanism
- Design judgment or opportunity
- Evidence gap
- Principle

Notes should be concise enough to review later and specific enough to challenge.

## 11. Thinking Score Rubric

Use 0–5 only for dimensions exercised in the session.

### Observation

- 0: no observable detail
- 3: some facts separated from interpretation
- 5: precise facts, context, and uncertainty clearly separated

### Context

- 0: generic user and situation
- 3: meaningful situation and constraints identified
- 5: context explains why behavior or priorities change

### JTBD Depth

- 0: feature or activity
- 3: functional progress with a meaningful outcome
- 5: evidence-grounded functional progress with relevant emotional/social dimensions

### Psychology

- 0: labels without explanation
- 3: plausible mechanism connected to evidence
- 5: alternative explanations and uncertainty considered

### Behavior

- 0: action described without causes or consequences
- 3: trigger, friction, and feedback identified
- 5: behavior understood across context, ability, motivation, and downstream effects

### Judgment

- 0: pure preference
- 3: choice tied to criteria and context
- 5: trade-offs, counterargument, and risk explicitly evaluated

### Abstraction

- 0: product-specific observation only
- 3: reusable insight with context
- 5: bounded, testable principle with evidence status
