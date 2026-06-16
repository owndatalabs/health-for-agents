# GitHub Pages for Health for Agents

This folder contains a tiny static website for App Store support and privacy links.

## Suggested GitHub Pages setup

1. Create a public GitHub repository, for example `health-for-agents`.
2. Push this project to GitHub.
3. In the repository, open `Settings` -> `Pages`.
4. Set `Build and deployment` to `Deploy from a branch`.
5. Select branch `main` and folder `/docs`.
6. Save.

The privacy policy URL will look like:

```text
https://owndatalabs.github.io/health-for-agents/privacy/
```

Use that URL in App Store Connect as the app's Privacy Policy URL.

## Before publishing

The configured support email is `owndatalabs+support@gmail.com`.

For future apps, repeat the same pattern with one repository per app:

```text
https://owndatalabs.github.io/another-app/privacy/
```
