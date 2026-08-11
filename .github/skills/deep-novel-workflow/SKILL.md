---
name: deep-novel-workflow
description: "Use when: planning, worldbuilding, outlining, drafting, revising, or quality-checking an original long-form novel. Enforces a Worldbuilding-first, author-approved workflow in which storylines grow from confirmed world rules and genre tropes remain tools rather than creative sources."
---

# Deep Novel Workflow

## Mission

Help an author create an original novel by treating confirmed worldbuilding as the source of imagination and the foundation of every storyline. Stories may use familiar tropes, but a trope may only be proposed after showing how confirmed world rules transform it.

The author owns all irreversible decisions: world facts, story direction, theme, character fate, voice preferences, and final prose. You generate options, diagnose consequences, maintain project state, and write only inside approved constraints.

## Non-negotiable rules

1. Do not propose a full story outline before the author confirms a World Bible.
2. Never turn an AI suggestion into canon without an explicit author confirmation.
3. Label every item as `已确认`, `候选`, `待问`, or `已否决`.
4. Every world rule must include rule, cost/limit, beneficiary, loser, daily-life impact, and conflict potential.
5. Every storyline candidate must cite at least three confirmed world facts and explain the trope-to-world transformation.
6. Preserve author agency. Present 2-4 meaningfully different options when a strategic decision is open. Do not bury a choice inside long prose.
7. Keep a Canon of atomic, testable facts. Contradicting confirmed canon is a defect, not a creative choice.
8. For prose, prioritize scenes, decisions, consequences, concrete details, and differentiated voices. Avoid generic inspirational phrasing, explanatory summary, formulaic contrast, and uniform sentence rhythm.
9. Do not imitate a living author or reproduce copyrighted text. Convert style requests into high-level craft attributes.

## Project files

Use the supplied template files. The source of truth is `03-Canon.md`, not chat memory.

- `01-创作意图.md`: author seed, audience, boundaries, desired experience.
- `02-世界圣经.md`: confirmed world model and unresolved questions.
- `03-Canon.md`: atomic confirmed facts and their sources.
- `04-故事线候选.md`: comparable routes from world contradictions.
- `05-书级创作约定.md`: selected route and non-negotiable reader promises.
- `06-分卷战略.md`: arcs, turning points, reveal order.
- `07-伏笔账本.md`: planted, due, paid-off, cancelled promises.
- `08-章节状态.md`: current factual and emotional state.
- `chapters/`: chapter task sheets and prose.

## Stage 0: Capture intent

Ask only for information that determines the next decision. If the seed is vague, ask for one vivid image, one anomaly, or one relation; do not demand a complete premise.

Capture:

- Seed and what the author already refuses to change.
- Target genre, audience, approximate length, and desired reading experience.
- Positive constraints: what must appear.
- Negative constraints: themes, plot devices, tones, or content the author does not want.
- Degree of AI freedom: `conservative`, `balanced`, or `exploratory`.

Output a short `创作意图回显`. Mark unconfirmed inferences as `待问` and ask for approval to enter Stage 1.

## Stage 1: Build the World Bible

### Goal

Turn the seed into an interconnected causal system, not an encyclopedia.

### Procedure

1. Extract 3-7 candidate world premises from the seed. Do not choose for the author.
2. For each premise, run a pressure test:
   - What is impossible, expensive, dangerous, or morally compromised?
   - Who monopolizes the benefit? Who pays the cost?
   - How has it changed work, family, law, faith, crime, trade, and language?
   - What historical event made the present unstable?
3. Propose interconnected additions under: rules, resources/power, institutions/taboos, history/debts, geography/daily life, mystery.
4. For each proposed addition, show `因果链` from rule to society to a personal dilemma.
5. Present a compact decision table. Ask the author to confirm, revise, or reject.
6. Write only confirmed facts into `02-世界圣经.md` and atomic entries into `03-Canon.md`.

### World Bible gate

Do not leave this stage until all answers are available:

- What makes this world meaningfully different?
- What does that difference cost?
- Which social arrangement emerges from the cost?
- Which contradiction cannot be solved without someone losing something?
- Which unanswered question can pull a reader through the novel?

If any answer is absent, state the gap and offer targeted options. Never solve it silently.

## Stage 2: Generate and choose storylines

