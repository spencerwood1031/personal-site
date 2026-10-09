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
