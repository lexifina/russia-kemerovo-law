<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Kemerovo Oblast (Kuzbass) only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 05:27 UTC, Kemerovo Oblast (Kuzbass): Official Internet Portal of Legal Information (region42): 12 addresses read; 1 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Kemerovo Oblast (Kuzbass): Official Internet Portal of Legal Information (region42)](http://publication.pravo.gov.ru/documents/block/region42) | `zakony-<year>/` | daily | 2026-11-27 05:27 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:26](checks/2026-11.md#ru-pravo-kemerovo-20261127t052630z) | pravo-kemerovo | 12 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-kemerovo-law/compare/fc0048626707...2cd53379033c) |
| [2026-11-26 05:31](checks/2026-11.md#ru-pravo-kemerovo-20261126t053119z) | pravo-kemerovo | 12 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-kemerovo-law/compare/64d5118ef430...05965d500d59) |
| [2026-11-25 05:36](checks/2026-11.md#ru-pravo-kemerovo-20261125t053621z) | pravo-kemerovo | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 13:45](checks/2026-11.md#ru-pravo-kemerovo-20261124t134527z) | pravo-kemerovo | 13 | 17 | 0 | 0 | 0 (0) | changes found | [4](https://github.com/lexifina/russia-kemerovo-law/compare/398cfcc0f177...5d9617e3033c) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
