# The Data That Built the World

A Marp presentation about influential datasets, from John Snow's cholera map to LAION-5B. It treats collection, provenance, consent, representation, licensing, and repurposing as part of each dataset's story.

## Contents

- `slides/presentation.md` is the presentation source.
- `themes/archive.css` provides the custom Marp theme.
- `research/` is an Obsidian-compatible research vault with dataset notes and a bibliography.
- `Taskfile.yml` contains reproducible install, preview, and export commands.

## Build and present

Requirements: Node.js, npm, and [Task](https://taskfile.dev/).

```sh
# Install the locked dependency set
 task install

# Open a browser preview
 task preview

# Create PowerPoint and PDF exports in dist/
 task build
```

The PowerPoint export preserves Marp presenter notes. Use the regular `task pptx` output rather than an editable PowerPoint export to retain the deck's visual rendering and notes.

## Sources and attribution

Research sources are documented in `research/bibliography.md` and summarized on the final slides. `ATTRIBUTION.md` records the repository's media and licensing review. Dataset access does not imply permission to redistribute, reuse, or train on the underlying data.

## License

The original presentation, theme, research notes, and documentation are licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/). See [LICENSE](LICENSE). This allows commercial reuse, provided credit is given and adaptations are shared under the same license.

Third-party software and linked resources remain subject to their own terms. This license does not grant rights in them.
