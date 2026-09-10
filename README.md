# tinkerer0

Research, code, and a few side quests.

[한국어](README.ko.md) · [All public projects](docs/PROJECTS.md) · [Games & experiments](docs/GAMES.md)

## Selected projects

### [MemoPet](https://github.com/tinkerer0/MemoPet) · macOS

A small animated notebook for capturing a thought or sketch without opening a separate notes app.

**Look at:** native window interactions, mixed text and drawing, and local notebook persistence.  
**Built with:** Swift · AppKit. **Available as:** source code to build locally; macOS 13+.

[Build & use](https://github.com/tinkerer0/MemoPet#build-and-run) · [Persistence tests](https://github.com/tinkerer0/MemoPet/blob/main/Tests/MemoPetCoreTests/MemoNotebookStoreTests.swift)

### [DeskWidget](https://github.com/tinkerer0/DeskWidget) · Windows

An app that turns a folder of local images into movable, resizable desktop widgets.

**Look at:** image validation, local settings, and an explicit file allowlist for packaging.  
**Built with:** Electron · JavaScript · C# launcher. **Available as:** source and a Windows packaging workflow; signed binaries are not currently provided.

[Source & setup](https://github.com/tinkerer0/DeskWidget#개발) · [Image validation](https://github.com/tinkerer0/DeskWidget/blob/main/src/image-utils.js) · [Packaging checklist](https://github.com/tinkerer0/DeskWidget/blob/main/docs/RELEASE_CHECKLIST.md)

### [evidence-gate](https://github.com/tinkerer0/evidence-gate) · Developer workflow

A Claude Code skill and audit hook for connecting completion claims to their supporting checks.

**Look at:** the distinction between declared and enforced rules, stale evidence, and forged citations.  
**Built with:** Python · Claude Code hooks. **Scope:** a workflow aid with rule-based checks, not a guarantee that generated work is correct.

[Design](https://github.com/tinkerer0/evidence-gate/blob/main/docs/DESIGN_declare_enforce_split.md) · [Audit hook](https://github.com/tinkerer0/evidence-gate/blob/main/hooks/eg_audit.py) · [Tests](https://github.com/tinkerer0/evidence-gate/blob/main/tests/test_eg_audit.py)

### [mote](https://github.com/tinkerer0/mote_game) · Browser game

A small arcade prototype built around absorption, growth, cashing out, and collecting skins.

**Look at:** a complete play loop in one HTML file, procedural sound, and browser-local saving.  
**Built with:** Canvas 2D · JavaScript · Web Audio. **Available as:** a browser prototype.

[Play](https://tinkerer0.github.io/mote_game/) · [Source & controls](https://github.com/tinkerer0/mote_game)

## Explore by area

- **Apps:** [MemoPet](https://github.com/tinkerer0/MemoPet), [DeskWidget](https://github.com/tinkerer0/DeskWidget), [DeskPin](https://github.com/tinkerer0/desk_pin)
- **AI-assisted development:** [Orca coordination policy](https://github.com/tinkerer0/orca-autonomous-coordinator), [evidence-gate](https://github.com/tinkerer0/evidence-gate), [other workflow tools](docs/PROJECTS.md#개발-도구와-작업-지침)
- **Games:** [playable projects, theme variants, and terminal experiments](docs/GAMES.md)
- **Visualization:** [AI Scientist Lab UI](https://github.com/tinkerer0/ai_scientist_lab_ui) — a synthetic interface demo, with no live research execution.

The linked repositories document their own setup and limitations. This overview highlights inspectable work; it does not imply a production release or an independent performance evaluation for every project.

## Feedback

I am still learning, and I welcome corrections and suggestions through issues or pull requests.

## License

[MIT](LICENSE) applies to this profile's documents. Linked projects retain their own licenses.
