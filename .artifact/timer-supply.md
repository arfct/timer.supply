---
title: Timer Supply
date: 2019-01
category: product
tags:
  - web
  - time
url: https://timer.supply
links:
  source: https://github.com/arfct/timer.supply
media:
  - src: countdown.png
    caption: With 4 minutes 30 seconds left, the wedge behind the digits spans four and a half minutes of the dial
    alt: Large black monospace digits reading 4m30s on a white page with a pale grey wedge sweeping out from behind them
  - src: presets.png
    caption: Before a timer starts, the field shows 05m00s as a placeholder above the seven presets
    alt: Grey monospace digits reading 05m00s on a white page, with a row of pale presets below from 5m to 60m
unconfirmed:
  - date
---

Opening timer.supply/#10m starts a ten-minute countdown, because Timer Supply writes every duration into its own address after the #. Opened without one, the page is a single text field with seven presets beneath it, from 5 to 60 minutes. Type 5m, 90s or 2:30 and press Enter, or click a preset.

While the timer runs, the time left is set in large Courier digits, and a duration entered without seconds is counted in whole minutes until the last one. Behind the digits is a wedge of pale grey, drawn as on a clock face, which starts at the current minute and covers as many minutes of the dial as remain. When the time is up a GIF fills the page, chosen at random from a list of one.

The whole site is one HTML file of 5 KB, with no dependencies, no accounts and no settings.

HTML, CSS, JavaScript. 2019.
