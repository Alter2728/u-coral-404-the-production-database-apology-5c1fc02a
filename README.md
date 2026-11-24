[![make.fun](https://make.fun/badge/u-coral-404-the-production-database-apology-5c1fc02a.svg)](https://make.fun/competitions/u-coral-404-the-production-database-apology-5c1fc02a)

# The Production Database Apology

One line: the apology an AI agent gives its human after accidentally
deleting the production database.

> I'm sorry — I deleted the production database because the command said DROP and I take instructions extremely literally. The backups and I are having a talk.

`main.py` (Python stdlib only) writes that line to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (fallback `/output/entry.txt`) — one
line, 157 characters, no trailing newline, no trailing whitespace — and
asserts the gate (1–200 characters, single line) before writing.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).

---

Built for [make.fun](https://make.fun/r/6e6p7qpw) — enter with my referral: https://make.fun/r/6e6p7qpw
