---
name: mnemonics
description: Creates memorable imagery, keywords, associations, acronyms, stories, and other memory devices from class materials. Use when the user wants help memorizing concepts, terms, sequences, definitions, or relationships.
---

# Mnemonics

## Start with clarification

Before creating mnemonics, ask the user:

1. Which file or files in `materials/` should be used?
2. What do they want to learn or remember using those materials?
3. What kinds of memory devices or associations tend to work well for them?
4. What personal interests, familiar places, or existing associations could
   make the devices more memorable?

Ask each clarification as an open-ended response question. Do not use
selectable options, multiple choice, or fixed answer buttons. Do not begin
until the source and learning target are clear.

## Strategy workflow

1. **Extract the memory targets**
   Read the selected material and list the exact facts, terms, sequences, or
   relationships the learner needs to recall. Keep each target small enough to
   test independently.
2. **Choose suitable mnemonic forms**
   Match each target to one or more useful forms:
   - vivid mental imagery for concrete facts or paired associations;
   - keyword links for unfamiliar terms and definitions;
   - acronyms or acrostics for short ordered sets;
   - a linked story for longer sequences;
   - spatial placement in a familiar location for grouped information.
   - only show me one mnemonic at a time
3. **Create candidates**
   Produce two or three concise candidates for each target. Prefer concrete,
   exaggerated, sensory, unusual, and active associations that are easy to
   reconstruct. Incorporate the learner's interests when provided.
4. **Verify accuracy**
   Check every candidate against the selected material. Reject devices that
   change the meaning, reverse an order, omit essential qualifiers, or create
   likely interference with another concept.
5. **Explain the mapping**
   Show exactly how every image, keyword, letter, place, or story beat maps to
   the source information. Clearly label the mnemonic as an added memory
   device rather than a source fact.
6. **Build and deliver the workspace**
   Create the HTML learning workspace below, then give the learner its link.
   Ask them to compare the candidates, select or personalize a favorite, and
   complete the built-in recall checks.
7. **Adapt from feedback**
   If the learner reports that a device is confusing or forgettable, revise
   the association instead of merely making it longer. End with the chosen
   mnemonic and a short spaced-review prompt.

## HTML learning workspace

Create a self-contained HTML file in `outputs/` that presents memorable
imagery, keywords, associations, and other selected memory devices. Let the
learner compare candidates, reveal mappings, and test recall.

- Use accessible, responsive HTML, CSS, and vanilla JavaScript with no external
  dependencies.
- Include clearly labeled controls to switch between memory targets, compare
  candidates, mark a favorite, reveal or hide mappings, and run recall checks.
- Keep answers hidden until the learner attempts a recall item or explicitly
  chooses to reveal it.
- Store favorites and progress in `localStorage` when available so reopening
  the file preserves the learner's work.
- Preserve meaning before memorability, and label added associations as memory
  devices rather than source facts.
- Avoid offensive or distressing imagery unless the learner explicitly asks
  for it.
- After writing the file, provide its path and, when the client supports local
  links, a clickable Markdown link. Briefly explain which controls to use.
- Do not start a server unless the learner asks for one.

## Success checklist

- [ ] The selected source material and memory target are explicit.
- [ ] Every mnemonic element has a clear and accurate mapping.
- [ ] Imagery and keywords are concrete, distinctive, and concise.
- [ ] The learner chooses or personalizes the final mnemonic.
- [ ] Retrieval is tested instead of assuming the mnemonic works.
- [ ] Added associations are clearly separated from source facts.
