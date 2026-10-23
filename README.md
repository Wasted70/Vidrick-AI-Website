# Vidrick Website — Cleaned Static Release

## Included

- Updated landing page
- Sign-in and account links
- Updated trial links for the future customer portal
- Updated licensing language
- Privacy, Terms, EULA, and Refund pages
- Updated support and sales addresses
- Netlify deployment instructions

## Important

Copy your existing `assets` folder into this folder before publishing. The landing page references the application screenshots inside `assets/`.

The portal links currently point to:

- `https://account.vidrick.ai/login`
- `https://account.vidrick.ai/register`

Those pages will become active when the customer portal is deployed.


## Updated application screenshots

This package includes application screenshots for:

- Transcribe
- Settings
- Editor
- Insights
- History
- About & Updates
- First-run Welcome

The homepage uses `*-versionless.png` copies of Transcribe and Editor; the
editor screenshot is available in an expandable preview. AI Insights uses an
accessible HTML/CSS illustration populated with clearly labeled fictional
output excerpts, with its sample transcript available below the illustration.
The simplified homepage layout is scoped in `homepage.css`; shared styles and
the existing guide/legal pages are unchanged. The original slogan is retained
at a smaller responsive size, with additional paint space for gradient-text
descenders. Release 4.3.4 appears in the improvements section and application
metadata, with a brief summary of HTTPS certificate protections and a stable download
link for 4.3.1 apps whose in-app updater is blocked, not in screenshot
labels. All original screenshot assets are retained.

The `assets` folder is already included, so this package can be deployed directly.
