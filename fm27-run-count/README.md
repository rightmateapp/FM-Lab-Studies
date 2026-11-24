# FM27 Run Count Study: raw results

How many simulated matches do you need before a win percentage means anything? This folder holds every match result behind that study, so you can check the numbers yourself.

- Game: Football Manager 27, version 27.1.0
- Saves: three test saves, each with one club we manage: Leicester City (England), KuPS (Finland), Barcelona (Spain)
- Fixtures: three per save, nine in total, all at home
- Each fixture was simulated in 10 separate builds of 200 matches, so 2,000 matches per fixture and 18,000 overall
- Plus three single builds of Leicester City v Walsall with 1,000, 1,500 and 2,000 matches

A **build** is one fresh set-up of the same fixture, made from the same save on the same game day. Every build of a fixture uses the same two clubs, the same tactics and the same match date. The matches within a build are then played over and over from that one set-up.

Tactics, line-ups and the save were left exactly as they were, and nothing was edited.

## Files

| File | What's in it |
|---|---|
| `fixtures.csv` | One row per fixture: the overall win % across all 10 builds, plus the lowest and highest build |
| `builds.csv` | One row per build: win / draw / loss %, points per match, goals, xG and shots, all from our club's side |
| `matches/<fixture>/build-01.csv` … `build-10.csv` | Every match in that build: score, xG, possession, shots, passes, corners, cards and so on, for both clubs |
| `single-build-sizes/` | Leicester City v Walsall: one build each of 1,000, 1,500 and 2,000 matches, with a summary |

All percentages are from the perspective of the club we manage (the home side in every fixture).

## Quick look

| Fixture | Win % (all 10 builds) | Lowest build | Highest build |
|---|---|---|---|
| Leicester City v Walsall | 79.0 | 72.5 | 88.0 |
| Leicester City v Middlesbrough | 27.9 | 18.0 | 32.5 |
| Leicester City v Coventry | 19.9 | 13.5 | 23.0 |
| KuPS v Gnistan | 46.2 | 37.0 | 52.0 |
| KuPS v SJK | 28.4 | 22.5 | 38.0 |
| KuPS v AC Oulu | 25.6 | 20.0 | 34.0 |
| Barcelona v Sevilla | 82.8 | 79.0 | 87.0 |
| Barcelona v Real Madrid | 47.5 | 40.5 | 55.5 |
| Barcelona v Atlético Madrid | 67.0 | 59.5 | 76.0 |

| Leicester City v Walsall, single build | Win % |
|---|---|
| 1,000 matches | 80.8 |
| 1,500 matches | 85.7 |
| 2,000 matches | 74.2 |

## Licence

Free to use and share with credit to Right Mate (https://www.patreon.com/RightMate_Official). Football Manager is a trademark of Sports Interactive; this data was produced independently and is not endorsed by Sports Interactive or SEGA.
