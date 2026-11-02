# uhifadhi privacy statements

The privacy statements of the uhifadhi field applications, one page per app,
served by GitHub Pages from `main` at `privacy.uhifadhi.org`. This is the
address an app store listing points at, and the page a person reads before
pressing Allow.

## Contents

- [The statements](#the-statements)
- [Where the text comes from](#where-the-text-comes-from)
- [Serving](#serving)

## The statements

| App | Page | Describes |
| --- | --- | --- |
| Doria | [`/doria/`](doria/index.html) | Uhifadhi Doria 0.5.5, dated 2 November 2026 |

A statement is dated and names the app version it describes. When a release
starts collecting something new, or stops, the statement changes with that
release and its date changes with it.

## Where the text comes from

The text is written once, in the design workspace that holds every uhifadhi
screen, and built into this site with "your organisation" where an
installation prints its own name. An installation of uhifadhi may serve the
same statement itself, at `/handset/privacy`, printing the organisation that
runs it. The two are the same words.

## Serving

`index.html`, `doria/` and `assets/` are served by GitHub Pages from `main`.
`CNAME` attaches the domain; the DNS record is a CNAME from `privacy` to
`utafitilabs.github.io`, as `downloads.uhifadhi.org` has. The page is
dependency-free: hand-written HTML and one stylesheet, the same one the
downloads page uses.
