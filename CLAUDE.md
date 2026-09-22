# CLAUDE.md — atoms (PUBLIC repo)

Small, publishable Markdown blocks shared by Greg's website and slide decks.

- Everything here is public. Greg's own CV and profile content is fine. No confidential partner, funding or unpublished material.
- Blocks are plain Markdown, included with `{{< include /atoms/profiles/<block>.md >}}`. No slide layout and no `#`/`##` headings (in slides, `##` starts a new slide). `greg.md` keeps its front matter.
- Change shared wording here, not in the repos that use it. They pull it with `git submodule update --remote atoms`.
