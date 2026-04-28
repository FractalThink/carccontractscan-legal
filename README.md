# carccontractscan-legal

Public source for the CarContractScan legal documents published at <https://legal.fractalthink.com>.

## What's here

- `privacy.md` — Privacy Policy, served at `/privacy`.
- `terms.md` — Terms of Service, served at `/terms`.
- `index.md` — Landing page with links to both.
- `CNAME` — GitHub Pages custom domain (`legal.fractalthink.com`).

## Hosting

Hosted via GitHub Pages from `main`, root directory. Jekyll renders the front-matter `permalink:` values; no plugins required.

## Editing

These files are mirrored from the app repo under `docs/legal/`. The app repo is the source of truth — edit there, then sync the rendered files into this repo so the published versions and the in-app `PRIVACY_VERSION` / `TERMS_VERSION` constants stay aligned.

When publishing a substantive change, bump:
- `Effective date:` line at the top of each `.md`.
- `PRIVACY_VERSION` / `TERMS_VERSION` in the app repo's `services/consent.ts`.

Bumping forces existing users to re-consent on next launch.
