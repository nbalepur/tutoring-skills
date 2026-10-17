# TutorMe

TutorMe uses iterative questioning, such as Socratic dialogue, to promote learning with coding agents. It brings evidence-informed educational practices into a dialogue that helps learners reason, explain, test, and apply ideas instead of passively receiving answers.

<p align="center">
  <img src="images/tutorme.png" alt="TutorMe tutoring session" width="600">
</p>

## Get started

Clone the repository and open it in an AI coding editor:

```bash
git clone https://github.com/nbalepur/tutoring-skills.git
cd tutoring-skills
```

The active skill is available for Cursor, Claude Code, and compatible agents.
Start it with:

```text
/tutorme
```

The tutor will ask you to choose source material and define what you want to
learn. It then asks one adaptive question at a time.

## Add class materials

Add lecture notes, readings, study guides, transcripts, or other source
material to `materials/`. The repository includes material from
[Python for Everybody](https://www.py4e.com/) as an example.

Good class materials should:

- focus on a coherent topic, such as one chapter or lecture;
- use Markdown, plain text, or a PDF with selectable text;
- contain concepts, definitions, examples, or problems;
- identify the source and license when appropriate;
- have clear names, such as `materials/py4e-ch05-loops.md`.

## How TutorMe teaches

TutorMe combines Socratic questioning with:

- retrieval practice before answers are shown;
- self-explanation and reasoning probes;
- adaptive scaffolding, hints, and fading;
- worked examples when productive struggle stalls;
- contrasting cases and transfer questions;
- specific feedback and misconception correction;
- an unscaffolded mastery check and spaced-review prompt.

The tutor stays grounded in the learner's selected files and separates source
facts from added explanations or analogies. It asks one main question per turn
and adapts the next question to the learner's actual response.

## Skill layout

The canonical instructions live at:

```text
.agents/skills/tutor-me/SKILL.md
```

Claude and Cursor wrappers point to that canonical file:

```text
.claude/skills/tutor-me/SKILL.md
.cursor/skills/tutor-me/SKILL.md
```

Earlier standalone strategy skills are preserved under `legacy/` for reference
but are not active entry points.

## Testing changes

Run `/tutorme` with material from `materials/` and verify that:

- the source and an observable learning goal become explicit;
- questions respond to the learner's reasoning;
- hints support discovery before direct explanation;
- misconceptions are corrected using the source;
- the learner completes a fresh application or explanation task;
- the recap records demonstrated understanding, gaps, and a next step.

## Contributors

- Nishant Balepur
- Dayeon (Zoey) Ki
- Yu (Hope) Hou
