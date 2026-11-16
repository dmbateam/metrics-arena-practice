# Metrics Arena — solo

A single-player practice version of **Metrics Arena**, the d.MBA *Business and Design Metrics* game.

Eight companies come to you with a problem. Three things could be wrong with each one, and one of them really is. You read the numbers (four funnels, then four P&Ls), ask one free question to see what is normal for that kind of company, then bet 100 chips on what is wrong. All 100 chips on the real problem scores 100 points, so the best possible score is 800. Three bots play alongside you for comparison.

At the end, results are emailed to the player and the d.MBA team via the shared EmailJS templates (same setup as the other solo games).

Round content and scoring mirror the facilitated multiplayer version (`metrics-arena`). The game data inside `index.html` is exported from that game's engine, not typed in by hand.

## Run

It's a single static file — just open `index.html`, or serve the folder:

```bash
python3 -m http.server 8111   # then open http://localhost:8111
```

No build step, no server code.
