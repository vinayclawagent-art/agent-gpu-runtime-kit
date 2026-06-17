# Post-Trial Runtime Debrief Template

Status: template-ready; no runtime validation proof recorded yet.

Use this after `Remote GPU Trial Packet.md` and `Post-Trial Promotion Decision Card.md` have real evidence attached. The goal is to convert the trial into precise README, prototype, and skill-draft patches without inventing proof.

## Trial evidence bundle
- Source package: [[Agent GPU Runtime Kit]]
- Trial packet: [[Agent GPU Runtime Kit/Remote GPU Trial Packet]]
- Promotion decision card: [[Agent GPU Runtime Kit/Post-Trial Promotion Decision Card]]
- Date reviewed:
- Operator:
- Reviewer:
- Workload / repo / notebook:
- Evidence links:
  - Command transcript or Colab log:
  - Output artifact / model / dataset / screenshot:
  - Cost, quota, runtime, and teardown notes:
  - Local baseline or alternative path notes:

## Evidence-to-claim review
| Claim to update | Evidence required | Keep / soften / remove | Patch note |
|---|---|---|---|
| Remote GPU runtime is faster or more feasible than local execution | Local baseline plus Colab runtime measurement |  |  |
| Setup is agent-repeatable | Auth, install, runtime startup, teardown, and artifact download logs |  |  |
| Outputs are traceable and reusable | Artifact path, checksum/inspection, repo diff, or screenshot |  |  |
| Cost/quota risk is acceptable | Runtime duration, credit/quota notes, failure modes |  |  |
| Skill draft is ready to promote or pilot | Filled promotion card plus observed pitfalls |  |  |

## Patch decisions
- [ ] Package README needs a wording update:
- [ ] Prototype packet/card needs field changes:
- [ ] Skill draft needs pitfalls/commands added:
- [ ] Infographic needs a flow correction:
- [ ] Repo README needs status wording changed:
- [ ] Hold validation claims until another trial:

## Debrief summary for next commit
- What happened:
- What changed in the artifact:
- What remains unvalidated:
- Next operator action:

## Guardrail
If a claim does not have a log, artifact, screenshot, diff, cost note, or source link, leave it as template-ready rather than validated.
