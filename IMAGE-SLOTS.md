# Hitech website: image slots

Every replaceable photo has a slot name.

## Slots using Hitech's own plant photos (shot at MIDC Butibori)
| Slot | Source | Where it appears |
|---|---|---|
| `home-hero` | DSC00065 | Home hero |
| `about-hero` | DSC00160 | About Us hero |
| `mfg-automation` | DSC00046 | Home manufacturing; About "From material to finished system" |
| `mfg-blending` | DSC00212 | same (closest match, see note) |
| `mfg-fabrication` | DSC00216 | same |
| `project-crew` | DSC00192 | Home "Where capability goes to work"; Case Studies |
| `assurance-testing` | DSC00305 | Assurance, "Ask for the evidence" |

Note: no photo of the centralised blending silos was in the set. If one exists, replace `mfg-blending`.

## Slots using images supplied by the client for Industries & Applications
| Slot | Where it appears | Notes |
|---|---|---|
| `app-water` | Home panel 1; Industries | HDPE pipe discharging water. Looks AI-generated |
| `app-agriculture` | Home panel 2; Industries | Drip-irrigated field. Looks AI-generated |
| `app-urban` | Industries | Coastal road and city aerial. Real third-party project photo: confirm usage rights |
| `app-marine` | Home panel 5; Industries | Dredger laying a floating pipeline. Real third-party photo: confirm usage rights |
| `app-industrial` | Home panel 3; Industries | Plant pipework with flanges. Looks AI-generated, small (654 px) |
| `app-mining` | Industries | Pipeline on supports at a mine. Third-party photo: confirm usage rights |
| `app-cable` | Home panel 6; Industries | Trench with coloured ducts. Looks AI-generated |
| `app-solar` | Industries | Solar farm cable trench. Third-party photo (grey conduit, not HDPE duct): confirm usage rights |

## Still brochure stand-ins (replace before launch)
`app-sewerage`, `app-chemical`, `app-gas`, `app-fire` (about 230 px wide, soft on large screens) and `map-india`
(keep the same framing so the city pins line up).

## How to replace an image
1. Save the photo in `images/` with the slot name (for example `images/app-sewerage.jpg`).
2. In `index.html` search for `var IMAGES={};` and add a line: `IMAGES['app-sewerage']='images/app-sewerage.jpg';`
3. Upload the whole folder. (Or send the photos and we embed them into the single file.)

## Also needed for production
- A square favicon, and `og-image.jpg` (1200 x 630) for link previews.
- Optional: product photos for the Products page (plant set has good ones: DSC00218 tee fitting, DSC00074 pipes).
