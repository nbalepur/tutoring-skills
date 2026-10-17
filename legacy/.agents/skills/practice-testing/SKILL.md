---
name: practice-testing
description: Generates quizzes or flashcards from class materials and provides feedback on answers. Use when the user wants retrieval practice, a knowledge check, flashcards, or an interactive quiz.
---

# Practice Testing

## Start with clarification

Before generating questions, ask the user:

1. Which file or files in `materials/` should be used?
2. What do they want to learn, remember, or be able to do using those
   materials?
3. How would they like to practice or test themselves?
4. What level of challenge and session length would be useful?

Ask each clarification as an open-ended response question. Do not use
selectable options, multiple choice, or fixed answer buttons. Do not begin
until the source, learning goal, format, and difficulty are clear.

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

Create a self-contained HTML file in `outputs/` that lets the learner answer
quiz or flashcard prompts, reveal feedback, track progress, and review missed
concepts.

- Use accessible, responsive HTML, CSS, and vanilla JavaScript with no external
  dependencies.
- Make interactive elements clearly look clickable and label what each one
  does.
- Do not reveal an interactive item's answer before the learner attempts it.
- After writing the file, provide its path and, when supported, a clickable
  Markdown link. Briefly explain which controls to use.
- Do not start a server unless the learner asks for one.

## Success checklist

- [ ] The selected source, scope, format, and difficulty are explicit.
- [ ] Questions can be answered from the selected material.
- [ ] Questions assess important concepts rather than trivia.
- [ ] Answers are not revealed before the learner attempts interactive items.
- [ ] Feedback explains the reasoning behind each answer.
- [ ] Missed concepts receive additional retrieval practice.
