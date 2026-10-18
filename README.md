# Travel Japan Memory

A browser-only travel memory app built as a single HTML file.

## Usage

Open `index.html` in a browser. The app stores data in the browser's local storage area, so exported backups are recommended before changing devices or browsers.

When an uploaded photo includes EXIF GPS metadata, the app tries to detect the prefecture automatically using embedded Japan prefecture boundary data. Photos without GPS metadata are saved to the currently selected prefecture.

## Notes

- No server is required.
- No build step is required.
- The latest app source is bundled into `index.html`.
- Automatic prefecture detection works offline after the HTML file is loaded.
- Some Android/browser file pickers may remove GPS metadata before the HTML app can read it.
- Boundary data source: jpn-atlas / Global Map Japan.
