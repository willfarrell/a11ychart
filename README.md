# A11yChart
Accessibility focused charting library

## Docs
- normalized pulled out
- no IE support, add in polyfill details
- no animation -> plugin
- line needs to pass in interpolations

## TODO
- [ ] pick supported colours, points, dashes, patterns
- [ ] add focus ring to chart elements
- [ ] CI/CD
- [ ] npm modules
- [ ] docs (gh-pages)
- [ ] docs domain `a11ycharts.js.org`
- [ ] resize causes duplicates to appear
### Bar
- [ ] add option to remove space between bars (x-axis), allow % of col to be used
### Box
- [ ] Build
### Line
- [ ] Add support for scatter plot
- [ ] Add ability to choose size of icon (bubble type) (future)
- [ ] Add option to allow stacked area (See stacked bar) (future)
### Pie
- [ ] Add background fill to label?

## Feature Scoping


- chart types [list](https://datavizcatalogue.com)
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
    - https://tympanus.net/codrops/2015/07/16/styling-svg-use-content-css
    - https://www.heropatterns.com/
    - https://iros.github.io/patternfills
- [x] support treeshaking, small codebase
- [ ] support streams (future)
- [ ] Alert user when chart changes (external)

This library core logic is based off the [Chartist.js](https://gionkunz.github.io/chartist-js/) library which is sadly no longer maintained. Huge thanks to @gionkunz and the Chartist community for building such a great library, this project would not exist without them.
