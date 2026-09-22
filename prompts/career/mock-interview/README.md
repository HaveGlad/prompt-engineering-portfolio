# Mock Interview

> *This prompt gives the user a mock interview experience.*

## Overview

This prompt produces a mock interview scenario that helps the user prepare for a real job interview.

**Best for:**
- Practicing for a job interview.
- Preparing for answering interview questions.
- Preparing for a scholarship interview.

**Structure:** ROLE- Role, Objective, Language, Example

**Technique:** Few-shot

**Output:** A series of questions asked one at a time, general feedback at the end of the questions.

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
   - `[JOB_POSITION]`: Input what job position you are interviewing for.
   - `[PREVIOUS_EXPERIENCE]`: Describe your previous experience in any job, preferably a job in the field you are applying for.
   -  `[SKILLS]`: List your skills related to the job.
   - `[EXAMPLE_QUESTIONS]`: Questions the user expects to be asked.
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.

---

## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the prompt and the resulting output.

---

## Customization Tips

- **Want more detail?** Increase the number of interview questions, or change the output requirements of the final summary.
- **Want it shorter?** Decrease the number of interview questions.
- **Different context?** Change the role or the objective.
---

## Technical Details

- **Structure:** ROLE- Role, Objective, Language, Example
- **Technique:** Few-shot
- **Best models:** Any models
- **Placeholders:** 4 placeholders
