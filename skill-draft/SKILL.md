---
name: long-horizon-agent-sandbox-evals
description: "Reusable procedure for evaluating long-horizon coding agents on repo resurrection, paper-to-code, and infra orchestration tasks."
status: draft
source_note: "[[Antigravity CLI as a Long-Horizon Agent Sandbox]]"
---

# long-horizon-agent-sandbox-evals

## Trigger
Use when a future task matches this source-backed workflow: The tweet turns a tool launch into a concrete benchmark pattern: can an agent resurrect finicky repos, adapt compute constraints, read papers, implement training, and choose cloud GPUs without hand-holding?

## Procedure
1. Define the bounded job and the artifact that proves completion.
2. List required tools, data access, constraints, and safety boundaries.
3. Run or delegate the job only when the human explicitly asks for execution.
4. Capture evidence: commands, links, screenshots, cost/time, failure modes, and verification output.
5. End with a decision: promote, iterate once, hold, or retire.

## Pitfalls
- Do not confuse a polished plan with a validated workflow.
- Do not execute installs or third-party tools just because a tweet mentioned them.
- Preserve source links and evidence paths so the artifact remains auditable.

## Verification
- A real trial has a filled evidence packet.
- The output artifact is inspectable by someone who did not run the task.
- The decision block names the next action and owner.
