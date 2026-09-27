# Plot Designer — Causal Architect

A conversational story-development assistant that helps writers understand their own stories, rather than writing those stories for them.

**Public design showcase — not a runnable application or a production release.** This repository intentionally contains only curated documentation and a synthetic example. The implementation and private development workspace are not included.

## The idea

Inspiration rarely arrives in order. A writer might begin with an ending, an image, a relationship, or a line of dialogue. That is a point of entry, not necessarily the beginning of the story.

Plot Designer reasons outward from what the writer knows:

> Given what is now established, what still needs to be understood?

It identifies missing causal connections, unclear motivations, contradictions, and structural possibilities. It asks one useful question at a time and accepts corrections, uncertainty, and deliberate ambiguity.

## What makes it different

- **Writer-owned content:** no invented events, motives, or resolutions by default.
- **Flexible entry:** build forward, backward, or outward from a known moment.
- **Author-weighted priorities:** emotional and thematic emphasis comes from the writer, not a universal checklist.
- **Architecture without invention:** compare arrangements of existing material, explaining their tradeoffs instead of declaring one objectively correct.
- **Visible progress:** an outline-so-far can show established material and open questions without pretending the story is complete.
- **Revision is normal:** writers can reopen an assessment when something feels wrong, including the timing of a motivation rather than its importance.

## A typical interaction

1. The writer supplies a fragment or existing outline.
2. The system distinguishes established claims from possibilities and interpretations.
3. It checks whether the next question is already answered or materially important to the writer's focus.
4. It asks one question, reflects back an interpretation, or offers an appropriate structural next step.
5. The writer answers, corrects, defers, reviews the outline, or finishes for now.

A structural movement is not automatically a chapter or a scene. Structural advice should explain function, sequence, emphasis, and what remains the writer's decision.

## Boundaries

Analysis and architectural comparison do not authorize new story content. Explicitly requested brainstorming remains provisional until the writer accepts it. An ambiguity is not necessarily a mystery to solve. A draft is not defective simply because it leaves something unstated.

## Project status

An experimental local prototype exists separately. It has exercised conversational development, revision workflows, source intake, and structural advisement. Source-intake testing demonstrated useful extraction and recovery, but also exposed interpretation and attribution errors even where quotations were exact.

This showcase does **not** claim production readiness, comprehensive semantic accuracy, or a completed security audit. Exact citations and passing mechanical tests are not substitutes for author review.

## Explore

- [Architecture and workflow](ARCHITECTURE.md)
- [Synthetic example](EXAMPLE.md)
- [Publication and privacy boundaries](PRIVACY.md)

No open-source license is granted by this repository. A licensing decision is reserved for a later release. Public visibility explains the concept; it does not publish the underlying implementation.
