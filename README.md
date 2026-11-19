# Weblean

Buildless, responsive studio website. Serve `dist` with any static HTTP server.

## Before public launch

- Replace the plain-text Weblean name in the header and footer with the official supplied wordmark. User approved temporary plain text on 2026-11-20.
- Add the confirmed contact email or project inquiry URL. User asked to defer this on 2026-11-20. The current inquiry dialog explicitly says contact details are pending and allows a local brief download; it does not send inquiries.
- Confirm final About copy: the supplied brief ended mid-sentence. Current copy follows the supplied positioning.
- Shveli showcase uses existing Shveli assets in an editorial product composition, not a literal app screenshot. No fabricated clients, metrics, or testimonials.

## Structure

- `dist/index.html`: content, accessible project and inquiry dialogs.
- `dist/styles.css`: responsive monochrome layout, reduced-motion support.
- `dist/app.js`: mobile menu, dialogs, local brief download, canvas coordinates.
- `dist/assets/`: existing Shveli brand and product imagery.

To add a project, duplicate the `.project` article and provide its own project details dialog and trigger. Update the selected-work count.
