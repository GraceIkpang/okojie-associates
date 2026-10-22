# Design mockups

Static HTML mockups used to design pages before they're built into the app.
They aren't part of the Laravel app or the frontend build.

| File        | Page     | Built in                                                          |
| ----------- | -------- | ----------------------------------------------------------------- |
| `home.html` | Homepage | `resources/js/pages/home.tsx`, `resources/js/components/home/`    |
| `portal-overview.html` | Client portal: overview | `resources/js/pages/portal/overview.tsx`, `resources/js/layouts/portal-layout.tsx` |

`shared/tokens.css` holds the colors, type and components the newer mockups share.
Mockups with several states (return status, fee) have a dark "Mockup states" panel
in the corner for switching between them. It isn't part of the design.

To view one, open the file in a browser. No server is needed. The moon/sun
button switches between light and dark.

The mockups can run ahead of the app while a design is being explored. The app
is the source of truth for what's live, and the mockup uses sample data (for
example the client and preparer names in the portal preview).
