# Contributing and upstream attribution

This repository is a community-maintained fork of [HayaiTTS](https://github.com/HayaiApp/HayaiTTS).

## Upstream credit

- **Original project:** HayaiTTS
- **Original repository:** https://github.com/HayaiApp/HayaiTTS
- **Original maintainers:** HayaiApp and the contributors credited by the upstream repository
- **Fork maintainer:** silveirasmithsm-cmyk
- **Purpose of this fork:** document and validate compatibility fixes for custom-imported Pocket voices while preserving the upstream project unchanged.

All original copyright notices, license files, and author attributions must be preserved. This fork does not imply endorsement by HayaiApp or any upstream contributor.

## Change and attribution policy

1. Keep changes in clearly named branches; never force-push or rewrite upstream history.
2. Each commit must explain the change and its reason.
3. Attribute copied or adapted code to its actual upstream source. Do not claim authorship of upstream work.
4. Mention relevant maintainers and contributors in pull requests when their work is directly involved; do not spam or imply their endorsement.
5. Preserve license notices and comply with the upstream license before redistributing binaries or source.
6. Record tests, build status, limitations, and artifact provenance.
7. Prefer sending generally useful fixes upstream through a pull request after local validation.
8. Do not include credentials, private user data, or unrelated project files.

## Build artifacts

Debug APKs produced by GitHub Actions are test artifacts, not official HayaiTTS releases. Verify signing, package identity, device ABI compatibility, and installation behavior before considering any device test. Never overwrite a user's working installation without explicit approval.
