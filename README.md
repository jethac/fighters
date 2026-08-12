# Fighter Tech Tree

**[Live → fighters.jethachan.net](https://fighters.jethachan.net)**

An interactive development tree of real-world **fighter aircraft** — from the
last piston fighters of the late 1930s to the 5th generation. A sibling of
[tietechtree.jethachan.net](https://tietechtree.jethachan.net), reskinned in
light-blue-on-navy.

- **Timeline**: horizontal position = first flight, with labeled eras and the
  end of WWII marked as the dawn of the jet age
- **Arrows**: solid = direct development · dashed = influence · dash-dot =
  license production or copy (including unlicensed ones — Nesher/Kfir, Avia
  S-199, Shenyang J-11B/J-15) · `?` = disputed
- **Variant chains**: F-15A→C / B→D→E→K→EX, F-16, F/A-18, F-35, Su-27 family —
  collapsible with the Variants toggle
- **Detail panel**: manufacturer, operator designations (Mustang Mk / CL-13
  Sabre / F-7 / CF-188…), summaries, per-arrow "what changed" notes, and links
  to Wikipedia and Grokipedia
- Photos are hotlinked from Wikimedia Commons with per-image credit

No dependencies, no build step — plain HTML/CSS/JS + SVG.

## Run locally

```bash
python -m http.server 8124
```

## License

[MIT](./LICENSE) © 2026 Jetha Chan

Facts draw on Wikipedia (CC BY-SA); Jane's All the World's Aircraft remains
the print gold standard. Photographs stay under their stated licenses with
credit shown per image. Summaries and arrow notes were LLM-drafted (Claude)
and fact-checked against Wikipedia — corrections welcome via issues.
