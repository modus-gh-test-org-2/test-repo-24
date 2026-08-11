# Add structured logging to the ingest path

Profiling showed the resolver repeating identical lookups within a single request. Adds a small per-request memo.

Change #2 of 5 on branch `pr/20260811-115807-2-add-structured-logging-to-the-ingest-pat`.
