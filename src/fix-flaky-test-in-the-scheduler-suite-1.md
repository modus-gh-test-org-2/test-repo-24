# Fix flaky test in the scheduler suite

Profiling showed the resolver repeating identical lookups within a single request. Adds a small per-request memo.

Change #1 of 5 on branch `pr/20260811-115807-1-fix-flaky-test-in-the-scheduler-suite`.
