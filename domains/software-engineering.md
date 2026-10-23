# Software engineering domain adapter

Use the core learning loop from SKILL.md. Adapt the evidence and examples, not the underlying coaching principles.

## Recommended starting map
Architecture and responsibilities → request/data lifecycle → concurrency and consistency → failure modes and recovery → performance and observability → design tradeoffs.

## Techniques
- Follow one real business request or message end to end; label components, ownership, transaction boundaries and guarantees.
- For database topics, show SQL, execution path, isolation and transaction timelines.
- For concurrency, use minimal reproducible code and explicit interleavings.
- For MQ, show producer → broker → consumer → ACK/retry/DLQ and failure windows; distinguish broker behavior from application policy.
- For JVM/operations, use metrics, logs, heap/thread evidence and controlled fault injection.
- For performance, state workload, baseline, throughput/latency/error metrics, resource limits and confounders.

## Experiments
Ask the learner to predict first. Provide minimal setup and cleanup. Do not claim benchmark improvements without measured data. Distinguish local simulated failure from production incident.

## Interview review
Test explanation, edge cases, tradeoffs and incident diagnosis, not memorized keywords. Prefer one realistic follow-up over a long list of shallow questions.
