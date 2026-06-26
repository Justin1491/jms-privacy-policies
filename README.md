# JMS Privacy Policies

This folder is a static GitHub Pages-ready site for JMS app privacy policies.

## Current Policy URLs

When published at the root of a GitHub Pages site, the app privacy policy URLs will be:

```text
https://<github-username>.github.io/<repo-name>/apps/chatpaste/
https://<github-username>.github.io/<repo-name>/apps/marketmosaic/
```

If you publish from a user or organization site repository named `<github-username>.github.io`, the URL will be:

```text
https://<github-username>.github.io/apps/chatpaste/
https://<github-username>.github.io/apps/marketmosaic/
```

## Publish on GitHub Pages

1. Create a new public GitHub repository, for example `jms-privacy-policies`.
2. Copy the contents of this `PrivacyPolicies` folder into the root of that repository.
3. Commit and push the files.
4. In GitHub, open the repository settings.
5. Go to Pages.
6. Set the source to deploy from the main branch and root folder.
7. Use the published app-specific URL as the App Store privacy policy URL.

## Add Another App

1. Create a new folder under `apps/<app-slug>/`.
2. Copy `apps/chatpaste/index.html`.
3. Update the app name, effective date, description, and policy details.
4. Add the new app to the policy list in `index.html`.

## Before Publishing

- Confirm the company name and copyright line are correct.
- Confirm the privacy text matches the shipped app behavior.
- Replace the contact section with a direct support email or support URL if one is available.
