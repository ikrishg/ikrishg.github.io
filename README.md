# ikrishg.github.io

The GitHub Pages root for the ikrishg account.

## What it does

- `index.html` redirects every visit to https://krishg.com, with a JavaScript redirect and a `noscript` meta refresh fallback.
- `.well-known/atproto-did` serves the AT Protocol (Bluesky) DID used to verify the handle. `_config.yml` tells Jekyll to publish the `.well-known` folder, which it would otherwise skip.

Project sites such as `ikrishg.github.io/pikoto.css` are served from their own repos, not this one.

## Deploying

GitHub Pages builds from `main` automatically. There is nothing to build locally.
