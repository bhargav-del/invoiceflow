# Invoiceflow

A calm, local-first invoice builder for freelancers and small teams.

Invoiceflow turns the most repetitive part of freelance work into a focused workflow: edit line items, see totals update live, create fresh drafts, and print when you're ready.

## Highlights
- Live invoice preview and automatic totals
- Add/remove line items with local persistence
- New invoice draft dialog
- Print-ready invoice action
- Responsive layout and accessible form controls
- No build step and no external credentials

## Run locally

```bash
python3 -m http.server 4173
```

Open http://localhost:4173.

The included GitHub Actions workflow deploys the static app to GitHub Pages.

## License
MIT © 2026 Yuin

## Desktop release

The repository includes a portable Windows desktop build. Every push to `main` runs the Windows packaging workflow and publishes a `.exe` to the repository's **Releases** section. The desktop shell loads the same app locally, so it works without an API key or server.

## Android release

An Android 7.0+ build (API 24+) is scheduled for **September 16, 2026 at 08:00 IST**. The same responsive product is packaged with Capacitor as an installable APK and published to the repository's **Releases** section as `v1.0.0`.
