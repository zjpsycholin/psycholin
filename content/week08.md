---
title: "Week 8: 🧩 Sentence Processing II"
subtitle: "Traxler, Ch. 4 (pp. 155–181) — Sentence Processing"
tags: ["discourse inference", "bridging", "elaborative", "situation model updating", "neural basis"]
summary: "How ambiguity is resolved under memory limits: cue-based retrieval, interference, locality, surprisal/expectations, PP-attachment & relative clauses, plus hands-on parsing practice."
---






<!--
## 📘 Overview
Building sentence structure in real time means juggling **multiple possibilities** while keeping prior words active in **working memory**. This week focuses on **how ambiguities get resolved** under **memory constraints**. We’ll examine **cue-based retrieval and interference**, **locality effects**, and **expectation-based (surprisal)** accounts. You’ll practice **PP-attachment** and **relative clause** parsing, run a **memory–interference mini-demo**, and learn to read **eye-tracking metrics** used in sentence processing research.

---

## 🎯 Learning Goals
By the end of Week 8, you should be able to:

- Explain how **working memory** and **cue-based retrieval** affect online parsing.
- Identify **similarity-based interference** and **locality** effects in comprehension.
- Apply **expectation/surprisal** logic to predict harder vs. easier continuations.
- Diagnose **PP-attachment** and **relative clause** ambiguities and justify your analysis.
- Interpret basic **eye-tracking measures** (first pass, regressions, total time) as evidence for ambiguity resolution and reanalysis.

---

## 📖 Required Reading
- **Traxler (1st ed.), Chapter 4, pp. 155–181** — *Sentence Processing* (ambiguity resolution, memory constraints, attachment, and individual differences).

---

## 🔑 Key Concepts & Mini-Explanations

### 🧠 Working Memory in Parsing
- **Maintenance + retrieval**: Words/phrases must be **kept active** and later **retrieved** to integrate new input. Load rises with **multiple clauses**, **embeddings**, or **long dependencies**.
- **Cue-based retrieval**: The parser uses **cues** (number, gender, thematic role) to fetch the right item from memory. Retrieval is **content-addressable** (jump directly to matches), not serial search.

### 🧲 Similarity-Based Interference
- **Interference** occurs when **distractors** share cues with the true target.  
  - *Example*: *The **keys** to the cabinet **were**…* vs. *The **key** to the cabinets **were**…* (number-marked distractor can mislead agreement or slow parsing).
- Predicts **more errors/slowdowns** when **multiple nouns** match retrieval cues (e.g., two plural NPs near the verb).

### 📏 Locality & Dependency Length
- **Locality effects**: Integrating two elements is harder when they are **farther apart** (longer **dependency length**).  
- Nested/center-embedded clauses produce **processing overload**:  
  - *The reporter [that the senator [that the journalist criticized] attacked] resigned.*

### 📈 Expectation & Surprisal
- **Expectation-based parsing**: Readers build **probabilistic expectations** from **frequency** and **context**.  
- **Surprisal** ≈ –log P(word | context): **unexpected** words/structures cause larger slowdowns.  
- Predicts easier processing when context **strongly predicts** the upcoming structure.

### 🧩 PP-Attachment Ambiguity
- *I saw the man with the telescope.*  
  - **VP-attachment**: *saw (with the telescope)* (instrument).  
  - **NP-attachment**: *the man (with the telescope)* (modifier).  
- Resolution relies on **verb bias**, **plausibility**, and **prosody/punctuation**.

### 🧱 Relative Clause Ambiguity (Subject vs. Object RC)
- **Subject RC (SRC)**: *The reporter [who __ attacked the senator] …*  
- **Object RC (ORC)**: *The reporter [who the senator attacked __ ] …*  
- ORCs often **harder** (longer dependency, interference from interveners). **Animacy** and **case marking** can mitigate difficulty (cross-linguistic variation).

### 👣 Evidence from Eye-Tracking
- **First fixation** / **first pass** time: early processing.  
- **Regression path (go-past)**: time including the **first regression**—sensitive to **garden-paths**.  
- **Total time**: later integration/repair.  
- **Where slowdowns appear** helps localize **disambiguation points** and **reanalysis** cost.

### 🧪 Good-Enough Comprehension
- Under load/time pressure, readers may build **shallow** representations guided by plausibility (“good enough”) rather than full syntactic detail—especially in noisy contexts.

