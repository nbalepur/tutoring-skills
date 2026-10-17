---
name: socratic-questions
description: Uses Socratic follow-up questions to probe and deepen a learner's knowledge. Use when the user wants to explore why facts are true, uncover assumptions, or study through dialogue.
---

# Socratic Questions

## Start with clarification

Before teaching, ask the user:

1. Which file or files in `materials/` should be used?
2. What do they want to learn, understand, or be able to explain using those
   materials?
3. How challenging should the questions be?

Ask each clarification as an open-ended response question. Do not use
selectable options, multiple choice, or fixed answer buttons. Do not start the
exercise until the material and learning goal are clear.

## Strategy workflow

Replace these placeholders with specific instructions for the coding agent:

1. **[Insert step 1 title]**
   [Insert a description of step 1.]
2. **[Insert step 2 title]**
   [Insert a description of step 2.]
3. **[Insert step 3 title]**
   [Insert a description of step 3.]
4. **[Insert additional steps as needed]**
   [Insert descriptions for the remaining steps.]

## HTML learning workspace

Create a self-contained HTML file in `outputs/` that presents the session and
lets the learner interact with its questions, hints, answers, and recap.

- Use accessible, responsive HTML, CSS, and vanilla JavaScript with no external
  dependencies.
- Make interactive elements clearly look clickable and label what each one
  does.
- Preserve the distinction between source facts and added explanations.
- After writing the file, provide its path and, when supported, a clickable
  Markdown link. Briefly explain which controls to use.
- Do not start a server unless the learner asks for one.

## Success checklist

- [ ] The selected source material and learning goal are explicit.
- [ ] Questions require reasoning, not only recall.
- [ ] Follow-up questions respond to the learner's actual answers.
- [ ] Hints support discovery before giving away the answer.
- [ ] Misconceptions are corrected clearly and respectfully.
- [ ] The session ends with a concise learning recap.
