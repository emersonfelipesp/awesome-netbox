# README quality checks

Preserve the two parallel README.md quality jobs and their complete original awesome-lint and awesome_bot commands. Keep full-history checkout because the tools may inspect repository history. Every pull request and main push selects the existing checks; feature pushes are already excluded. Only superseded pull-request work may cancel. Keep repository token permission read-only and do not persist checkout credentials.

Do not skip a failing check, add ignored links without an established contract, invent successful execution or require a release as a CI prerequisite. Main protection must use actual successful check names and their observed application identity. No upstream source or publication automation is part of these quality jobs.

## Supported lint runtimes

The maintained Node setup action reads Node 24 from `.node-version`, satisfying the current awesome-lint Node >=20 engine. The previous asdf action and obsolete Node 16 declaration are removed because their bootstrap failed before lint. Ruby remains on the original 3.0 series with its runner-supported 3.0.7 patch release. Preserve the complete lint commands and report real README failures; do not add ignored links to make an unavailable runtime appear successful.
