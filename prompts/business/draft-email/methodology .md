# Design Methodology: Draft Email

## Design Goal

This prompt is to write a basic business email and is aimed to be used by company employees.

---

## Design Approach: Structure and Technique

Explain the two design choices behind your prompt and why they fit the task.

**Structure I used:** R-T-F, Role-Task-Format

**Why this structure fits my task:**
- It tells the AI the role of the user, meaning the AI can match the tone better.
- It describes the task and also explains the format of the output, which will give the desired output.

**Technique I used:** Zero-shot

**Why this technique fits my task:**
I used zero-shot because it is the most direct way to enter your expectations and then it drafts an email, especially since there isn't any examples to provide.

---

## Part-by-Part Justification

Justify each part of your prompt: what it is, what goes in it, and why the prompt needs it. If your prompt is technique-driven and short (for example zero-shot chain-of-thought), justify the technique and the few parts you do have instead.

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Your job title is [JOB_TITLE] and your responsibilities include [JOB_RESPONSIBILITIES] | [Reason] |
| Task | Write an email to [RECIPIENT] about [TOPIC] and asking [REQUEST]. Send from [SENDER]. | [Reason] |
| Format | The format of the email is a first line addressing the recipient, then a short paragraph (a sentence or two) explaining who you are. Then, write a paragraph about the topic and asking the request. Finish with a line thanking the recipient for their time, and then sign with the name of the sender. | [Reason] |

---

## Testing and Iteration

Test your prompt against a naive baseline, a plain version of the same request with no deliberate structure or technique, and refine it based on what you see.

**Baseline I compared against:**
```
[Your plain, naive version of the same request]
```

| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | [result] | [notes] |
| Version 1 | [result] | [notes] |
| Final | [result] | [notes] |

**What testing showed:** [In your own words, how your designed prompt performed compared to the baseline, and what you changed as a result.]

**What I learned:** [What this taught you about prompt design.]

---

## Strengths and Limitations

**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]
