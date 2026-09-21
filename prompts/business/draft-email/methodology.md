# Design Methodology: Draft Email

## Design Goal

This prompt is to write a basic business email and is aimed to be used by company employees.

---

## Design Approach: Structure and Technique

**Structure I used:** R-T-F, Role-Task-Format

**Why this structure fits my task:**
- It tells the AI the role of the user, meaning the AI can match the tone better.
- It describes the task and also explains the format of the output, which will give the desired output.

**Technique I used:** Zero-shot

**Why this technique fits my task:**
I used zero-shot because it is the most direct way to enter your expectations and then it drafts an email, especially since there isn't any examples to provide.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Your job title is [JOB_TITLE] and your responsibilities include [JOB_RESPONSIBILITIES] | The AI needs to know the context of who you are so it can write from your perspective. |
| Task | Write an email to [RECIPIENT] about [TOPIC] and asking [REQUEST]. Send from [SENDER]. | The AI needs to know why you're writing this email as well as who it's to and from so it can accurately write an email based on your situation. |
| Format | The format of the email is a first line addressing the recipient, then a short paragraph (a sentence or two) explaining who you are. Then, write a paragraph about the topic and asking the request. Finish with a line thanking the recipient for their time, and then sign with the name of the sender. | The AI needs to know what the output should look like so that it can produce the result you're expecting. |

---

## Testing and Iteration

Test your prompt against a naive baseline, a plain version of the same request with no deliberate structure or technique, and refine it based on what you see.

**Baseline I compared against:**
```
Write an email about [TOPIC].
```

| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 0 | Very basic request. |
| Version 1 | 75 | Used a specific structure and technique, as well as a lot more details. |
| Final | 90 | Filled in the placeholders with specific details. |

**What testing showed:** Version 1 was way better than the naive baseline, but I didn't fill in the placeholders so it wasn't very specific. The final version had the placeholders filled in, and as long as they are filled in with very specific details, then it will work great.

**What I learned:** I learned the importance of a clear prompt that tells AI exactly what you want it to do. I also learned the importance of details, and that AI doesn't handle vague parameters very well.

---

## Strengths and Limitations

**Works well when:** Placeholders are filled out with very specific details

**Struggles when:** Placeholders are filled out with vague parameters and not much detail.

**Would improve next:** Make the format of the email better fit the needs of the user.
