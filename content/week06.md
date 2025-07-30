---
title: "Week 6: Sentence Processing I – Parsing and Constraints"
date: 2025-05-23T11:10:00-04:00
tags: ["sentence processing", "parsing", "two-stage models", "constraint-based models", "garden-path"]
summary: "Covers foundational theories of sentence parsing, including garden-path effects, modular vs. interactive models, and role of frequency, context, and prosody."
---

## 📘 Overview

When we read or hear a sentence, our brain rapidly organizes words into grammatical structure—a process known as **parsing**. This week introduces the classic models of how parsing works, explores **garden-path sentences**, and compares **modular (two-stage)** and **interactive (constraint-based)** approaches. We also discuss how frequency, semantics, prosody, and visual context guide real-time sentence comprehension.

---

## 🧠 Core Concepts

### What Is Parsing?

- Parsing is the **unconscious process** of assigning **syntactic structure** to incoming linguistic input.
- The parser must resolve **temporary ambiguities** and do so **incrementally**—word by word.

---

### Garden-Path Sentences

- Ambiguities lead to **misanalysis** during parsing:
  > “The horse raced past the barn fell.”  
- Requires **reanalysis**, which increases processing time.

---

### Two-Stage Models (Modular Parsing)

| Feature | Description |
|---------|-------------|
| **Syntax-first** | Parsing is guided by grammatical structure alone, before semantics or context intervene. |
| **Minimal Attachment** | Choose the parse with **fewest nodes** (simplest structure). |
| **Late Closure** | Attach new words to the **current phrase** if possible. |
| **Serial** | Only one parse is pursued at a time. Reanalysis happens when it fails. |

- Empirical support: eye-tracking shows longer fixations when initial parse fails.

---

### Constraint-Based Models (Interactive Parsing)

| Feature | Description |
|---------|-------------|
| **Multiple constraints** | Parsing is influenced by **syntax, semantics, frequency, discourse**, etc. |
| **Parallel processing** | Multiple interpretations are considered simultaneously. |
| **Probabilistic** | Readers/listeners evaluate likelihoods based on prior experience. |

- Supported by studies showing that **frequency** of verb argument structure, **story context**, and **visual scenes** can affect initial parse:contentReference[oaicite:0]{index=0}.

---

### Key Influences on Parsing

| Factor | Effect |
|--------|--------|
| **Story Context** | Helps disambiguate otherwise ambiguous sentences |
| **Verb Subcategorization Frequency** | Frequent syntactic frames are preferred |
| **Prosody** | Intonation affects syntactic grouping in spoken language |
| **Semantic Plausibility** | Meaning constraints bias interpretation |
| **Visual Context** | Real-world scenes affect syntactic interpretation (e.g., Tanenhaus et al.)

---

## 📚 Reading

- Traxler (2012), Chapter 4: *Sentence Processing* (pp. 141–166)

---

## 🏷️ Key Terms

| Term | Definition |
|------|------------|
| **Parsing** | The process of assigning syntactic structure during comprehension |
| **Garden-path Sentence** | A sentence that leads the reader to an incorrect parse |
| **Minimal Attachment** | Preference for syntactic structures with fewer nodes |
| **Late Closure** | Tendency to attach new information to the current clause |
| **Constraint-Based Parsing** | Parsing model that uses multiple sources of information simultaneously |

---

## 🧪 Examples & In-Class Activities

### 🧩 Garden-Path Sentence Game

- Present sentences like:
  > “The old man the boats.”
  > “The man whistling tunes pianos.”
- Ask students to find the ambiguity and reparse them.

### 📈 Minimal Attachment Exercise

- Students diagram sentence structures with different parses.
- Predict which one the parser would favor using two-stage rules.

### 🎬 Constraint-Based Video Clip

- Show short clips where context affects sentence interpretation.
- Relate to visual world paradigm (e.g., eye movements during parsing).

### 🔁 Reanalysis Reaction Task

- Read ambiguous sentences and note when rereading is necessary.
- Connect delays to eye-tracking evidence in parsing studies.

---

## ❓ Self-Check Questions

1. What is the difference between two-stage and constraint-based parsing models?
2. How do minimal attachment and late closure guide initial parsing?
3. What types of evidence support interactive, constraint-based parsing?
4. What makes garden-path sentences difficult to understand?
5. How do frequency and context influence syntactic ambiguity resolution?

---

## 🧩 Practice Prompt (Adapted)

> Choose one of the following sentences and explain why it is hard to parse:  
> “The cotton clothing is made of grows in Mississippi.”  
> What parsing strategy might the brain use first?  
> How would a constraint-based model help resolve it?

---

## 🔁 Related Chapters

- Chapter 3: *Word Processing* (semantic access and ambiguity)
- Chapter 5: *Discourse Processing* (beyond sentence level)
