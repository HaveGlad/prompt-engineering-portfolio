# Design Methodology: Mock Interview

## Design Goal

This prompt helps users practice for a job interview by providing them with a mock interview experience.

---

## Design Approach: Structure and Technique

**Structure I used:** ROLE- Role, Objective, Language, Example
**Why this structure fits my task:**
- It assigns a role to the AI, since the AI needs to fit the character of an employer.
- It provides examples that show what type of questions should be asked.

**Technique I used:** Few-shot

**Why this technique fits my task:**
I used few-shot because the examples of questions helped the AI understand what kind of questions it should ask in the mock interview in order to create more relevant questions for the user, overall leading to a more useful experience for the user.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | You are an employer and you are hiring for [JOB_POSITION]. I am an applicant with [PREVIOUS_EXPERIENCE] experience and with these skills: [SKILLS]. | This assigns the AI a specific persona that interacts with the user in a certain style. |
| Objective | Ask the user mock interview questions that simulates a real job interview. | This clearly tells the AI what the purpose of the conversation is, and the goal of the experience. |
| Language | Use professional language that fits what an employer would sound like. | This helps the AI better fit the scenario and make the mock interview more relevant to the user. |
| Example | Please include the following questions and as well as similar questions: What skills are your strongest? What are your career goals? [EXAMPLE_QUESTIONS] | This directs the AI to ask the right kind of questions and know what is expected. |

---

## Testing and Iteration

Test your prompt against a naive baseline, a plain version of the same request with no deliberate structure or technique, and refine it based on what you see.

**Baseline I compared against:**
```
Produce a mock job interview for a software engineering job.
```

| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | 15 | No details, naive baseline |
| Version 1 | 90 | Used a clear structure and technique |
| Final | 95 | Filled in the placeholders |

**What testing showed:** The clean structure of the prompt and the examples helped the AI know exactly what was being asked of it and what its role was in the conversation.

**What I learned:** Clear details are key to helping the AI be able to provide the best output.

---

## Strengths and Limitations

**Works well when:** Placeholders are filled in with specific information that pertains to the interview.

**Struggles when:** Vague details are given, not enough example questions are provided.
**Would improve next:** I would make the mock interview more personalized to the user, and easier to adjust for different situations.