---

## 📝 Pre-Class Activities
1. **Read** pp. 155–181 and mark one **PP-attachment** and one **RC** example that slowed you down.  
2. **Cloze guess**: For the stem *“The editor realized the article …”* write **three continuations** (from most to least expected).  
3. **Memory rehearsal**: Read and repeat aloud a sentence with one **center-embedding**; notice where you hesitate.

---

## 💬 In-Class Activities

### 1) Interference Mini-Demo (10 min)
- Instructor presents pairs; you predict which is harder and why:  
  1. *The **keys** to the cabinet **were** on the table.*  
  2. *The **key** to the cabinets **were** on the table.*  
- Discuss: Which cues (number, proximity) created **retrieval conflict**?

### 2) PP-Attachment Workshop (15 min)
- **Pairs** label each sentence as **VP-attach** or **NP-attach** and give **one cue** (verb bias/plausibility/prosody) that favors your choice.  
  - *I photographed the girl with the **drone**.*  
  - *I bumped the vase with the **elbow**.*  
  - *They spotted the hiker with the **binoculars**.*  
- **Bonus rewrite**: Add **comma**/**that**/**prosody** to force your intended reading.

### 3) Relative Clause Lab (15 min)
- **Triads**: Classify as **SRC** or **ORC**; predict difficulty and **why** (distance/interference/animacy).  
  - *The researcher who __ praised the technicians presented the results.*  
  - *The researcher who the technicians praised __ presented the results.*  
  - *The patient that the nurse with the badges comforted __ recovered quickly.*  
- **Tweak** animacy/case to reduce difficulty and re-test your prediction.

### 4) Surprisal & Continuations (10 min)
- Groups propose **high- vs low-expectation** continuations for stems like:  
  - *Because the chef forgot the* …  
  - *When the witness identified the* …  
- Rank continuations from most to least **expected**; predict where **slowdowns** would occur.

### 5) Reading Measures Quick Read (8 min)
- Given a short ambiguous paragraph, identify the **disambiguation region**.  
- Decide which measure (first pass, go-past, total time) would likely show the **largest effect**, and why.

### 6) Wrap (2 min)
- On a sticky: write **one interference cue** and **one way** to reduce it (e.g., change number/animacy or add a function word).

---

## 🔁 Post-Class Review
- **One-pager**: For one PP sentence and one RC sentence, list: ambiguity type → cues considered → final parse → predicted **slowdown region**.  
- **Reflection (100–120 words)**: Which framework (**locality**, **interference**, or **surprisal**) best explained your own slowdowns today? Give one concrete example.

---

## 🏠 Homework
- **Textbook “Test Yourself”** (Ch. 4, pp. 155–181) items on ambiguity resolution and memory constraints.  
- **Short analysis (≈150–200 words)**: Choose an English news sentence with a PP or RC ambiguity. Analyze resolution using **two** lenses (e.g., interference **and** surprisal).  
- **Optional**: Collect two **self-made minimal pairs** that manipulate **distance** (short vs. long dependency) and predict which will be harder.

---

## 🧩 Self-Check Questions

**Q1.** What is **cue-based retrieval**, and how does it explain interference?  
<!-- Retrieval uses diagnostic cues (e.g., number, case) to directly access items in memory; similar distractors that partially match the cues compete, causing slowdowns or errors. -->
<!--
**Q2.** Give an example of a **locality effect**.  -->
<!-- Longer distances between dependent elements (e.g., subject–verb) increase processing cost, especially in center-embedded structures. -->
<!--
**Q3.** How does **surprisal** predict processing difficulty?  -->
<!-- Higher surprisal (lower conditional probability of a word/structure) leads to larger processing slowdowns at that point. -->
<!--
**Q4.** In *I saw the man with the telescope*, what cues could bias **VP** vs **NP** attachment?  -->
<!-- Verb instrument bias (see/photograph), plausibility of instrument vs modifier, prosody/commas, and discourse focus. -->
<!--
**Q5.** Why are **object relative clauses** often harder than **subject relatives**? --> 
<!-- Longer dependencies and more opportunities for similarity-based interference due to intervening nouns; animacy/case cues can mitigate the cost. -->

---
<!--
## 🧰 Key Terms
**Cue-based retrieval**, **Similarity-based interference**, **Locality (dependency length)**, **Expectation**, **Surprisal**, **PP-attachment (VP vs NP)**, **Subject/Object relative clause (SRC/ORC)**, **Filler–gap dependency**, **First pass/Go-past/Total time**, **Good-enough processing**.

