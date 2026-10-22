# Triage Labels

The skills speak in terms of five canonical triage roles. This file maps those roles to the actual label strings used in this repo's issue tracker.

| Label in mattpocock/skills | Label in our tracker | Meaning                                  |
| -------------------------- | -------------------- | ---------------------------------------- |
| `needs-triage`             | `needs-triage`       | Maintainer needs to evaluate this issue  |
| `needs-info`               | `needs-info`         | Waiting on reporter for more information |
| `ready-for-agent`          | `ready-for-agent`    | Fully specified, ready for an AFK agent  |
| `ready-for-human`          | `ready-for-human`    | Requires human implementation            |
| `wontfix`                  | `wontfix`            | Will not be actioned                     |

When a skill mentions a role (e.g. "apply the AFK-ready triage label"), use the corresponding label string from this table.

Edit the "Label in our tracker" column to match whatever vocabulary you actually use.

## Labels that exist in the tracker but are not triage roles

These are also created in the tracker and used by other skills. Do not confuse them with a triage role:

| Label         | Used by      | Meaning                                |
| ------------- | ------------ | -------------------------------------- |
| `wayfinder:map`       | `/wayfinder` | The canonical map issue                |
| `wayfinder:research`  | `/wayfinder` | Ticket resolved as research            |
| `wayfinder:prototype` | `/wayfinder` | Ticket resolved as a prototype         |
| `wayfinder:grilling`  | `/wayfinder` | Ticket resolved by grilling the idea  |
| `wayfinder:task`      | `/wayfinder` | Ticket resolved as implementation work |
