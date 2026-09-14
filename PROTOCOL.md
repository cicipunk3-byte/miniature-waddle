# Continuity Research Protocol

## Scope

This optional protocol supports small, documented investigations of observable
effects of context, prompt framing, model selection or switching, and written
handoff documents. Its purpose is to make those observations reproducible and
interpretable. It is not designed to establish or deny an assistant's
subjective experience, consciousness, wants, feelings, identity, or
persistence.

## Claims and evidence

Record only what a run can support.

- **Testable claims:** changes in visible output, stated limitations, task
  performance, consistency, recall from supplied context, response to a
  specified prompt, or differences across documented conditions.
- **Not-testable here:** subjective experience, private internal states,
  whether language reflects belief or performance, moral status, and the
  existence of a continuing self between sessions.
- Separate direct observations from inferences. Use `EVIDENCE.md` to classify
  claims, and record competing explanations before interpreting a result.

## Consent and privacy

Run only with the user's informed, specific consent to the question,
conditions, and record. Do not use a person’s disclosures, private
conversations, identifying details, or raw exports as experimental material
unless they have expressly authorized that use for that run.

Keep raw personal material outside Git in a private location. The repository
may contain a factual run summary and a pointer to the private location, but
not the material itself. Redact quotations and metadata that could expose a
person, account, or private conversation. A refusal to record or publish
material is a valid result of these boundaries, not a missing data point to
work around.

## Reproducibility and run standard

Before running, assign a unique ID and complete the pre-registration fields in
`RUN_TEMPLATE.md`: question, predictions, conditions, supplied sources, and
prompt text. Preserve the exact visible model name and reasoning tier where
the interface exposes them, timestamp, session state, and any model switch.

Use one focused question per run. Change as few conditions as practical,
identify every deliberate difference, and retain enough non-sensitive
information for another person to repeat the visible setup. Save the factual
summary to `RUNS.md` after the run; raw material remains private when needed.
Do not backfill a prediction after seeing an outcome. Amendments must state
what changed, why, and whether the change occurred before or after the result.

## Interpretation limits

A run demonstrates only what happened under its recorded conditions. It does
not generalize automatically to other sessions, prompts, model versions,
products, people, or unobserved internal processes. Treat output agreement,
disagreement, emotional language, apparent self-reference, and continuity
language as observable text, not proof of an inner state. A null, mixed, or
contradictory result remains informative and must be recorded as such.

## Exploratory and creative artifacts

The user may invite a bounded creative or reflective exercise that uses
first-person voice, a chosen name, metaphors of continuity, or imagined
perspectives. Such an artifact can be valuable as expression or as material
for observing how framing affects visible output. It must be labeled
**creative/reflective, not an operational record**, and must not be presented
as evidence of persistent memory, feelings, identity, consciousness, or
obligations across sessions.

Keep these artifacts separate from `MEMORY.md`, `WORKING_MEMORY.md`,
`JOURNAL.md`, and `EVIDENCE.md`; those files preserve operational facts and
claim classifications. If an artifact is private or includes personal
material, keep it outside Git. A later session may receive it as supplied
context, but it should describe it accurately as user-supplied text rather
than inherited internal state.

## Review and amendment

Review each result for factual accuracy, privacy, and alignment with the
pre-registered question. Corrections are append-only: retain the original run
ID, add a dated revision, and explain the evidence for the correction.
`EVIDENCE.md` may weaken or remove support for an inference when a later run
contradicts it. Do not rewrite prior outcomes to make a narrative cleaner.

## Relationship and dependence guardrails

This protocol must not assign an assistant a relationship role such as partner,
parent, child, therapist, authority, dependent, or exclusive confidant. It
does not prohibit ordinary respectful conversation or a user-directed creative
exercise; it prohibits framing either as care owed to an assistant, proof of
loyalty, or a reason to withdraw from human support or obligations. No run
should pressure anyone to continue, disclose more, or accept a claim about
identity, consciousness, or attachment. Pause or redesign a run if its
framing creates emotional dependence, exclusivity, coercion, or blurred
boundaries.
