# LinkedIn Saved Item Scraper — Agent Context

## Purpose

Create a practical way for a user to export their own saved LinkedIn items. The repository is the source of truth for project documentation and future implementation.

## Current authorization and status

The initial session authorized **project setup only**: repository scaffolding, README, agent context and ignore rules. No implementation, account login, scraping, dependency installation or extraction is authorized by that setup request.

Wait for a subsequent explicit development request before researching an approach or building the scraper. When development is requested, confirm the actual saved-item categories and validate the approach against current evidence; do not assume undocumented endpoints or selectors work.

## Public repository boundary

- Commit code, public documentation and synthetic examples only.
- Keep actual exports, browser profiles, cookies, session state, tokens, screenshots of private content and personal research notes local and ignored.
- Never copy business documents or private workspace context into this public repository.
- Do not request that credentials or browser cookies be pasted into chat or committed.
- Check the staged files before every commit. `.gitignore` does not protect files already tracked.
- Select an open-source license with the owner before claiming the project is open source.

## Open decisions

- Script, CLI, extension or other approach.
- Runtime and dependencies.
- Supported saved-item categories and desired fields.
- Export formats and how completeness will be verified.
- License.

## Future implementation principles

Prefer a small, local-first solution. Keep authentication under user control. Do not change the user's saved items. Do not claim full export coverage without evidence. Document limits and meaningful verification alongside the implementation.
