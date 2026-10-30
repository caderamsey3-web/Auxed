# Auxed

Your taste. On record.

A responsive, single-user music journal built with one self-contained HTML file.

## Features

- Browse and search the starter album catalog, or log any album manually.
- Rate in half-star steps, review, tag, edit, and log repeat listens.
- Save favorites and a listening queue.
- Create lists, add albums, and arrange their order.
- Edit your profile and view listening statistics.
- Remove sample data and download or restore a JSON backup.

## Publish with GitHub Pages

1. Open this repository's Settings → Pages.
2. Set Source to Deploy from a branch.
3. Select main and /(root), then click Save.
4. Wait for the Pages deployment to finish. GitHub will show the website URL on that page.

Settings: https://github.com/caderamsey3-web/Auxed/settings/pages

Expected address after Pages is enabled: https://caderamsey3-web.github.io/Auxed/

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

No build command, dependencies, API keys, or server are required. The root index.html is the website.

## Run locally

Open index.html in a modern browser, or serve the folder with:

    python -m http.server 8000

Then visit http://localhost:8000.

## Data and prototype scope

Personal data stays in localStorage in the current browser; it is not sent to GitHub or shared with other visitors. There are no accounts or cross-device synchronization.

Use You → Download backup and You → Restore backup to move your collection between browsers or from the chat preview to the published website.

The starter catalog contains illustrated placeholder covers and removable sample diary entries and lists. Music playback and online catalog search are not connected.
