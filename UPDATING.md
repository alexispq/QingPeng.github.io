# Updating Qing Peng's Website

This site is intentionally simple: edit `index.html` for public copy, `assets/css/styles.css` for styling, and `data/writings.json` for structured records that future tools can reuse.

## Add a New Paper

1. Add a new `<article class="paper">` inside either the `#publications` or `#working-papers` section of `index.html`.
2. Use the existing paper entries as the template: title, coauthors, venue/status, abstract, and presentations if available.
3. Add the same paper to `data/writings.json`.
4. If there is a public PDF, save it in `assets/files/` and link to it locally.

## Update the C.V.

Replace `assets/files/qing-peng-cv.pdf` with the new PDF, keeping the same filename. The homepage and contact buttons will keep working.

## Update the Photo

Replace `assets/images/qing-peng.jpg` with a square optimized portrait. Keep the image under about 200 KB when possible.

## Add or Fix a Collaborator

Edit the People section in `index.html` and update `data/coauthors.json`. Co-author links were not added unless they could be verified confidently from the migrated material, so Qing should review every person and add the correct website, university page, or LinkedIn URL before publication.

## Before Publishing

Preview locally, check the mobile layout, click every navigation item, and open the C.V.
