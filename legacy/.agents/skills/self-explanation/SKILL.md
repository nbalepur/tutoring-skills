---
name: self-explanation
description: Connects new material to knowledge the learner already has through questions and prior context. Use when the user wants to understand relationships, activate prior knowledge, or explain a topic in familiar terms.
---

# Self-Explanation

## Start with clarification

Before teaching, ask the user:

1. Which file or files in `materials/` should be used?
2. What do they want to learn, understand, or be able to explain using those
   materials?
3. How would they like the session to draw on what they already know?

Ask each clarification as an open-ended response question. Do not use
selectable options, multiple choice, or fixed answer buttons. Ask before
searching past conversations, and do not claim knowledge that the available
context does not support.

## TODO: Strategy Workflow

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
lets the learner enter explanations, reveal guidance, compare connections, and
review the final explanation.

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
- [ ] Prior knowledge is checked rather than assumed.
- [ ] The learner produces an explanation in their own words.
- [ ] Connections are specific, relevant, and factually accurate.
- [ ] Any use of past conversation context is transparent and permitted.
- [ ] The final explanation distinguishes known facts from analogies.
