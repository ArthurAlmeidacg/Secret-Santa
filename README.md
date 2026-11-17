# Secret Santa

A simple, single-file Secret Santa web app. No backend, no sign-up, no database.

## How it works

1. The organizer adds all participants' names (and an optional message, such as a suggested gift budget).
2. The app draws random pairs, so nobody draws themselves and nobody is drawn twice.
3. Each participant gets a unique link. Opening it shows who they should buy a gift for.
4. The organizer only sees the "Copy link" and "WhatsApp" buttons, never the results.

## Notes

- The draw result is encoded inside each link, so nothing is stored on a server.
- The encoding is obfuscation, not real encryption. It's meant for casual family fun, not high-security use.
- Send all links before closing or refreshing the page, since redrawing produces different results.
