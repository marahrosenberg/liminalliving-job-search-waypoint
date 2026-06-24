# Changelog

# Changelog

## v1.1.0 — June 2026

### Changed
- README: Rewrote install instructions as two-track flow (free vs Pro/Max)
- README: Added grounded opening — users don't need a job description or resume to start
- README: Corrected resume upload timing — Claude asks for it during intake, not at setup
- README: Added invocation examples for both free and paid users
- SKILL.md: Moved resume ask from setup to Experience Intake section
- SKILL.md: Added delivery format question (Word / plain text / Markdown) before Step 9
- SKILL.md: Added "I just need somewhere to be right now" as a named entry point
- SKILL.md: Expanded Support Mode trigger to include users arriving without a task
- protocol.md: Updated Step 7 to remove .docx-only constraint
- protocol.md: Added format question to Step 9 delivery sequence

### Fixed
- YAML frontmatter: Added > to description field to prevent parser error on skill upload

## v1.0.0 — May 2026
- Initial release
### Renamed
- Tool renamed from `liminalliving-resumework` to `liminalliving-job-search-waypoint`
- Rationale: "victory" framing too war-like; waypoint better reflects the journey
  orientation — a fixed point that helps you know where you are, not a promised destination

### Structural
- Unpacked repo — tarball removed, files now live directly in the repository
- Added `references/protocol.md` — previously existed only as a Google Doc (v3.0)
- Added `LICENSE` (CC BY-NC 4.0)

### protocol.md (v4.0, built from Victory Protocol v3.0)
- Removed personal data (location-specific prohibited terms)
- Replaced ad-hoc prohibited terms list with anti-AI writing checklist (banned phrases +
  register test)
- Reframed "wound/bleeding" language to plain "problem statement" language
- Reframed Claude-specific memory retrieval instruction to general best practice
- Synced cover letter structure to T-shape, 5 moves (was inconsistent with SKILL.md)
- Wove emotional layer markers into Steps 1, 2, and 3A — references SKILL.md Support Mode
- Added non-linear career framing section to Step 6
- Added Quick Reference section at end

### SKILL.md
- Updated skill name in frontmatter
- Replaced load order table with plain prose instruction
- Synced cover letter quick reference to T-shape, 5 moves
- Added anti-AI writing check note to Document Standards

### README
- Rewrote for new name and waypoint framing
- Updated install instructions (no longer tarball-based)
