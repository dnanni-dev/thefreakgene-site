# thefreakgene.com

Source for [thefreakgene.com](https://thefreakgene.com), deployed with Cloudflare from this repo.

## How it works

- Every push to `main` triggers an automatic deploy on Cloudflare.
- The site is plain static files at the repo root. `index.html` is the home page.
- No build step: in Cloudflare, leave the build command empty and set the output directory to `/`.

## Editing

1. Edit or add files (directly on GitHub, or locally and push).
2. Commit to `main`.
3. Cloudflare redeploys within a minute or so.
