# iOS File Picker Fix for GitHub Pages

This update removes the file-type filter from the picker so iPhone and iPad no longer grey out KML files.

## What changed
- The file picker now accepts any file.
- The app validates KML or KMZ after selection.
- This specifically fixes Safari on iOS/iPadOS greying out .kml files.

## How to update your site
1. Download this ZIP.
2. Unzip it.
3. Replace the files in your GitHub repo with these updated ones.
4. Wait a minute for GitHub Pages to redeploy.
5. Refresh Safari.