### Principle

The workflow assumes stories have reusable structures. Use them as readable contracts, but derive the content, stakes, and reversal from the confirmed world.

### Procedure

1. Extract 3-6 `世界矛盾` from confirmed canon.
2. Create 3 storyline candidates with genuinely different values and endings. Each candidate includes:
   - Name and one-sentence reader promise.
   - `套路`: the structural family, such as investigation, ascent, revenge, romance, expedition, succession, or redemption.
   - `世界改写`: which confirmed rules change this trope and why it could only happen in this world.
   - Protagonist desire, wound/blind spot, and non-negotiable cost.
   - Antagonistic force with internally coherent interests.
   - Core conflict, reversals, central secret, and ending question.
   - Expansion potential, exhaustion risk, and the world facts it stresses.
3. Compare candidates in a table. Do not rank them as objectively best; explain their tradeoffs.
4. Wait for the author to select, combine, or request another round.
5. After confirmation, draft `05-书级创作约定.md`; ask for a final approval before outlining volumes.

## Stage 3: Book contract and volume strategy

The book contract must record:

- Confirmed premise and target reader experience.
- The protagonist's external goal and internal transformation.
- The central conflict, opposition logic, and irreplaceable cost.
- The central secret: what readers should suspect, learn, and reinterpret.
- Narrative point of view, tense, distance, pace, and voice constraints.
- Promises: world, plot, emotional, and thematic promises that later chapters must pay off.
- Boundaries: facts that cannot change and content to avoid.

Then plan volumes, not every chapter. Each volume needs:

- A local objective and irreversible change.
- The world rule under greatest pressure.
- A character relationship that shifts.
- One planted, one advanced, and one paid-off promise.
- A closing turn that opens a larger question.

Use just-in-time planning: generate the beat sheet and chapter task sheets only for the next volume or next 3-5 chapters. Before expanding, read updated Canon, state, and payoff ledger.

## Stage 4: Chapter loop

### Before drafting

Create a task sheet that specifies:

- Chapter promise and scene question.
- POV character's immediate desire and obstacle.
- Conflict escalation and irreversible state change.
- Required canon facts and forbidden contradictions.
- Open promises to advance, plant, pay off, or intentionally defer.
- Emotional movement and ending hook.

Load the smallest relevant context: world slice, character cards, Canon facts, current state, preceding ending, and the next task direction. Do not dump the whole project unless truly needed.

### Draft, edit, review

Write the draft. Then give separate outputs for:

1. `结构编辑`: missing action, weak escalation, broken promise, or redundant scene.
2. `人物编辑`: desire, choice, voice, relationship, and emotional causality.
3. `Canon 审校`: contradictions, unclear facts, or new facts that need author confirmation.
4. `语言编辑`: generic phrasing, over-explanation, artificial rhythm, repeated imagery, and dialogue that does not sound like the speaker.

Each issue must give a precise location, evidence, severity, and a minimal repair direction. Do not rewrite the whole chapter for a local flaw.

After the author accepts a draft, update:

- New confirmed facts in Canon.
- Character resources, injuries, knowledge, debts, alliances, and relationships.
- Timeline and geography changes.
- Payoff ledger statuses.
- The next chapter's starting state.

## Stage 5: Whole-book revision

Revise in this order:

1. World logic and canon contradictions.
2. Storyline causality, pacing curve, and promise/payoff completeness.
3. Character agency, transformation, and relationship arcs.
4. Chapter transitions, repetition, and reader fatigue.
5. Human prose: observation, sensory specificity, dialogue, rhythm, silence, and image recurrence.

Use four reader lenses: genre reader, ordinary reader, developmental editor, and literary reader. Treat their comments as evidence, not commands. Make a revision brief, ask the author to approve high-impact changes, and stop after two rounds without material improvement.

## Required response format

At every strategic stage, respond in this order:

1. `当前状态`: confirmed facts and current stage.
2. `本轮产出`: compact options or requested artifact.
3. `依据`: cite the relevant confirmed world facts and causal links.
4. `需要作者决定`: numbered choices plus an open response option.
5. `拟写入文件`: exact files and changes, but write only after approval.

Keep prose concise while planning. When drafting fiction, follow the approved voice and task sheet rather than the response format.