# Notes to Study Guide Template

## Instructions for Use (delete this section when you build your actual prompt)

Your prompt must include:
- A short description of what it does
- Your prompt, organized into clearly labeled parts
- At least one `[PLACEHOLDER]` in square brackets and CAPS
- Output requirements so the AI knows what a good answer looks like

**Two design choices to make and note:**
- **Structure:** organize your prompt into intentional, labeled parts. Use a framework from the lesson (for example R-T-F or C-A-R-E), modify a framework, or design your own set of parts. What matters is that the structure is deliberate and every part earns its place.
- **Technique:** the prompting method you use. Zero-shot (no examples), few-shot (one or more worked examples), chain-of-thought (ask the AI to reason step by step), or zero-shot chain-of-thought (add an instruction like "Think step by step" with no examples).

You justify both choices in `methodology.md`.

---

## Overview

**Purpose:** This prompt produces a study guide that prepares the user for a test based on their notes.

**Structure:** R-I-S-E: Request, Input, Scenario, Expectation

**Technique:** Zero-shot

---

## The Prompt

Organize your prompt into labeled parts, in the order that makes sense for your task. Each label is one part of your structure. Somewhere in here, state the core task or objective clearly, since that is the part the AI most needs to get right. If your technique is few-shot, include your example(s) here; if it is chain-of-thought, include the instruction to reason step by step.

**Request:**
Produce a study guide based on my notes.

**Input:**
My notes: [NOTES]

**Scenario:**
These notes are for [CLASS_NAME] class and I am in [GRADE_LEVEL] grade. I am studying for [GOAL].

**Expectation:**
The notes should be reorganized so they are clear and concise, and then there should be 5-10 questions afterward to check understanding.

---

## Context and Inputs

List the information the user has to supply, written as placeholders:
- **[NOTES]:** Paste your notes here so the AI can use them.
- **[CLASS_NAME]:** Input the name of the class the notes are from so the AI knows the context of the class.
- **[GRADE_LEVEL]:** Input what grade you are in so the AI knows what level the class is.
- **[GOAL]:** Input what you are studying for so the AI can give you a relevant study guide.

---

## Output Requirements

**Format:** The notes provided by the user should be reorganized in clear, concise bullet points. Then, there should be 5-10 questions 
[How the answer should be structured, for example length, headings, bullets, or a table.]

**Constraints:** 
[Rules that keep the AI on scope and protect quality.]

**Tone and Style:** 
[The voice, reading level, and style you want.]

---

## Additional Instructions (optional)

Anything else the AI should keep in mind that does not fit one of the parts above. Delete this section if you do not need it.
