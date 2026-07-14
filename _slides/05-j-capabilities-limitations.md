---
transition: zoom
---

## The AI Capabilities and Limitations Framework

Delegating well — and, later, discerning good output from bad — depends on a realistic picture of what today's AI is actually good at. This companion framework names **four properties that shape what AI can and can't do for you.** Each sits on a spectrum: the further toward the *limitation* end your task falls, the more you should verify the output and compensate for it.

| Property | The question it answers | Works well (capability) | Gets shaky (limitation) |
|----------|-------------------------|-------------------------|-------------------------|
| **Next Token Prediction** | Where do AI answers come from? | Well-worn paths: summarize, reformat, explain common concepts | Novel territory, sparse patterns; "true" vs. "sounds true" |
| **Knowledge** | What does the AI actually know? | Frequent, recent-in-training, consistent: mainstream topics, popular languages | Rare, post-cutoff, niche, local, or contested topics |
| **Working Memory** | What is the AI paying attention to right now? | Material fits comfortably, session is current, you supply the relevant context | Very long documents/conversations; expecting cross-session continuity (the "cliff") |
| **Steerability** | How much am I in control? | Short, concrete, verifiable instructions ("respond as a table," "under 100 words") | Long reasoning chains, abstract asks, native precision |

Read the table as a checklist for **Delegation** and **Discernment**: before handing a task to AI, ask where it lands on each spectrum. A task built from common concepts, mainstream knowledge, a short context, and a concrete instruction is a safe delegation. A task in novel territory, on post-cutoff or contested facts, over a huge context, and requiring a long, precise chain of reasoning is one to supervise closely — or keep for a human.

> **Try it:** The [Token Prediction Playground](https://www.billmongan.com/Ursinus-CS357-Fall2026/TokenPredictor) is a tiny in-browser next-word model: feed it a common phrase and watch it get confident (capability); feed it rare or ungrounded words and watch it shrug (limitation). It makes the top row of the table above tangible — and it is the tool you will use in the icebreaker below.

*Copyright 2026 Anthropic. Original work building on the AI Fluency Framework developed by Prof. Rick Dakan (Ringling College of Art and Design) and Prof. Joseph Feller (University College Cork). Released under the CC BY-NC-SA 4.0 license.*
