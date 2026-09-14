# Design Methodology: [Prompt Name]

## Design Goal

The goal of this prompt is to help students study for tests and quizzes by creating a study guide and generating questions based on their notes.

---

## Design Approach: Structure and Technique

Explain the two design choices behind your prompt and why they fit the task.

**Structure I used:** R-I-S-E

**Why this structure fits my task:**
- This structure allows user input.
- This structure describes the situation and what the user is looking for.

**Technique I used:** Zero-shot

**Why this technique fits my task:**
I didn't have any examples to give, so I just said what I was looking for, making a detailed zero-shot technique.

---

## Part-by-Part Justification

Justify each part of your prompt: what it is, what goes in it, and why the prompt needs it. If your prompt is technique-driven and short (for example zero-shot chain-of-thought), justify the technique and the few parts you do have instead.

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Request | Produce a study guide based on my notes. | Tells the AI what it should do. |
| Input | My notes: [NOTES] | Gives the AI data to use. |
| Scenario | These notes are for [CLASS_NAME] class and I am in [GRADE_LEVEL] grade. I am studying for [GOAL]. | Gives the AI context around the request, so it can produce relevant results. |
| Expectation | The notes should be reorganized so they are clear and concise, and then there should be 5-10 questions afterward to check understanding. | Tells the AI what the result should look like. |

---

## Testing and Iteration

Test your prompt against a naive baseline, a plain version of the same request with no deliberate structure or technique, and refine it based on what you see.

**Baseline I compared against:**
```
Make a study guide for these notes. [Paste notes here]
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