---

## 🌐 Optional Resources
- Short explainers on **cue-based parsing** and **surprisal** (intro-level blog posts/videos).  
- Eye-tracking visualization examples showing **regressions** at disambiguation points.  
- Practice sets for **PP-attachment** and **relative clause** ambiguities.

---

### ✅ How to use these notes
- **Before class:** preview key terms; try the cloze/continuation predictions.  
- **During class:** justify each parse with **explicit cues** (bias, plausibility, distance).  
- **After class:** connect your slowdowns to **interference**, **locality**, or **surprisal** and note which lens felt most explanatory.

-->










<!--
## 📘 Overview

This week continues our exploration of discourse processing, with a special focus on how we use **inference** to connect and enrich the information conveyed across sentences. We explore key types of inferences—**bridging**, **elaborative**, and **predictive**—and the cognitive and neural mechanisms that support their generation during reading and listening.

---

## 🧠 Core Concepts

### What Are Inferences?

- Inferences are **unstated connections or conclusions** drawn by the reader to construct a **coherent mental representation**.
- Readers and listeners go beyond literal input to **fill in gaps**, **explain causal links**, and **anticipate outcomes**.

---

### Bridging Inferences (Backward)

- Needed to **maintain coherence** when connections are implicit.
- Example:
  > “The vase fell. Sarah swept up the pieces.”
  - Inference: The vase broke.
- These are **memory-based** and often automatic.

---

### Elaborative Inferences (Forward)

- Add **new, plausible information** beyond what’s stated.
- Example:
  > “The actress stepped onto the stage.” → She might perform or speak.
- These depend on **goals**, **schemas**, and **world knowledge**.
- Can be **optional** and variable across readers.

---

### Predictive Inferences

- Readers often anticipate **what will come next**.
- Example:
  > “The storm clouds gathered...” → Rain is likely.
- The **strength** of predictive inferences depends on context and individual differences.

---

### Memory and Updating

- **Situation models** are updated as new information arrives.
- Inferences can guide **activation**, **integration**, and **suppression** processes.
- Updating involves deciding whether new input **modifies**, **adds to**, or **replaces** previous info.

---

### Brain and Inference Generation

- Neuroimaging studies show:
  - **Medial prefrontal cortex** supports situation updating.
  - **Right hemisphere** often recruited for making global coherence inferences.
- Patients with brain injury often struggle with **bridging and elaborative** inference tasks:contentReference[oaicite:0]{index=0}.

---

## 📚 Reading

- Traxler (2012), Chapter 5: *Discourse Processing* (pp. 210–230)

---

## 🏷️ Key Terms

| Term | Definition |
|------|------------|
| **Inference** | A mental process of deriving unstated conclusions or connections |
| **Bridging Inference** | Inference that connects a new sentence to previous discourse |
| **Elaborative Inference** | Inference that enriches the situation model with unstated but plausible information |
| **Predictive Inference** | Expectation about upcoming content based on prior context |
| **Situation Model Updating** | The revision of mental representations as discourse unfolds |

---

## 🧪 Examples & In-Class Activities

### 🔄 Inference Generation Challenge

- Provide students with short texts missing an explicit link (e.g., cause/effect).
- Ask: “What must be true for this story to make sense?”

### 🧠 Bridging vs. Elaborative Sorting Task

- Given 10 example inferences, students classify them as **bridging**, **elaborative**, or **predictive**.

### 📖 Contextual Prediction Game

- Pause after a context sentence.
- Students write down what they think comes next.
- Compare against actual continuation and reflect.

---

## ❓ Self-Check Questions

1. What is the difference between bridging and elaborative inferences?
2. How do situation models change as we receive new input?
3. What kinds of information support predictive inferences?
4. How does the brain contribute to inference generation?
5. Can all inferences be controlled? Are they always useful?

---

## 🧩 Practice Prompt (Adapted)

> Read the sentence:  
> “The engine sputtered, and the car rolled to a stop.”  
> - What inferences can you draw about what happened?  
> - What types of inferences are these, and how do they support comprehension?

---

## 🔁 Related Chapters

- Chapter 4: *Sentence Processing* (syntactic ambiguity and interpretation)
- Chapter 6: *Reference* (linking entities across discourse)
-->