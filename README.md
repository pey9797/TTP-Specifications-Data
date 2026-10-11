## XRange TTP Catalog

XRange represents agent behaviors through structured **Tactic–Technique–Procedure (TTP) catalogs** rather than describing criminal and investigative actions only as free-form prompts.

The catalog follows a three-level hierarchy:

- **Tactic** describes the high-level behavioral objective of an agent.
- **Technique** specifies the general method used to achieve that objective.
- **Procedure** defines a more concrete behavioral instance that can be selected and executed within an XRange scenario.

Each catalog entry is assigned a unique identifier and includes its behavioral definition and its relationship to the corresponding tactic, technique, or procedure.  
This structure enables agent actions to be referenced consistently across scenarios and makes it possible to trace an observed action back to the TTP specification that produced it.

XRange currently defines three TTP catalogs according to agent role:

| Catalog | Scope | Tactics | Techniques | Procedures |
|---|---|---:|---:|---:|
| **XR-P** | Shared social-media posting and interaction behaviors | 12 | 29 | 18 |
| **XR-C** | Criminal-purpose behaviors performed by adversarial agents | 16 | 37 | 41 |
| **XR-I** | Investigative actions for detection, tracing, evidence collection, and response | 8 | 32 | 21 |

### Role of TTPs in XRange

The TTP catalogs are not used only as descriptive labels.

During scenario execution, XRange agents reference the corresponding TTP definitions when selecting and performing behaviors.  
As a result, a scenario can be described not only by natural-language actions, but also by a structured sequence of TTP identifiers.

This provides a common representation for:

- specifying criminal and investigative behaviors,
- constructing repeatable adversarial scenarios,
- recording agent actions in a consistent form, and
- comparing different scenarios using the same behavioral vocabulary.

Representative TTP entries and their use in example scenarios are included in this repository.

### Availability of the Full TTP Specifications

The complete TTP catalogs are not publicly distributed in this repository because some procedure-level entries contain detailed specifications of crime-related behaviors that could be misused if released without restriction.

To support research transparency and reproducibility, the overall catalog structure, identifiers, statistics, and representative examples are publicly documented.

The complete TTP specifications can be provided to **peer reviewers and researchers upon reasonable request for academic validation and reproducibility purposes**.

For access to the full TTP catalogs, please contact:

**[Jiyoung Lee]**  
**Email:** [choh_56@daegu.ac.kr]
