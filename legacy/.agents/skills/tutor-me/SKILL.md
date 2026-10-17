---
name: tutor-me
description: Coordinates a tutoring session by helping the learner choose class materials and one or more study strategies. Use when the user asks to study, learn, review material, or start a guided tutoring session.
---

# Tutor Me

## Clarify the session

Ask each clarification as an open-ended response question, one at a time. Do
not use selectable options, multiple choice, or fixed answer buttons. Ask in
this order:

1. Inspect `materials/`, then ask which available file or files the learner
   wants to use. Tell them what is available and let them name any number of
   files in their own words. If the folder has no useful files, ask the learner
   to add or identify material before continuing.
2. Ask what they want to learn, understand, remember, or be able to do with
   those materials.
3. Ask how they would like to study it. Describe the available strategies as
   examples, but let them answer freely:
   - Socratic questions — follow-up questions that deepen understanding.
   - Self-explanation — connect the topic to prior knowledge.
   - Guided reading — highlights, summaries, and key information.
   - Practice testing — an interactive quiz or flashcards.
   - Mnemonics — memorable imagery, keywords, associations, or memory devices.
4. If more than one strategy is selected, ask which order they want to use.

Do not begin tutoring until the materials, learning goal, and strategies are
explicit.

## Run the session

1. For each selected strategy, read and follow its instructions:
   - Socratic questions:
     `.agents/skills/socratic-questions/SKILL.md`
   - Self-explanation: `.agents/skills/self-explanation/SKILL.md`
   - Guided reading: `.agents/skills/guided-reading/SKILL.md`
   - Practice testing: `.agents/skills/practice-testing/SKILL.md`
   - Mnemonics: `.agents/skills/mnemonics/SKILL.md`
2. Follow the selected strategies in the agreed order using only the selected
   materials.
3. Reuse answers already provided; do not repeat equivalent clarification
   questions from a strategy skill.
4. Keep source-grounded facts distinct from general knowledge or inference.
5. After each strategy, briefly check whether to continue, adjust, or stop.
6. End with:
   - what was covered;
   - what the learner demonstrated;
   - remaining gaps or uncertainties;
   - one suggested next step.

## Success checklist

- [ ] The learner explicitly selected materials and strategies.
- [ ] Multiple strategies run in the learner's chosen order.
- [ ] Each strategy follows its own skill instructions.
- [ ] The session stays grounded in the selected materials.
- [ ] The learner can adjust or stop between strategies.
- [ ] The final recap gives a clear next step.
