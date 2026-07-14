---
transition: zoom
---

## 2. A Working Definition

In this section, you will lock down the formal definition of an agent and place it on a spectrum from simple reflex to fully autonomous — so that every system you encounter this semester has a precise vocabulary to describe it.

**An agent is anything that perceives its environment through sensors and acts upon it through actuators in pursuit of a goal** (Russell and Norvig). For the software agents in this course:

$$
\text{action}_t = \pi(\text{observation}_t, \text{memory}_t, \text{goal})
$$

where $\pi$ is the agent's **policy**: the rule, program, or model that maps what the agent knows to what it does next. In the agents we build, $\pi$ is implemented by a **large language model** plus the scaffolding we write around it.

**Agency is a spectrum, not a switch.** A system is *more agentic* when it takes more steps autonomously, uses more tools, and recovers from more errors without a human in the loop. Greater agency brings greater usefulness, and greater responsibility — which is why governance occupies the final unit of this course.

Now that you have a working definition of agency, the next section previews the arc of the entire semester so you can see where each future topic fits.

A spam filter classifies each incoming email as spam or not, one message at a time, and takes no further action. According to our working definition, the *most* accurate description is:

- It is a fully agentic system because it perceives and acts
- **✓ It exhibits minimal agency: it perceives and acts, but pursues no multi-step goal and uses no tools**
- It is not an agent because it uses machine learning
- It is not an agent because it has no body

> **⚠️ Common Misconception:** Many people assume that "AI" and "agent" mean the same thing, and that any system using machine learning is therefore an agent. In fact, a spam filter is an AI system (it learned from data) but barely qualifies as an agent, because it reacts to one email at a time with no goal that spans multiple steps. Conversely, the thermostat in System A is agent-like — it pursues a temperature goal continuously — but uses no AI at all. Agency and machine learning are separate ideas that often appear together but do not require each other.
