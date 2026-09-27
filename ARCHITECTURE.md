# Architecture and workflow

This is a conceptual explanation of responsibilities and boundaries, not a complete implementation specification or deployment guide.

```text
Writer's material and priorities
             |
             v
Source and provenance record
             |
             v
Claims, uncertainty, and causal relationships
             |
             v
Dependency assessment <---- Writer corrections and emphasis
             |
             v
One question / reflection / structural offer
             |
             v
Writer direction ----> revised working outline
```

## Responsibility boundaries

| Component | Responsibility | Must not imply |
| --- | --- | --- |
| Intake | Preserve supplied material and its origin | That every sentence is established canon |
| Claim extraction | Propose what the source explicitly supports | That an exact quotation guarantees a correct interpretation |
| Dependency assessment | Identify an important missing connection | That every ambiguity requires resolution |
| Conversation | Discover, clarify, connect, or test one issue | That the writer must complete a fixed questionnaire |
| Architecture | Compare structural arrangements and reader effects | That movements prescribe exact chapter counts |
| Review and revision | Preserve decisions and allow reconsideration | That model suggestions are author approval |

## Choosing the next question

Question selection should consider the writer's priorities, causal importance, existing answers, and whether further detail would materially change the outline. Repeated questioning of a settled or intentionally peripheral issue is a failure, not progress.

When enough material exists for the current focus, the system should offer synthesis, an outline-so-far, or structural comparison. The writer remains free to explore another area, revise an earlier decision, or stop.

## Structure as a lens

Three-act, five-act, journey-based, and other models can be considered when appropriate. Timeline presentation is a separate decision: a chronological story can be presented through a frame or a braided timeline. Comparisons should make the emotional and informational tradeoffs legible.

Close alternatives should be identified as close. A synthesis may preserve useful properties from both, without manufacturing the events needed to make it work.

## Evidence and state

The prototype separates proposed records, validation, review, and committed state. Source discovery can use paragraph identifiers and exact quotations, with deterministic offset resolution. Invalid citations can be retained separately rather than silently corrected. Unselected prose remains unresolved context, not proof of exhaustive understanding.

These mechanisms help auditability. They cannot, by themselves, detect every mistaken speaker, inferred motive, reversed action, or false causal connection. Semantic review remains necessary.

## Future interoperability

An eventual structured narrative-asset record could describe emotional significance, relationships, recurrence, payoff, and spoiler sensitivity. Any later commercialization system would assess commercial value separately. Commercial suggestions must not autonomously modify plot decisions; such feedback requires a deliberate author-approved development pass.

This is a future boundary, not a claim that those downstream agents are built or connected.
