# ramp-docs

Public hosting for the Ramp documents that are shared with teachers and
institutions. Nothing here is source code: the product repository is separate
and private.

Each file is a generated copy. The working copies live in the product
repository under `docs/`, carry candid editing notes in a trailing HTML
comment, and are stripped by `npm run share:refresh` before they are copied
here. **Do not edit anything in this repository by hand**: the next refresh
overwrites it, and a hand edit is how a sent document stops matching the
working one.

`robots.txt` and a `noindex` tag keep these out of search results. They are
public so that a link works without a login, not so that they are found.
