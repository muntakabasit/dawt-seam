# OFA RICK — LIVING CLASSROOM LESSONS 001

**Date:** 2026-11-24  
**Source lanes:** DAWT Animation Studio → Ofa Rick; DAWT Design; Uncle Sam handoff context; Ofa Jack engineering boundary  
**Standing:** LESSONS / CROSS-LANE REFERENCE — NOT A DECISION, NOT BUILD AUTHORITY  
**Execution status:** PREFLIGHT ONLY  
**Privacy note:** Recruitment administration and other personal case details are intentionally excluded. This record preserves product, design, learning and engineering lessons only.

## Why this exists

This packet preserves the material lessons that emerged while shaping Ofa Rick's Educate Yourself Centre / Living Classroom so future workers do not have to reconstruct the reasoning from chat.

Consulting this file transfers no authority. It does not release any HOLD, dispatch Claude, activate Ofa Rick's older persona/runtime, or authorise application code.

---

## Lesson 1 — Build the teacher, not another quiz site

The target experience is not a question-and-answer website with an AI chat box attached.

The classroom should help the learner:

1. understand what a task is asking,
2. see the underlying relationship,
3. practise it,
4. demonstrate it independently,
5. transfer the skill to an external assessment or real problem.

**Keeper:**  
> Ofa Rick succeeds when the learner becomes less dependent on Rick.

---

## Lesson 2 — Assessment reference and teaching system are different things

For Army Readiness, the official Mindmill practice environment is the primary assessment reference.

Its role is to show **what the learner must be able to do**.

Ofa Rick's role is to teach **how to develop that ability**.

Therefore:

- do not clone Mindmill's interface;
- do not copy proprietary questions or question banks;
- do not call Ofa Rick scores official Army scores;
- independently author exercises that reproduce the underlying skill and task mechanics;
- return to the official reference environment to test transfer.

**Keeper:**  
> Assessment specification is not teaching specification.

---

## Lesson 3 — Use a complete learning cycle

The intended cycle is:

```text
DISCOVER
What is this capability and why does it matter?

LEARN
Rick demonstrates the underlying reasoning.

PRACTISE
The learner attempts original progressively challenging examples with feedback.

ASSESS
The learner works independently, with timing and accuracy measured.

TRANSFER
Return to the external reference or real-world context and test whether the skill improved.
```

The Transfer stage is important because Ofa Rick must not grade its own success in isolation.

---

## Lesson 4 — Learn, Practice and Assess need different assistance rules

Teaching and independent assessment are not the same interaction state.

### Learn / Practice

Rick may:

- explain;
- point;
- highlight;
- animate relationships;
- answer questions;
- replay an explanation;
- adapt the explanation;
- offer feedback.

### Assess

Rick must not:

- reveal an answer;
- speak clues;
- visually expose the solution;
- change the task to make it easier;
- provide assistance that invalidates independence.

**Keeper:**  
> Assistance must disappear when independent competence is being measured.

---

## Lesson 5 — Voice is central, but "voice enabled" is not a sufficient requirement

Voice is not a chatbot bolted onto a lesson.

Rick should behave like a teacher who can:

- speak;
- listen;
- tolerate a pause;
- indicate that a question is being processed;
- coordinate speech with what is being shown;
- be interrupted;
- replay;
- yield control;
- stay quiet while the learner thinks.

The intended turn model is:

```text
READY
Nothing records or plays automatically.

LISTENING
The learner deliberately gives Rick the floor to listen.

THINKING
The system truthfully indicates processing.

EXPLAINING
Speech and visual explanation refer to the same object or relationship.

YOUR TURN
Rick stops. The exercise becomes primary.
```

**Keeper:**  
> Rick must know when to speak, when to listen, when to explain, and when to disappear.

---

## Lesson 6 — Acoustic Turn Ownership is a learning mechanism

Voice-state signalling is not decorative.

The learner should not have to guess:

- whether the microphone is active;
- whether Rick is listening;
- whether Rick has understood;
- whether Rick is still processing;
- whether Rick is speaking;
- whether the turn has returned to the learner.

Truthful turn ownership reduces cognitive load and protects attention.

No automatic recording or playback should be implied by visual polish.

---

## Lesson 7 — Explain in Place

The strongest visual direction is to move explanation into the material being learned.

Avoid:

```text
DIAGRAM
↓
LONG PARAGRAPH ABOUT THE DIAGRAM
```

Prefer:

```text
THE ACTUAL OBJECT / RELATIONSHIP
↓
Rick points to the exact thing
↓
highlight / path / grouping / transformation reveals the relationship
↓
Rick explains briefly
↓
guidance disappears
↓
learner attempts
```

