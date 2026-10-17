---
name: guided-reading
description: Turns long class materials into structured highlights, summaries, and key takeaways. Use when the user wants to consume a long reading, identify important information, or create concise study notes.
---

# Guided Reading

## Start with clarification

Before processing the text, ask the user:

1. Which file or files in `materials/` should be used?
2. What do they want to learn, understand, or take away from those materials?
3. What kind of reading aid or result would be most useful to them?
4. How detailed should the result be?

Ask each clarification as an open-ended response question. Do not use
selectable options, multiple choice, or fixed answer buttons. Do not summarize
until the material, learning goal, and output format are clear.

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

Create a self-contained HTML file in `outputs/` that presents the reading with
clickable navigation, highlights, summaries, key terms, and source references
appropriate to the requested format.

- Use accessible, responsive HTML, CSS, and vanilla JavaScript with no external
  dependencies.
- Make interactive elements clearly look clickable and label what each one
  does.
- Preserve the distinction between source facts and added interpretations.
- After writing the file, provide its path and, when supported, a clickable
  Markdown link. Briefly explain which controls to use.
- Do not start a server unless the learner asks for one.

## Success checklist

- [ ] The selected source material and desired output are explicit.
- [ ] The result preserves the source's meaning and important qualifications.
- [ ] Key information is prioritized over merely interesting detail.
- [ ] Highlights are traceable to locations in the source when possible.
- [ ] Interpretations are not presented as direct claims from the source.
- [ ] The output is substantially easier to review than the original material.
