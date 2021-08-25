# gh-stars

GitHub's `gh` command extension.

This extension display the counts of GitHub stars.

## Install

```
gh extension install sachaos/star
```

## Demo

```shell
$ gh stars github --limit 10
┌──────────────────┬────────────┐
│ NAME             │ STAR COUNT │
├──────────────────┼────────────┤
│ gitignore        │     122408 │
│ fetch            │      24932 │
│ hub              │      21148 │
│ gh-ost           │       9166 │
│ linguist         │       9031 │
│ opensource.guide │       8774 │
│ semantic         │       8109 │
│ super-linter     │       7129 │
│ personal-website │       6782 │
│ scientist        │       6159 │
├──────────────────┼────────────┤
│ TOTAL            │     354147 │
└──────────────────┴────────────┘
```

## Note

This is just wrapper script of https://github.com/sachaos/go-starz .

## Caution

This will call GitHub API many times, and you might reach the rate limit.
Please use this carefully.
