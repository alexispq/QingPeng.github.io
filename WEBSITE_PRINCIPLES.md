# Website Principles

## Purpose

The site presents Qing Peng's position, research, teaching, contact information, and C.V. with a quiet academic tone. The first screen should immediately identify Qing as an Economist at the IMF Shanghai Center.

## Structure

The repository is a static GitHub Pages site. It does not require a build step. This keeps the preview private and easy to inspect before anything is pushed.

## Design

- White background with restrained blue links and gray metadata.
- Concise top navigation: About, Research, Publications, Working Papers, Teaching.
- Side-by-side academic hero on desktop: text left, portrait right.
- Portrait stacks above the text on mobile.
- Paper entries are plain text blocks rather than cards.
- Focus states remain visible for keyboard navigation.

## Content Rules

- Keep the homepage intro and bio text distinct.
- Use active, plain academic prose.
- Keep dates unambiguous.
- Link to local PDFs when possible.
- Do not add visible migration notes or process commentary to public pages.

## Migration Notes

The old Google Sites page supplied the research, teaching, CV, and contact content. Qing supplied the portrait directly and it was optimized locally. The user later updated Qing's current position to Economist, IMF Shanghai Center. Co-author external links were left blank rather than guessed; review `data/coauthors.json` before publication.
