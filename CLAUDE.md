# CLAUDE.md

## Commit authorship

Author every commit as Spencer so the work counts toward his GitHub contributions:

```
spencerwood1031 <spencerwood1031@gmail.com>
```

Pass it per commit rather than changing git config, for example:

```
git commit --author="spencerwood1031 <spencerwood1031@gmail.com>" -m "..."
```

Keep any Co-Authored-By trailers the session adds; they don't affect authorship.

## Commit time zone

Spencer is in New York. Commit in his time zone so GitHub puts the work on the right day
(the cloud machine runs on UTC, which pushes evening commits to the next day):

```
TZ=America/New_York git commit --author="spencerwood1031 <spencerwood1031@gmail.com>" -m "..."
```

## Publishing

When Spencer asks for a change to the site (or says anything along those lines), make it and
publish it to main right away; no need to ask first. If he's choosing between options, show
the options before publishing.

## Quotes

Never change the wording of a quote on your own. Copy it exactly as written in the source, even if
it reads oddly. Point out problems and let Spencer decide. Trims for brevity or style are fine only
when Spencer approves them and they are marked the standard way: … for cut words, [ ] for changed
or added words. Show him the full quote and the proposed version before publishing.
