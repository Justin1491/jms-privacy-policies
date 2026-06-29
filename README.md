# JMS App Support and Privacy Pages

This folder is a static GitHub Pages-ready site for JMS app support information and privacy policies.

## Current URLs

When published at `https://justin1491.github.io/jms-privacy-policies/`, the current public pages are:

```text
https://justin1491.github.io/jms-privacy-policies/support/
https://justin1491.github.io/jms-privacy-policies/apps/chatpaste/
https://justin1491.github.io/jms-privacy-policies/apps/marketmosaic/
```

## App Store Metadata

- Generic JMS Support URL: `https://justin1491.github.io/jms-privacy-policies/support/`
- ChatPaste Privacy Policy URL: `https://justin1491.github.io/jms-privacy-policies/apps/chatpaste/`
- Support email: `jmsappdevoplement@gmail.com`

## Add Another App

1. Add the app-specific privacy policy at `apps/<app-slug>/index.html`.
2. Add app-specific support notes to `support/index.html` if the app needs them.
3. Update the shared navigation links in `index.html`, `support/index.html`, and each app privacy page.
4. Update each page's `Related Pages` section so users can move between Support, ChatPaste, Market Mosaic, and the app directory.
5. Update `index.html` so the new app pages are discoverable from the home page.

## Before Publishing

- Confirm the company name and copyright line are correct.
- Confirm the support and privacy text match the shipped app behavior.
- Do not include private user data, logs, API keys, secrets, or unreleased support addresses.
- Run a relative-link check across the static HTML pages before pushing.
