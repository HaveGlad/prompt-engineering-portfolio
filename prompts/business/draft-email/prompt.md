# Draft Email Template

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

**Purpose:** This prompt helps draft a basic business email.

**Structure:** R-T-F: Role, Task, Format

**Technique:** Zero-shot

---

## The Prompt

Organize your prompt into labeled parts, in the order that makes sense for your task. Each label is one part of your structure. Somewhere in here, state the core task or objective clearly, since that is the part the AI most needs to get right. If your technique is few-shot, include your example(s) here; if it is chain-of-thought, include the instruction to reason step by step.

**Role:**
Your job title is [JOB_TITLE] and your responsibilities include [JOB_RESPONSIBILITIES]

**Task:**
Write an email to [RECIPIENT] about [TOPIC] and asking [REQUEST]. Send from [SENDER].

**Format:**
The format of the email is a first line addressing the recipient, then a short paragraph (a sentence or two) explaining who you are. Then, write a paragraph about the topic and asking the request. Finish with a line thanking the recipient for their time, and then sign with the name of the sender.

---

## Context and Inputs

List the information the user has to supply, written as placeholders:
- **[JOB_TITLE]:** The title of your job, important so the AI knows what your job title is.
- **[JOB_RESPONSIBILITIES]:** What you do in your job, so the AI knows what you actually do.
- **[RECIPIENT]:** Who the email is being sent to, so the AI knows what name to put.
- **[TOPIC]:** What the email is about, so the AI can include it in the email.
- **[REQUEST]:** What you want to ask the recipient, that way the AI can incorporate it into the email and knows the purpose of the email.
- **[SENDER]:** The name of the sender, so the AI can sign the name.

---

## Output Requirements

**Format:** The email should be formatted like a typical email, so there should be a first line addressing the recipient, then a short paragraph (a sentence or two, maximum three sentences) explaining who you are. Then, write a paragraph about the topic and ask the request. Finish with a line thanking the recipient for their time, and then sign with the name of the sender.

**Constraints:** Only use the information provided by the user.

**Tone and Style:** Use a professional tone and match it to the job title.

---
