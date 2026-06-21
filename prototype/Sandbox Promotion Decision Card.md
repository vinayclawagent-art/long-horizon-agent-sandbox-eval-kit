# Sandbox Promotion Decision Card

Use this card after the next real long-horizon sandbox trial, evidence packet, post-trial debrief, and evidence-quality rubric are complete. It converts proof into a narrow promote / pilot-only / iterate / hold decision without upgrading claims from template existence alone.

## Trial reference

- Trial date:
- Operator:
- Source task / repo / paper / infra target:
- Evidence packet: [[Sandbox Trial Evidence Packet]]
- Post-trial debrief: [[Post-Trial Debrief Template]]
- Evidence rubric: [[Sandbox Evidence Quality Rubric]]

## Minimum proof required before any promotion

- [ ] Full command/log trail is attached or linked.
- [ ] Final commit, artifact, or failed stopping point is reproducible from the evidence.
- [ ] Human interventions are counted, not hidden.
- [ ] Cost, runtime, environment, and cloud/GPU choices are recorded.
- [ ] At least one failure mode is preserved with the recovery decision.
- [ ] Rubric score and notes are filled before editing README/prototype/skill claims.

## Decision gate

Choose exactly one:

- [ ] **Promote to reusable skill** — evidence shows repeatable setup/debug/verification autonomy on a real sandbox task, and the skill draft can name concrete triggers, commands, pitfalls, and verification steps.
- [ ] **Pilot-only** — useful for VinClawLabs/Mission Control, but evidence is too narrow for a general Hermes skill.
- [ ] **Iterate** — artifact structure helped, but the trial exposed missing fields, weak scoring, or unclear handoff steps.
- [ ] **Hold** — evidence is incomplete, non-reproducible, or mostly template-level.

## Evidence-to-claim map

| Proposed claim | Evidence link | Rubric note | Allowed wording now | Patch target |
| --- | --- | --- | --- | --- |
| Agent can recover a finicky repo with bounded help |  |  |  | README / skill draft |
| Agent can translate source material into runnable code |  |  |  | prototype / skill draft |
| Agent can make inspectable infra/GPU/runtime decisions |  |  |  | README / infographic |
| Workflow is reusable across another sandbox task |  |  |  | installed skill decision |

## Patch queue

- README claim changes:
- Prototype changes:
- Skill draft changes:
- Infographic/spec changes:
- Next trial needed:

## Decision owner sign-off

- Decision:
- Why this decision is justified by evidence:
- Claims explicitly not made yet:
- Next review date:
