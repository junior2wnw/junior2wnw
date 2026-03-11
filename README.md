# junior2wnw

Current work sits around local runtimes, approvals, audit trails, and machine operations.

The public surfaces below are meant to be inspectable, not glossy.

## Current work

### Klava

`Klava` is the current implementation path.

It already has:

- desktop shell
- local runtime API
- guarded terminal flow
- multi-step operations in Pro
- task history and support bundles

Links:

- Repo: https://github.com/junior2wnw/klava-bot
- Field note 01: https://junior2wnw.github.io/klava-bot/field-note-01.html
- Main site: https://junior2wnw.github.io/klava-bot/

### Machine Work Index

This is the separate intake surface for difficult local-machine workflows.

Links:

- Index: https://github.com/junior2wnw/machine-work-index
- Open a case note: https://github.com/junior2wnw/machine-work-index/issues/new?template=case_note.md

## Working preferences

- local-first execution instead of remote-only control planes
- explicit approvals for risky actions
- durable operations instead of disposable chat turns
- clear audit trails and recovery context
- claims that survive inspection

## Current boundary

- Gonka onboarding, model discovery, and balance checks are working in the current Klava client state
- the signed `chat/completions` path is still blocked by the provider-side panic tracked in `gonka-ai/gonka#876`
- status doc: https://github.com/junior2wnw/klava-bot/blob/main/GONKA_STATUS.md

## Open threads

- difficult local workflows with meaningful approval boundaries
- consultant, IT, and support environments with repetitive machine work
- places where the public framing should become narrower and more exact

## One constraint

I am not interested in claiming that an AI can "do everything on your computer".

I am interested in making long local tasks more structured, more reviewable, and less chaotic.
