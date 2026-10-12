# Security policy

This covers [rookdex.app](https://rookdex.app) and every repository in the `rookdex` organization.

Rookdex is a static site. There are no accounts and no server-side data. Your progress lives in your own browser, and exports are files on your own device. So the things I care most about are:

- script injection, for example through an imported file or a note
- anything that gets around the Content Security Policy
- the service worker serving stale or tampered files
- a dependency or CI step that could ship code I didn't write

## Reporting a vulnerability

Please don't open a public issue. Report it privately instead: go to the repository's **Security** tab and choose **Report a vulnerability**. For the app itself, that's [rookdex/rookdex](https://github.com/rookdex/rookdex/security/advisories/new). Only I can see the report.

Tell me what you found, how to reproduce it, and what an attacker could do with it.

## What to expect

I build Rookdex on my own, so I can't promise fixed response times. I aim to reply within a week and keep you posted while I work on a fix. Only the live site and the `main` branch get fixes. When it's fixed, I'll credit you in the advisory unless you'd rather stay anonymous.

Thanks for helping keep Rookdex safe.