Reusable primitives can include:

- arrows;
- paths;
- highlights;
- grouping;
- geometric transformations;
- annotations;
- object comparison;
- spatial manipulation.

Animation must remain subordinate to understanding.

---

## Lesson 8 — DAWT Animation intentions can become teaching behaviour

Existing animation research can be translated into learning functions:

- **HOLD** — give the learner time to understand;
- **GATHER** — bring numbers, shapes or relationships together;
- **INTERRUPT** — reveal a mistake without breaking concentration unnecessarily;
- **TRANSFER** — connect an abstract idea to a concrete or real-world example;
- **YIELD** — Rick stops teaching and lets the learner attempt;
- **RETURN** — recover the exact useful learning position;
- **Explain in Place** — teach directly on the object;
- **Learning Gems** — concise memorable visual explanations;
- **Character acting** — personality through timing and expression without requiring expensive continuous generative video.

These are creative intentions, not a requirement to animate everything.

---

## Lesson 9 — One environment, different perceptual states

The Educate Yourself Centre should not behave like one static dashboard.

The same environment can become different surfaces depending on the learner's activity:

- reading → calm reading surface;
- reasoning → visual working surface;
- practising → distraction-minimised exercise surface;
- talking to Rick → conversational teaching surface;
- assessing → quiet independent surface.

**Keeper:**  
> One environment, different perceptual states.

---

## Lesson 10 — Measure learning, not interface polish

DAWT Design's responsibility is not merely to certify typography, colour and animation quality.

The Yard of Excellence must ask whether the full encounter makes the learner more capable.

A useful acceptance encounter is:

```text
ENTER
↓
understand where you are
↓
hear Rick
↓
interrupt Rick
↓
see the exact relationship he is describing
↓
ask a question
↓
receive a better explanation
↓
Rick yields
↓
solve an unfamiliar problem independently
↓
leave
↓
return to the correct useful position
```

Also validate:

- readable typography;
- keyboard access;
- reduced-motion mode;
- quiet / no-speech path;
- truthful microphone state;
- ability to complete the experience without voice;
- sensory harmony;
- learning continuity.

**Keeper:**  
> Excellence is not the presence of STT + TTS + animation + persistence. It is the quality of the relationship between them.

---

## Lesson 11 — A real-world relationship should become visible

The teaching standard is higher than getting the answer right.

A strong Ofa Rick explanation should help the learner notice a relationship they did not previously recognise, then increasingly recognise it without assistance.

Example pattern:

```text
surface difference
↓
why the difference matters
↓
visual relationship becomes legible
↓
learner practises recognition
↓
guidance disappears
↓
learner transfers recognition independently
```

This is the distinction between a learning environment and a test simulator.

---

## Lesson 12 — Deterministic machinery should carry established operations

The system should not depend on a language model for everything.

Prefer ordinary software where the operation is defined:

- arithmetic exercise generation → deterministic code;
- answer validation → deterministic code;
- spatial rotation → SVG / Canvas;
- diagram animation → reusable motion components;
- timing → local timers;
- progress → local persistent state;
- repeatable explanations → cached content / audio;
- accessibility state → deterministic interface logic.

Use intelligence where it adds genuine educational value:

- explaining an unexpected misunderstanding;
- adapting an explanation;
- answering unfamiliar questions;
- producing new lesson material with validation.

**Keeper:**  
> Claude can manufacture capabilities; Claude should not become the permanent runtime for every classroom action.

---

## Lesson 13 — Local-first efficiency is part of the product quality

The classroom should reuse existing local mechanisms before creating replacements.

Important engineering principles:

- recover before rebuilding;
- cache stable outputs;
- avoid duplicate services;
- avoid unnecessary model calls;
- avoid continuous generative video;
- avoid heavy dependencies without demonstrated need;
- inspect machine capacity before activating resource-intensive workloads;
- do not sacrifice protected existing services to make Rick appear more sophisticated.

Computational efficiency is not separate from experience quality. Slow, fragile or resource-hungry teaching is poor teaching infrastructure.

---

## Lesson 14 — Protect existing learning material before building

The existing learning journey is part of the product foundation, not disposable prototype content.

Before implementation:

- establish the canonical Ofa Rick source;
- locate Classroom V1.1 if it exists in the inspected scope;
- locate University Resource Integration V1 if it exists in the inspected scope;
- locate and fingerprint the Week 01 workbook;
- locate directly related course, assessment and progress material;
- do not recreate missing components merely because they are not immediately found.

Use precise status language:

