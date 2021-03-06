---
layout: top
title: Changelog
---

### Todo

{% if jekyll.environment != "production" %}
#### Private

#### Public
{% endif %}

- More characters!
- Document workflow on [wiki](https://github.com/drakeirving/puff-hitbox-viewer/wiki)
- Improve tools for contributions

### Changelog

{% if jekyll.environment != "production" %}
#### Pre-release

{% endif %}

#### v1.3.0
- Added Isabelle!

#### v1.2.6
- Piranha Plant updated animations (hurtboxes, timings)

#### v1.2.5
- More Safari quirks

#### v1.2.4
- Fixed various quirks causing app to not work on older versions of Safari (thanks apple)

#### v1.2.3
- Implemented URL query param for linking to a specific frame of a move (`f`)

#### v1.2.2
- Implemented URL query params for linking to a specific character and/or move (`char`, `move`)

#### v1.2.1
- Added loop controls, cursor changes on hovering controls
- Implemented move transition parameter
- Extended autocancel display to also have the early windows

#### v1.2.0
- Added Piranha Plant!
- Set up app for multiple characters, hopefully without too much going wrong
- Updated Jigglypuff animations to include hurtbox visualizations (EyeDonutz)

#### v1.1.0
- Implemented timeline visualizations
  - Active frames
  - FAF
  - Autocancel
- Implemented tooltips and added to various things
- Added Grab type and color mapping for grabs
- Adjusted colors to match CrossMod output
- Added hitbox parameter for custom colors
- Added hitbox parameter for additional move notes
- Fixed some bad things

#### v1.0.6
- Implemented hitbox detail table, minor adjustments

#### v1.0.5
- Added frame slider

#### v1.0.4

- Switched clips over to h264 as webm still unsupported on some browsers
- Frame counter now seeks to frame
- Self-hosting fonts to minimize loading times

#### v1.0.3

- Added frame counter  
- Fixed a ton of bugs caused by FP inaccuracies by being way more rigorous about frame timing and seeking
  - End of some clips caused video stalling, infinite event calls, some other nonsense
  - Chrome: frame timing off by one due to playback engine I guess, caused jittering at clip end (esp. combined with above)

#### v1.0.2
- Added FAQ and changelog pages
- Added more links to places

#### v1.0.1

- Changed video loading
- Made favicon work
- Small bugfixes

#### v1.0.0

- Site first published
