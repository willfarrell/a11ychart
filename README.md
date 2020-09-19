# a11ychart
Accessibility focused charting library

## Feature Scoping

- engine
  - svg
  - canvas
    - [AOM](https://wicg.github.io/aom/)
- chart types
  - scatter
  - line
  - bar
  - bar-stacked
  - box
  - pie
  - donut
- scales
  - x,y
  - time,y
  - log
  - x-axis full preview w/ zoom handles
- provide table of data
- figure description auto generated from data
  - summary of points
  - summary of series (when >1)
  - describe graph pattern in words (tensorflow?)
  - option to override with custom
- ability to play audio representing the data
  - Fade from left to right speaker for x-axis
  - low to high pitch for y-axis
  - say name of series before playing
  - check audio player best practices
- Page Zoom: points, lines, bars scale with page (auto adjust scales?)
- Points/Line/Fill
  - Set colour at chart, series, point level, have presets
  - colours must meet 7:1  contract ratio
  - Set shape/icon at chart, series, point level
  - points have option to have line above/below (Data Science)
  - lines have dash pattern (morse code for series name/id)
  - bar fill has line pattern
    - https://www.heropatterns.com/
    - https://iros.github.io/patternfills/
    - https://www.svgbackgrounds.com/#geometric-intersection
- support treeshaking, small codebase
- support streams
- Alert user when chart changes (external)
