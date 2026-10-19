# The Voice of Ming

A synthesized engine sound for the Tesla in-car browser, driven by GPS speed.
Pure static HTML + Web Audio — no server, no samples.

**Current voice:** 2006–2015 Mazda MX-5 (NC), 2.0 L MZR inline-4, muffler delete.
7,200 rpm redline, NC 6-speed ratios (3.815 / 2.260 / 1.640 / 1.177 / 1.000 / 0.832, 3.909 final, 205/50R16),
straight-pipe rasp, highway drone, and crackle on lift-off.

- **GPS drive**: speed comes from `navigator.geolocation.watchPosition` (needs HTTPS, e.g. GitHub Pages).
- **Test drive**: a slider stands in for speed so you can try it while parked.
- Throttle is guessed from acceleration, so it short-shifts when cruising and revs out when you floor it.
