# Post-Trial Promotion Decision Card

Status: template-ready; no validation proof recorded yet.

Use this only after the first real trial packet has been filled with evidence. Do not promote the kit, patch the skill draft, or claim validation from memory.

## Trial identity
- Source package: [[Agent GPU Runtime Kit]]
- Trial packet: [[Agent GPU Runtime Kit/Remote GPU Trial Packet]]
- Date completed:
- Operator:
- Reviewer:
- Workflow / repo / surface:
- Evidence bundle links: 
  - Logs/transcript:
  - Output artifact/diff/screenshot:
  - Cost/runtime/friction notes:

## Evidence-backed review
| Gate | Question | Evidence link | Decision note |
|---|---|---|---|
| Runtime value | Did the remote GPU make the task meaningfully faster, cheaper, or more feasible than the local baseline? |  |  |
| Artifact integrity | Was the output artifact downloaded, checksummed or inspected, and linked back to the command/log evidence? |  |  |
| Setup friction | Were dependency installs, authentication, runtime startup, and teardown low-friction enough for repeated agent use? |  |  |
| Cost / quota risk | Were credits, runtime limits, or session instability acceptable for the intended workflow? |  |  |
| Skill readiness | Are the observed pitfalls specific enough to patch the skill draft without guessing? |  |  |

## Promotion decision
Choose exactly one after evidence review:

- [ ] **Promote** — Promote remote GPU runtime for repeated agent jobs.
- [ ] **Pilot-only** — Pilot-only for expensive or accelerator-only jobs.
- [ ] **Iterate** — Iterate setup before reuse.
- [ ] **Hold** — Hold; local or managed GPU path is safer.

Decision owner:
Decision date:
Rationale, with evidence links:

## Patch queue if promoted or iterated
- [ ] Package README wording to update:
- [ ] Prototype packet/card changes to make:
- [ ] Skill draft pitfalls to add:
- [ ] Infographic/spec adjustments:
- [ ] Follow-up trial needed:

## Guardrail
Every claim above needs a packet/log/issue/screenshot/diff/source link. Leave fields blank instead of inventing validation proof.
