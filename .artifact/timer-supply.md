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
    caption: A countdown with 4 minutes 30 seconds left, and the grey wedge behind the digits
    alt: Large black monospace digits reading 4m30s on a white page with a pale grey wedge sweeping out from behind them
  - src: presets.png
    caption: The page before a timer starts, with the 05m00s placeholder and seven presets
    alt: Grey monospace digits reading 05m00s on a white page, with a row of pale presets below from 5m to 60m
unconfirmed:
  - date
---

Timer Supply is a countdown timer on one web page. The page is a single text field. Typing a duration such as 5m, 90s or 2:30 and pressing Enter starts the countdown. Clicking one of the seven presets below the field, from 5 to 60 minutes, starts it too. The duration is also written into the address after the #, so a link such as timer.supply/#10m starts a ten-minute timer when it opens.

During a countdown the remaining time is set in large Courier digits. A grey wedge behind the digits marks the remaining time as an angle on a clock face, starting at the current minute. When the time runs out, a GIF covers the page.

The site is one HTML file of 5 KB with no dependencies. It has no accounts and no settings.

HTML, CSS, JavaScript. 2019.
