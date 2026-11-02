# Ember Garden website

Static site for Ember Garden: a landing page (`index.html`) and the privacy
policy (`privacy.html`) linked from Google Play. No build step.

Hosted on GitHub Pages from its own public repo, since the game repo is
private. To publish changes, copy these files into that repo and push.

Contact email (in both HTML files): `embergarden.support@gmail.com`.
When the game is live, swap the "Coming soon" span in `index.html` for the
Google Play link noted next to it. If the app ever adds ads, purchases,
analytics or online features, update `privacy.html` (and its effective date)
and the Play Console Data safety form together.

Preview locally: `python -m http.server 8765 --directory website`
