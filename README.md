# Human Interface Guidelines Skill

Apply Apple's Human Interface Guidelines (HIG) to design, review, and specify UI/UX for iOS, iPadOS, macOS, watchOS, tvOS, and visionOS.

## Install

```bash
npx skills add zanwei/human-interface-guidelines-skill --skill human-interface-guidelines
```

## Includes

- `SKILL.md`: operational workflow and output templates
- `references/hig_section_map.md`: HIG hierarchy map
- `references/hig_catalog.md`: page catalog with title + abstract
- `scripts/search_hig.py`: keyword search on local catalog
- `scripts/fetch_hig_page.py`: fetch and render HIG DocC pages to Markdown

## Usage examples

- "Review this iOS settings page against HIG and list must-fix issues."
- "Convert this PRD into a HIG-aligned iOS UI spec."
- "Pick the right component pattern for a visionOS picker flow."
