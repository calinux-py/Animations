# Dropball

A minimal canvas animation of a ball bouncing between two ground points, each impact triggering a water-drop ripple effect.

## What it does

A white ball arcs back and forth between two fixed platforms. On each landing, a short horizontal line bursts outward from the contact point — starting tight and bright, expanding and thinning like a water surface ripple, then fading out before the ball returns.

- Parabolic arc with gravity curve
- Squash \& stretch on impact and launch
- Water-drop ripple lines (expand + fade, no glow)
- Seamless infinite loop


## Usage

Just open `index.html` in a browser. No dependencies, no build step.



## Customization

All the key values are constants at the top of the script:

| Constant | Default | Description |

|---|---|---|

| `LEFT\_X` / `RIGHT\_X` | `90` / `210` | X positions of the two bounce points |

| `BOUNCE\_Y` | `248` | Ground contact Y |

| `PEAK\_Y` | `78` | Arc peak Y |

| `BALL\_R` | `12` | Ball radius in px |

| `CYCLE` | `850` | Duration of one half-arc in ms |

| `RIPPLE\_DURATION` | `620` | How long each ripple lasts in ms |




