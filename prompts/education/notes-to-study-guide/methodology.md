# Design Methodology: [Prompt Name]

## Design Goal

The goal of this prompt is to help students study for tests and quizzes by creating a study guide and generating questions based on their notes.

---

## Design Approach: Structure and Technique

**Structure I used:** R-I-S-E

**Why this structure fits my task:**
- This structure allows user input.
- This structure describes the situation and what the user is looking for.

**Technique I used:** Zero-shot

**Why this technique fits my task:**
I didn't have any examples to give, so I just said what I was looking for, making a detailed zero-shot technique.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Request | Produce a study guide based on my notes. | Tells the AI what it should do. |
| Input | My notes: [NOTES] | Gives the AI data to use. |
| Scenario | These notes are for [CLASS_NAME] class and I am in [GRADE_LEVEL] grade. I am studying for [GOAL]. | Gives the AI context around the request, so it can produce relevant results. |
| Expectation | The notes should be reorganized so they are clear and concise, and then there should be 5-10 questions afterward to check understanding. | Tells the AI what the result should look like. |

---

## Testing and Iteration

**Baseline I compared against:**
```
Make a study guide for these notes. [Paste notes here]
```

| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 25 | [] |
| Version 1 | 75 | [notes] |
| Final | 100 | [notes] |

**What testing showed:** My first designed prompt was pretty clear, but it lacked the constraints and specifics on the formatting of the result, because I just used the prompt itself and didn't include the output requirements. The naive baseline prompt was very vague and didn't give any details on what the outcome should look like or what should be included. So, I kept the prompt itself the same but added the outcome requirements, and that resulted in a clear prompt that provided details on how the outcome should be.

**What I learned:** I learned the importance of not only including a clear structure, but also clearly listing the constraints and describing the expected format of the outcome. Details is key to a good prompt that produces the result you want.

---

## Strengths and Limitations

**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]
