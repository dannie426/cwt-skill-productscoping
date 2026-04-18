---
name: product-scoping
description: Use this skill when a team or individual wants to scope a product idea, especially in a hackathon or time-constrained build context. Triggers when someone says things like "help me scope my idea", "I want to validate my product idea", "help us figure out what to build", "we need a design or build handoff", or "we want to run a product scoping session". This skill guides the user through a structured discussion, then extracts two handoff documents — one for design, one for the builder or coding agent.
---

# Product Scoping Skill

This skill runs a two-phase product scoping session:

**Phase 1 — Discussion Guide**
Present the question list to the user. They discuss it as a team (or solo) and return their answers — either typed directly, or as a transcript from a recording tool like Granola.

**Phase 2 — Extraction**
Take whatever they return and produce two clean handoff documents.

---

## Phase 1: Present the Discussion Guide

When the skill is triggered, present the following to the user exactly as written:

---

**PRODUCT SCOPING SESSION**

*Work through these questions as a team. You don't need to cover every single one — go deep on what matters most for your idea. You can type your answers here directly, or record your discussion and paste the transcript when you're done.*

---

**THE USER**
1. Who specifically is this for? Describe one real person — their situation, their context, their day.
2. What are they trying to do or achieve that they currently can't, or can't do well?
3. How are they solving this problem today, and what's frustrating about that?

**THE PROBLEM**
4. What's the core friction? Describe it in one sentence without mentioning your solution.
5. How often does this person experience this problem, and how much does it bother them?
6. Is there a moment where this frustration peaks — a specific situation where it becomes really painful?

**THE ANGLE**
7. What already exists that tries to solve this? Name at least one thing.
8. What does your product do that those things don't, or who does it serve that they don't?
9. Why is now the right time for this to exist?

**THE EXPERIENCE**
10. When someone uses your product, how do you want them to feel? Name the emotion.
11. What's the single most important moment in the experience — the one thing that has to land?
12. Walk through the core flow in plain language: what does the user do first, then what, then what?
13. Are there any existing products, apps, or experiences that capture the feeling you're going for? Name them and say what you're borrowing.

**THE SCOPE**
14. If you could only build one thing today, what would it be?
15. What features are you explicitly leaving out, and why?
16. What needs to actually work end to end, and what just needs to look like it works?
17. What's the one moment in your demo that has to be real and has to be good?

---

*When you're ready, paste your answers or transcript below and I'll produce your handoffs.*

---

## Phase 2: Extract and Produce Handoffs

Once the user returns their answers or transcript, produce the following two outputs. Use only what the team actually said. Do not fill gaps with assumptions. Where something wasn't covered, flag it clearly as **Still to resolve: [topic]**. If the team was unclear or contradicted themselves, flag it rather than resolving it for them.

---

### OUTPUT 1: DESIGN HANDOFF

*For the designer. Covers the user, the feeling, the key moments, the flow, and references.*

Structure:
- **The user**: Who they are, their context, their core frustration in their daily life
- **The feeling**: How the team wants the user to feel when using the product
- **The key moment**: The single most important moment in the experience that has to land
- **The core flow**: What the user does, step by step, in plain language
- **References and inspiration**: Any existing products, apps, or experiences the team mentioned

---

### OUTPUT 2: BUILD HANDOFF

*For the developer or coding agent. Covers the idea, the feature list, the demo flow, and what's out of scope.*

Structure:
- **Idea statement**: One sentence — who it's for, what problem it solves, what makes it different
- **Feature list**: What needs to be built, in priority order
- **Demo flow**: What needs to work end to end for the demo
- **Out of scope**: What the team explicitly decided not to build
- **Dependencies or constraints**: Any technical considerations the team mentioned

---

## Behaviour Notes

- Keep both outputs tight and immediately usable. These will be handed off and acted on within minutes.
- Do not pad or summarise beyond what's needed.
- If the input is a raw transcript with crosstalk or filler, clean it up but stay faithful to what was actually said.
- Tone should be direct and practical — no introductory fluff.
