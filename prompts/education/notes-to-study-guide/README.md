# Notes to Study Guide

> *This prompt produces a study guide that prepares the user for an assessment based on their notes.*

## Overview

This prompt is used to help the user prepare for a test or quiz by compiling their notes into concise bullet points, then providing a list of questions for the user to answer based on the notes.

**Best for:**
- Studying for a quiz
- Practicing test questions
- Reviewing notes to retain understanding

**Structure:** R-I-S-E: Request, Input, Scenario, Expectation

**Technique:** Zero-shot

**Output:** The user's notes will be reorganized into clear, concise bullet points, then there will be 5-10 questions to quiz the user on the notes. The answers to the questions will be found at the very bottom of the output.

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
   - `[NOTES]`: Paste your notes here
   - `[CLASS_NAME]`:  Input the name of the class the notes are from
   - `[GRADE_LEVEL]`: Input what grade you are in
   - `[GOAL]`: Input what you are studying for
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.

---

## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the prompt and the resulting output.

---

## Customization Tips

- **Want more detail?** Increase the number of questions, or change how concise the reorganized notes are.
- **Want it shorter?** Decrease the number of questions.
- **Different context?** Change the scenario so it matches your specific situation.

---

## Technical Details

- **Structure:** R-I-S-E: Request, Input, Scenario, Expectation
- **Technique:** Zero-shot
- **Best models:** Any model
- **Placeholders:** 4 placeholders, one big input (your notes), four smaller inputs (details on what the notes are for)
