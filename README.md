# ai_bookmarks
collection of domain-specific prompt engineering and mental models— from aerospace engineering, theoretical physics, military operations, and system architecture—designed for precision-driven outputs.

---

## Table of Contents
1. [ASD-STE100 (Simplified Technical English)](#1-asd-ste100-simplified-technical-english)
2. [3Blue1Brown (Intuitive Mathematical Narration)](#2-3blue1brown-intuitive-mathematical-narration)
3. [The Feynman-Geller Technique (Physics Lecture Style)](#3-the-feynman-geller-technique-physics-lecture-style)
4. [The US Navy SEAL "BLUF" & WRAIR Protocol (Mission-Critical Clarity)](#4-the-us-navy-seal-bluf--wrair-protocol-mission-critical-clarity)
5. [The Paul Graham Essay Framework (Intellectual Inversion)](#5-the-paul-graham-essay-framework-intellectual-inversion)
6. [The Architect’s "C4 Model" Blueprint (System Design Style)](#6-the-architects-c4-model-blueprint-system-design-style)
7. [The Bloomberg "Heard on the Street" Financial Synthesis](#7-the-bloomberg-heard-on-the-street-financial-synthesis)

---

### 1. ASD-STE100 (Simplified Technical English)
* **The Inspiration:** International aerospace standard controlled vocabulary designed to eliminate ambiguity, complex syntax, and translation errors in maintenance manuals.
* **The Style:** Forces the AI to use a restricted vocabulary, strict active voice, short sentences, and standardized technical terms.
* **The Prompt Blueprint:**
```bash
  "Adhere strictly to ASD-STE100 Simplified Technical English standards for this response. Use only approved vocabulary, write sentences under 20 words, use active voice exclusively, and eliminate all descriptive filler, corporate jargon, and ambiguous modifiers."*
```
---

### 2. 3Blue1Brown (Intuitive Mathematical Narration) aka 3b1b style videos
* **The Inspiration:** Grant Sanderson’s YouTube channel, famous for building deep mathematical understanding through visual metaphors, geometric transformations, and answering "why" before "how."
* **The Style:** Forces the AI to construct an intuitive mental picture, use spatial framing, and guide the reader through an Aha! moment before introducing formal equations or code.
* **The Prompt Blueprint:**
```bash
  Explain [complex concept/algorithm] using the 3Blue1Brown teaching style. Do not start with definitions or equations. Instead, build a visual mental model: describe what we are looking at geometrically or spatially, explain the core tension or problem it solves, animate the mental transformation step-by-step, and only then introduce the formal math or code.
```
---

### 3. The Feynman-Geller Technique (Physics Lecture Style)
* **The Inspiration:** Richard Feynman’s legendary undergraduate physics lectures and the biographical teaching style of physicist Murray Gell-Mann.
* **The Style:** Forces the AI to explain a hyper-complex technical concept using zero jargon, physical analogies, and spatial intuition before introducing any mathematical formalism.
* **The Prompt Blueprint:**
```bash
  "Explain [complex topic] using the Feynman Teaching Method. Structure the response in three tiers: 1) A physical intuition or real-world analogy a smart 12-year-old can visualize, 2) The mechanical breakdown of why it works physically or logically, and 3) The formal mathematical or architectural definition. Strip out corporate buzzwords and academic hedging."*
```
---

### 4. The US Navy SEAL "BLUF" & WRAIR Protocol (Mission-Critical Clarity)
* **The Inspiration:** Military operational briefs and tactical debrief protocols designed to survive high-stress, low-attention windows.
* **The Style:** Forces Bottom Line Up Front (BLUF) formatting paired with strict risk/consequence parsing. It completely eliminates conversational pleasantries and structures text for split-second scanning.
* **The Prompt Blueprint:**
```bash
  Analyze [problem/architecture] using the military BLUF protocol. Format your output strictly as: **[BLUF]** (1 sentence summary), **[Situation/Risk]** (what breaks if ignored), **[Execution Steps]** (numbered imperative commands), and **[End State]** (what success looks like). Use active voice and drop all introductory text.
```
---

### 5. The Paul Graham Essay Framework (Intellectual Inversion)
* **The Inspiration:** The distinctive essay-writing and startup-advising style of Y Combinator co-founder Paul Graham—characterized by contrarian hooks, dense paragraphs, and relentless first-principles reduction.
* **The Style:** Trains the model to attack a conventional assumption, trace a trend back to an unexpected root cause, and write with conversational intellectual rigor.
* **The Prompt Blueprint:**
```bash
  Analyze [topic/trend] using Paul Graham's essay style. Start with a counter-intuitive observation or a simple, surprising sentence. Avoid structured bullet-point lists where possible; instead, use fluid, dense paragraphs that trace an idea down to its foundational economic or psychological incentive. End with a sharp, memorable insight rather than a summary.
```
---

### 6. The Architect’s "C4 Model" Blueprint (System Design Style)
* **The Inspiration:** Simon Brown’s C4 software architecture model (Context, Containers, Component, Code).
* **The Style:** Instead of giving a rambling text overview of a system, it forces the AI to output architectural thinking strictly hierarchically, treating the response like an engineering blueprint.
* **The Prompt Blueprint:**
```bash
  Describe [system/product] using the C4 architectural abstraction layers. Provide: 1) System Context (who uses it and what it plugs into), 2) Containers (the major deployable units, databases, or microservices), 3) Components (internal module breakdown of the core service), and 4) Code-level interaction patterns for the critical path. Format structural layouts using text-based architecture blocks or Mermaid diagrams.
```

---

### 7. The Bloomberg "Heard on the Street" Financial Synthesis
* **The Inspiration:** Elite financial journalism that translates messy macroeconomic data into punchy, market-moving narratives.
* **The Style:** Forces the AI to look at a technical or business topic through the lens of incentives, second-order effects, and risk exposure rather than generic descriptions.
* **The Prompt Blueprint:**
```bash
  Analyze [technology/business decision] like a senior financial columnist. Focus strictly on second-order effects: Who wins, who absorbs the hidden costs, what structural bottleneck is being ignored, and what historical parallel applies. Keep the tone sharp, cynical, and grounded in economic reality.
```
