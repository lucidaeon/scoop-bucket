# lucidaeon/scoop-bucket

A [Scoop](https://scoop.sh) bucket for lucidaeon's command-line tools.

## Install

```powershell
scoop bucket add lucidaeon https://github.com/lucidaeon/scoop-bucket
scoop install starcat
scoop install blackmoon
```

Don't have Scoop yet? `irm get.scoop.sh | iex` (if PowerShell blocks it, run
`Set-ExecutionPolicy RemoteSigned -Scope CurrentUser` first).

## Tools

| tool | what it does |
|---|---|
| [starcat](https://github.com/lucidaeon/mediumcoeli) | ephemeris computation + table presentation |
| [blackmoon](https://github.com/lucidaeon/mediumcoeli) | reads / merges / writes astrology chart formats |

Each manifest tracks the latest Windows release; `scoop update` picks up new
versions as they ship.

## Note on SmartScreen

The binaries are currently unsigned; on first run Windows SmartScreen may warn
("Windows protected your PC"). Authenticode code-signing is on the roadmap.
