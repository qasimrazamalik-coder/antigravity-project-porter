# Contract

## Capability
Prepare a portable agentic-IDE project packet with context boundaries, commands, environment checks and rollback notes.

## Input root
`items` with fields: id, priority, effort, channel.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
