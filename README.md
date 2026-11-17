# Advent of Code — NDC solutions

A collection of Advent of Code puzzle solutions written in `.ndc`, organized by year.

## Progress

| Year | Completed | Progress |
| --- | ---: | ---: |
| 2015 | 7 / 25 | 28% |
| 2016 | 11 / 25 | 44% |
| 2017 | 9 / 25 | 36% |
| 2018 | 17 / 25 | 68% |
| 2019 | 1 / 25 | 4% |
| 2020 | 0 / 25 | 0% |
| 2021 | 1 / 25 | 4% |
| 2022 | 0 / 25 | 0% |
| 2023 | 2 / 25 | 8% |
| 2024 | 25 / 25 | 100% |
| 2025 | 12 / 12 | 100% |
| **Total** | **85 / 262** | **32%** |

Progress counts distinct day numbers with at least one solution. Alternative, fixed, and experimental versions are preserved in the repository but count once toward completion. Advent of Code has 25 puzzles per year through 2024; 2025 and later years use 12 puzzles.

## Running

Solutions live in `<year>/<day>.ndc` and read their puzzle input with `read_stdin()`. Inputs are stored (gitignored) in `input/<year>/<day>.txt` and fed to the script by [`aoc`](../aoc-cli):

```sh
aoc get 5 -y 2015   # download input/2015/5.txt (needs COOKIE in .env)
cd 2015 && aoc run 5   # year is inferred from the directory
```
