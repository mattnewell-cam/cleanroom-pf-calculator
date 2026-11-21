# Cleanroom PF Calculator

Add more filtration or increase the positive pressure? For a room or house pressurised with
filtered air, this compares options of (overpressure, filter efficiency) by time-averaged
protection factor, counting both the air that passes through the filter and the unfiltered outdoor
air that wind pushes in through leaks.

**Live page:** https://mattnewell-cam.github.io/cleanroom-pf-calculator/

Wind infiltration is modelled hour by hour from 5 years (2019–2023) of NOAA ISD-lite airport
records for the 60 largest US metros: airport wind scaled to house height for the terrain, wall
pressure coefficients and gust levels from published low-rise building data, house and room
pressures solved from power-law leak flows (exponent 0.65) with a fixed-flow supply fan. The
page's "How it is calculated" section gives the steps and sources. The page is a single
self-contained HTML file with the model results embedded.
