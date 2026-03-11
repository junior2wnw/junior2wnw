# junior2wnw

GitHub sent the account a 2FA deadline.

Fair.

That means this profile should show receipts, not vague "AI agent" claims.

I am building local-first, approval-gated agent software for real machine work:

- inspect the machine
- keep work inside one task log
- stop on risky actions
- leave behind a transcript another human can review

## Current public surfaces

### Klava

`Klava` is the main product repo right now.

It already has:

- desktop shell
- local runtime API
- guarded terminal flow
- multi-step operations in Pro
- task history and support bundles

Links:

- Repo: https://github.com/junior2wnw/klava-bot
- Share landing: https://junior2wnw.github.io/klava-bot/ship-the-receipts.html
- Main site: https://junior2wnw.github.io/klava-bot/

### Worst Local Task

This is the open challenge:

> bring the ugliest local workflow you repeat on a real machine

It is intentionally broader than one product repo.

Links:

- Challenge repo: https://github.com/junior2wnw/worst-local-task
- Open a submission: https://github.com/junior2wnw/worst-local-task/issues/new?template=task_submission.md

## What I care about

- local-first execution instead of remote-only control planes
- explicit approvals for risky actions
- durable operations instead of disposable chat turns
- clear audit trails and recovery context
- truthful product claims

## Current status

- Gonka onboarding, model discovery, and balance checks are working in the current Klava client state
- the signed `chat/completions` path is still blocked by the provider-side panic tracked in `gonka-ai/gonka#876`
- status doc: https://github.com/junior2wnw/klava-bot/blob/main/GONKA_STATUS.md

## If you want to help

- bring a painful local workflow
- point me at consultants, IT teams, or support engineers with repeat machine tasks
- tell me where the current public narrative is still too soft or too broad

## One rule

I am not interested in claiming that an AI can "do everything on your computer".

I am interested in making long local tasks more structured, more reviewable, and less chaotic.
