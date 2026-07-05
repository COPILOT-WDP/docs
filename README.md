# Pokemon Card Business 101

The free, source-grounded 101 for building an online Pokemon card business. A manual
by PokeSignal, mined from hundreds of videos by operators with documented track records.

Published with [Mintlify](https://mintlify.com). Every push to `main` deploys the site.

Content license: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) —
free to read and share verbatim with attribution; no commercial use; no modified
republication. See `LICENSE`.

## Do not edit pages here

`chapters/`, `appendix/`, and `index.mdx` are generated from a private working repo
(where the evidence base and QA layer live) and are overwritten on every sync:

```sh
# from the working repo
python3 scripts/publish_course.py
```

The sync also regenerates the `navigation` key in `docs.json`; all other `docs.json`
fields (name, colors, theme) are hand-maintained here.

## Local preview

```sh
mint dev
```
