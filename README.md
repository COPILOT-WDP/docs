# From Binder to Business

A free, source-grounded reference manual on starting and running an online Pokemon card
business, mined from hundreds of videos by operators with documented track records.

Published with [Mintlify](https://mintlify.com). Every push to `main` deploys the site.

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
