# plan-levels-timer

Starts the daily runs in a private repository at fixed times, because GitHub does not start scheduled runs in
private repositories on the free plan. It holds no code or data: one workflow that calls GitHub's
`workflow_dispatch` API with a token stored as a repository secret (`DISPATCH_TOKEN`).
