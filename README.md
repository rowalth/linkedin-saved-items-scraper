# LinkedIn Saved Item Scraper

Project for a tool, script or workaround to export a user's own saved LinkedIn items.

**Status: repository scaffold only. No scraper has been implemented or run.**

## Goal

Make saved LinkedIn content available for personal reference outside LinkedIn. The implementation approach and supported saved-item categories still need to be researched and validated.

## Intended capabilities

- Export the user's own saved items with their original LinkedIn links.
- Preserve useful metadata and available text where feasible.
- Support a portable export format; CSV and JSON are candidates.
- Handle duplicates and make incomplete exports explicit.
- Keep authentication and actual exported data on the user's machine.

These are project goals, not existing features or promises of complete coverage.

## Current setup

- Public repository intended: `rowalth/linkedin-saved-items-scraper`.
- Shared agent context: [AGENTS.md](AGENTS.md).
- Local data, browser profiles and credentials excluded through `.gitignore`.
- Runtime, dependencies and extraction method: undecided.
- License: not selected. Public visibility alone does not grant an open-source license.

There is nothing to install or execute yet. No dependencies or browser extensions are required for this scaffold.

## Next development session

Start with the project goal and `AGENTS.md`. Research feasible approaches, verify which saved-item categories can be accessed, and agree on a first implementation scope before building it.

This is an independent project and is not affiliated with LinkedIn.
