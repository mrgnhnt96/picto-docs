# picto-docs

Generated hosting for **<https://docs.picto.dev>**. Everything on the
`gh-pages` branch of this repo is *build output* — do not edit it here, it is
force-overwritten on every deploy.

## Where the source lives

The docs themselves are written and reviewed in the private `picto` repo
under `apps/docs/content/` (one markdown file per page), built with
[jaspr_content](https://pub.dev/packages/jaspr_content), and published here
by that repo's `.github/workflows/deploy-docs.yml` on every push to `main`
that touches `apps/docs/`.

## Why this repo exists at all

GitHub allows a maximum of one Pages site per repository, and one custom
domain per site. The `picto` repo already spends its site on the marketing
site + dashboard at <https://picto.dev>, so `docs.picto.dev` needs a
repository of its own. This is that repository, and it holds nothing else.

Found a mistake in the docs? Please report it against the picto repo (or
wherever you normally reach us) rather than here — a fix committed here
disappears on the next deploy.
