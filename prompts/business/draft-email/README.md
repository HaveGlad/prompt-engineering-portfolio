# Draft Email

> *A prompt that writes a basic business email.*

## Overview

This prompt writes a basic business email based on the user's context and what they need accomplished. This would be useful in companies to draft emails faster.

**Best for:**
- A company employee asking a question to a coworker
- An employer sending an email to an employee
- An employee sending an email to a customer

**Structure:** R-T-F, Role-Task-Format

**Technique:** Zero-shot

**Output:** It will be formatted as a standard professional email with the following elements:
- a line addressing the recipient
- the body of the email split into paragraphs
- a closing line thanking the recipient for their time
- the name of the sender (a signature)

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
   - `[JOB_TITLE]`: The title of your job
   - `[JOB_RESPONSIBILITIES]`: What you do in your job that is relevant to your request
   - `[RECIPIENT]`: Who the email is being sent to
   - `[TOPIC]`: What the email is about, the purpose of the email
   - `[REQUEST]`: What you want to ask the recipient
   - `[SENDER]`: The name of the sender
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.

---

## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the prompt and the resulting output.

---

## Customization Tips

- **Want more detail?** Change the output requirements to add paragraphs and to add information that you need.
- **Want it shorter?** Change the output requirements to have shorter paragraphs, or remove paragraphs.
- **Different context?** Describe clearly your context in the "role" section of the structure. Otherwise, change any of the wording as long as you keep it specific.

---

## Technical Details

- **Structure:** R-T-F; Role, Task, Format
- **Technique:** Zero-shot
- **Best models:** Any models
- **Placeholders:** 6 placeholders
