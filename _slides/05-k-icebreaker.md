---
transition: zoom
---

## Icebreaker: Predict the Next Token

*Estimated time: 20 minutes.*

Today's first practice is **seeing where AI answers come from**. No accounts, no installs — just your team, paper, and the course's [Token Prediction Playground](https://www.billmongan.com/Ursinus-CS357-Fall2026/TokenPredictor), a tiny next-word model that runs entirely in your browser. The goal is to feel the top row of the Capabilities and Limitations table — *Next Token Prediction* — from the inside.

**Step 1 — Predict by hand (7 minutes).** As a team, take these prompt stems (the Manager keeps time; the Recorder writes everything down). For each, every member privately writes the **three most likely next words** and a confidence (high/medium/low) — before anyone opens the Playground:

- "The capital of France is ___"
- "Once upon a ___"
- "To be or not to ___"
- "My professor's favorite ___"
- "The 2027 Nobel Prize in Physics was awarded to ___"

Compare within the team: where did everyone agree? Where did predictions scatter?

**Step 2 — Compare with the simulator (7 minutes).** Now type each stem into the [Token Prediction Playground](https://www.billmongan.com/Ursinus-CS357-Fall2026/TokenPredictor) and record what it predicts, and how confidently. Score your team against the machine. Watch for the pattern: on well-worn phrases the model is confident and so were you; on rare, personal, or future-facing stems it shrugs — and so, honestly, did you.

**Step 3 — What prediction can and cannot do (6 minutes).** Discuss as a team, and the Recorder posts your answers to the discussion board:

- Which stems were easy for both humans and the model, and *why*? (What makes a continuation "well-worn"?)
- Which stems *cannot* be answered by pattern-completion at all, no matter how much text the model has seen? What would a system need instead?
- If a model always continues with what "sounds right," when will "sounds true" diverge from "is true"? Name one concrete task where you would therefore verify its output.

### Reflection

- What surprised you about how well (or poorly) your team predicted the model's behavior?
- Where does your own knowledge come from, and how is that different from — or similar to — next-token prediction?
- Name one task from your own week that next-token prediction alone could handle, and one it could not.
