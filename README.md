# Travel Japan Memory Demo

A browser-only travel memory app built as a single HTML file.

## Usage

Open `index.html` in a browser. Visit status, visit dates, and memos are saved automatically. Uploaded photos are compressed and saved to the currently selected prefecture.

The app stores all travel data and photos in IndexedDB in the current browser. Exported JSON backups are recommended before changing devices, browsers, or the site URL.

## Notes

- No server is required.
- No build step is required.
- No photo location or GPS metadata is read.
- The latest app source is bundled into `index.html`.