# Inter Built-in Documents

Standalone Lao-language static HTML app for creating built-in furniture documents. Demo / single-admin local prototype.

## Features

- Quotation, invoice, receipt (including partial payment)
- Multiple quantity/price line items, THB and LAK
- Printable A4 layout / browser Save as PDF
- Local document listing, edit and delete with confirmation
- Backup and restore JSON files
- Mobile responsive design

## Run

Open `index.html` in Chrome, Safari or another modern browser. No dependencies or build tools required.

## Deploy

Upload the contents of this folder to the repository root. For GitHub Pages, set **Settings → Pages → Build and deployment → Deploy from a branch → main / root**. For Render static sites, choose build command `echo ready` and publish path `.` (repository root).

## Important security note

This is an MVP prototype: documents are saved only to the current browser's localStorage. There is no genuine password-protected admin account, no server database, no multi-device sync or online backup. Anyone with browser access to this origin/profile may view saved information. Only non-sensitive test records should be used until real authentication and protected backend storage are implemented. GitHub Pages makes the app's code public, not the data stored in each user's browser.
