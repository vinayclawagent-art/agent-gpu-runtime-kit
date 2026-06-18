# Trial Evidence Index

Status: template-ready, evidence pending.

Use this index during the first real Remote GPU Trial Packet run so the promotion card and runtime debrief can point at exact proof instead of vague notes.

## Trial identity

- Date:
- Operator:
- Task / repo:
- Trial packet: [[Agent GPU Runtime Kit/Remote GPU Trial Packet]]
- Promotion card: [[Agent GPU Runtime Kit/Post-Trial Promotion Decision Card]]
- Debrief template: [[Agent GPU Runtime Kit/Post-Trial Runtime Debrief Template]]

## Evidence slots

| Evidence | Required? | Link / location | Pass signal | Notes |
| --- | --- | --- | --- | --- |
| Local task brief | Yes |  | Clear objective, input files, expected artifact |  |
| Colab session/setup log | Yes |  | Runtime type, package install, auth approach, start time captured |  |
| Execution transcript | Yes |  | Command/output trace shows the job actually ran remotely |  |
| Runtime + cost notes | Yes |  | Wall-clock time, accelerator type, manual cleanup/cost risk recorded |  |
| Output artifact | Yes |  | Downloaded file/model/report/diff is linked or attached |  |
| Failure/retry notes | If any |  | Error messages and recovery steps captured before rewriting claims |  |
| Security/privacy check | Yes |  | No secrets or sensitive datasets copied into the public package |  |

## Claim-to-evidence map

| Claim to update later | Evidence required before changing it | Decision |
| --- | --- | --- |
| "Repeatable GPU handoff workflow" | At least one successful local→Colab→artifact return run | Pending |
| "Cost/runtime advantage" | Comparable local/runtime notes or explicit cost rationale | Pending |
| "Reusable Hermes skill" | Observed commands, pitfalls, cleanup steps, and failure modes | Pending |

## Handoff note

Do not mark the kit validated from this blank index. After the real trial, paste links into the rows above, then complete the promotion card and runtime debrief before patching README/prototype/skill claims.
