# Logos

Image assets for Vertus: favicons and icons for third-party providers.

This repository has no license file. The provider files show logos of other companies' products.

## Files at the root

| File | Format | Size |
|---|---|---|
| `favicon 256x256.png` | PNG | 256 x 256 |
| `favicon_512x512.png` | PNG | 512 x 512 |
| `WhatsApp Image 2026-08-10 at 3.55.43 PM.jpeg` | JPEG | 320 x 321 |

The JPEG shows a pink mark on a light, rounded tile.

## Files in `providers/`

Files are named by provider: `providers/<provider>.<ext>`. A sub-service with its own icon is at
`providers/<provider>/<sub-service>.<ext>`. The `-dark` suffix marks a version for dark backgrounds.

| Provider | Files |
|---|---|
| Airtable | `airtable.svg`, `airtable.png` (512 x 512) |
| Atlassian | `atlassian.svg`, `atlassian/project_management.svg` |
| Calendly | `calendly.svg` |
| Dropbox | `dropbox.svg` |
| GitHub | `github.svg`, `github-dark.svg` |
| Gmail | `gmail.svg`, `gmail.webp` (1280 x 1019), `Gmail_icon_(2026).svg.webp` (a WebP file, byte-identical to `gmail.webp`) |
| Google | `google.svg`, `google_calendar.svg`, `google_contacts.svg`, `google_docs.svg`, `google_forms.svg`, `google_sheets.svg`, `google_tasks.svg` |
| Higgsfield | `higgsfield.svg` |
| HubSpot | `hubspot.svg` |
| Linear | `linear.svg`, `linear-dark.svg` |
| Microsoft | `microsoft.svg`, `microsoft/calendar.svg`, `microsoft/calendar.png` (512 x 512), `microsoft/email.svg`, `microsoft/email.png` (512 x 512), `microsoft/file_storage.svg`, `microsoft/messaging.svg` |
| Notion | `notion.svg` |
| Salesforce | `salesforce.svg` |
| Slack | `slack.svg` |
| Stripe | `stripe.svg` |
| Zoom | `zoom.svg` |

## Using these files

Files under `providers/` are linked by their raw GitHub URL on `main`, so renaming or moving one breaks
those links.
