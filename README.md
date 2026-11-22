# LPC & OPC Study Companion

GitHub Pages-ready study companion. Upload all files in this folder to the root of your repository.

## Latest interface update
- Study slide settings icon opens a dedicated edit mode. Only Add Slide, Delete Slide, Insert Image and Save are shown while editing. Saving returns to read-only mode.
- Inserted slide images are compressed and constrained to the slide text width, with a maximum displayed height of 280px while preserving aspect ratio.
- Flashcard settings icon opens edit mode with Add Card, Delete Card and Save Card. Normal mode shows the question, Reveal Answer, and previous/next navigation.
- Main-menu settings icon reveals Add Topic, Delete Topic and Change Order. Topic deletion and reordering controls appear only when their respective menu action is selected.
- Topic order is persisted across reloads. New topics automatically include Study, Additional Notes and Review sections.

## Data storage
Study edits, notes, cards, images and topic order are saved in browser local storage on the device. They are not automatically synced to GitHub or other devices. Keep an export/backup of important study data before clearing browser data or changing devices.

## Publish
1. Extract the ZIP.
2. Upload/replace the repository files (`index.html`, `manifest.webmanifest`, `sw.js`, and `README.md`).
3. Commit the changes and allow GitHub Pages to redeploy.
4. Refresh the app. The service-worker cache version is updated to load the new interface.
