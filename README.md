# Exit Replay Simulator — train the exit, not the entry

A tiny, free, browser-based drill for the moment most traders actually
lose money: **after** entry, when a candle closes against you and you
have to choose — HOLD or OUT — right now, with no hindsight.

Built as the practice core of **Reps**, a practice terminal that
enforces your trading rules while you practise (session locks,
stop/target truth rules, discipline reports).

## How to play

Open `index.html` in any browser. No install, no server, no account.

- Five built-in trades. Candles reveal **one at a time**
  (NEXT CANDLE button).
- Each trade shows the entry, stop-loss, take-profit, and an orange
  **exit line** — for a short, the high of the entry candle; for a
  long, its low.
- After every new candle you must press **HOLD** or **OUT** before
  the next candle prints.
- The rule being trained: **the first candle that closes beyond the
  exit line is the test.** OUT = you respected it. HOLD = you failed
  it. Stop and target hits inside a candle close the trade
  automatically.
- You get an execution score (5 trades in `index.html`). P&L is
  shown, never graded — discipline is the score.

`exit-replay-1000.html` is the long-form variant with a 1000-candle
stream for extended sessions.

## The five lessons in the default set

1. Exit-line close (short) — the basic test.
2. Take-profit auto-hit — do nothing correctly.
3. Wick vs close + time exit — a wick through the line is not a close.
4. Stop-loss auto-hit — the plan protects you if you let it.
5. Exit-line close (long) — the mirror image.

## Why this exists

Most prop-firm challenges are failed on behaviour after entry —
holding losers past the plan, not on finding entries. This drill
isolates that single skill and scores it honestly.

## License

MIT — see [LICENSE](LICENSE). Free to use and share.
Trading involves risk; this is a training drill, not financial advice.
