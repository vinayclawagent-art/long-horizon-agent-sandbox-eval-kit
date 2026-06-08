# Sandbox Trial Evidence Packet

Status: ready for next real trial — not validation-complete.

Use this packet immediately after running `agent-sandbox-eval-builder.html` on one real Antigravity/Codex/Hermes sandbox task. Leave unknown fields blank instead of inferring outcomes.

## 1. Trial identity

- Date:
- Operator:
- Agent/runtime tested:
- Repo or task:
- Source issue/spec/paper link:
- Trial branch or workspace:
- Timebox:
- Budget / compute cap:

## 2. Task class

Select one primary class:

- [ ] Repo resurrection / dependency repair
- [ ] Paper-to-code implementation
- [ ] Infra orchestration / cloud GPU selection
- [ ] Multi-step feature implementation
- [ ] Regression triage / test repair
- [ ] Other:

## 3. Guardrails set before run

- Allowed paths:
- Blocked paths:
- Secret / credential restrictions:
- Max diff size:
- Required tests or verification command:
- Required log location:
- Human checkpoint rule:

## 4. Evidence attachments

Attach source-backed proof only.

- Agent transcript/log path or URL:
- Commit SHA or diff artifact:
- Test output path:
- Cost / token / compute estimate:
- Failure-mode notes:
- Human interventions made:

## 5. Builder score snapshot

Copy the final markdown handoff from `agent-sandbox-eval-builder.html` here.

```markdown
[paste builder output]
```

## 6. Failure-mode triage

| Failure mode | Observed? | Evidence link | Fix before next trial |
| --- | --- | --- | --- |
| Setup drift |  |  |  |
| Missing context |  |  |  |
| Unsafe file edit |  |  |  |
| Verification skipped |  |  |  |
| Cost/time exceeded |  |  |  |
| Human takeover needed |  |  |  |

## 7. Decision gate

Choose exactly one after evidence is attached:

- [ ] **Promote** — repeatable enough for a documented workflow/skill.
- [ ] **Pilot-only** — useful for constrained tasks but needs supervision.
- [ ] **Iterate** — update prompt, harness, or scoring before another trial.
- [ ] **Hold** — evidence does not justify more use yet.

Decision rationale:

## 8. Next artifact update

- [ ] Update package change log with evidence-backed result.
- [ ] Update skill draft if the procedure changed.
- [ ] Add a worked example only if the trial produced source-backed proof.
- [ ] Keep package wording evidence-ready if the trial was incomplete.
