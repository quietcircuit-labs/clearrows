# ClearRows

A browser-based CSV cleaner. Files are processed in your browser; no backend or account is needed. Open `dist/index.html` in a modern browser or serve the `dist` folder with any static web server.

Choose a CSV, toggle cleaning rules, compare the original and cleaned previews, and export a new file. The original file is never overwritten. Supports comma-delimited CSV with quoted fields and embedded newlines; malformed rows are rejected. Duplicate removal compares entire rows after enabled transformations, keeping the first. Previews show up to 100 rows; exports include all rows. Very large files may exceed browser memory.

Optional Google Fonts are loaded from Google when online; the tool works with fallback fonts offline. CSV content is not transmitted by the app.