```text
FOUND
ABSENT IN INSPECTED SCOPE
UNVERIFIED
BLOCKED
```

Never convert "not found here" into universal absence.

---

## Lesson 15 — Reality preflight before implementation

A material mismatch between a brief and filesystem reality is a reason to stop implementation and inspect reality.

The bounded preflight should establish:

1. canonical project root, branch, revision and governing decision;
2. protected learning material and fingerprints;
3. existing animation and voice capabilities;
4. source present vs tested vs operational;
5. actual worker instance and environment;
6. permitted workspace;
7. relevant service and resource state;
8. authentication state without attempting sign-in;
9. one smallest viable implementation slice.

No application code, installations, commits, restarts or protected-system changes during this preflight.

**Current execution standing:** PREFLIGHT ONLY.

---

## Lesson 16 — Presence, tested and operational are different claims

For every reusable capability, record separately:

```text
SOURCE PRESENT
Do we have the implementation?

TESTED
Has its claimed behaviour been exercised?

OPERATIONAL
Is the required runtime/service currently usable in the target environment?
```

Do not collapse those three states into "available."

This matters especially for:

- voice input;
- voice output;
- interruption / barge-in;
- animation primitives;
- persistence;
- local models;
- audio services.

---

## Lesson 17 — The fractions instrument and Living Classroom are different proofs

The proposed fractions teaching instrument is intentionally smaller than the complete classroom.

A later fractions slice may prove:

- deterministic visual explanation;
- interaction correctness;
- accessibility;
- learning-state mechanics.

It may remain voice-free.

That does not weaken the voice requirement for the complete Living Classroom.

**Keeper:**  
> A bounded proof should prove exactly what it claims, not pretend to be the finished classroom.

---

## Lesson 18 — Suggested implementation sequence remains staged

No build is authorised by this lesson record.

The current staged model is:

```text
STEP 1
OFA RICK REALITY PREFLIGHT 001
read-only foundation discovery

STEP 2
FRACTIONS TEACHING INSTRUMENT
later separately authorised deterministic visual proof

STEP 3
LIVING CLASSROOM
only after source baseline, learning content, voice capability
and acceptance requirements are reconciled

STEP 4
YARD OF EXCELLENCE
observe one complete human learning encounter
```

This sequence is a lesson from the current work, not a new execution decision.

---

## Lesson 19 — Preserve responsibility boundaries

Current responsibility separation:

- **Ofa Rick** — teaching, practice, assessment, learning progress;
- **DAWT Animation Studio** — animation and visual teaching mechanisms;
- **DAWT Design** — perceptual quality and Yard of Excellence judgement;
- **Quiet Reader** — possible calm reading/listening patterns;
- **Maya / relevant voice mechanisms** — potential reusable spoken interaction machinery;
- **Uncle Sam** — administrative commitments and readiness, not teaching;
- **Ofa Jack** — governed engineering execution and validation;
- **Belawu** — continuity, crossings and authority.

Do not merge repositories or activate every subsystem merely because their lessons are useful.

---

## Lesson 20 — Recovering material does not release an old runtime HOLD

The older Ofa Rick persona/runtime HOLD remains separate.

Finding old source, lessons, content or voice mechanisms is not permission to resurrect or activate that runtime.

Recovery ≠ activation.

---

## Lesson 21 — Design like a disciplined listener

A broader DAWT lesson applies here too:

Do not ask the learner to design the teaching system.

Listen to how they describe:

- what they thought the problem meant;
- where they became confused;
- what relation they failed to notice;
- how they tried to solve it;
- what changed when an explanation worked.

Useful pattern:

```text
STORY / ATTEMPT
↓
EXPERIENCE
↓
FRICTION
↓
UNDERLYING LEARNING NEED
↓
TEACHING INTERVENTION
↓
INDEPENDENT RETRY
```

Do not over-psychologise the learner. Use their experience to reveal practical learning needs.

---

## Yard of Excellence keeper

> When Rick teaches something, the learner should come away seeing a real-world relationship they did not previously recognise — and become increasingly able to recognise it without him.

---

## Governance / custody

This file is a cross-lane lesson surface only.

It does **not**:

- dispatch Claude;
- authorise code;
- release PREFLIGHT ONLY;
- choose a canonical repo;
- claim Classroom V1.1 is present or absent;
- claim voice services are operational;
- modify Ofa Rick;
- change Ofa Jack focus;
- alter Uncle Sam;
- activate the old Ofa Rick persona/runtime;
- establish Mindmill content as reusable copyrighted training content;
- replace the owning project's eventual canonical lesson/spec files.

Admission and implementation remain separate.
