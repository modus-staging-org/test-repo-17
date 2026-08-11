# Add structured logging to the ingest path

Profiling showed the resolver repeating identical lookups within a single request. Adds a small per-request memo.

Change #3 of 6 on branch `pr/20260811-121032-3-add-structured-logging-to-the-ingest-pat`.
