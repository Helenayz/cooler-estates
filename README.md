# Cooler Estates

Shade the estate from the first sketch. A hackathon prototype for *Cooler Estates, Smarter Design*: an early-stage design tool that scores building layouts and tree planting by outdoor shade in Singapore's hottest hours.

- **Project page:** <https://helenayz.github.io/cooler-estates/>
- **Tool:** <https://helenayz.github.io/cooler-estates/app.html>

## What the tool does

1. **Massing.** Enter the planning brief (plot ratio, site coverage, height limit, floor-to-floor). The tool generates six building layouts across six block typologies and ranks them by outdoor shade at 11:00, 13:00 and 15:00 on the equinox. The architect picks one, then drags, rotates or re-heights blocks while the shade updates live.
2. **Landscape.** The confirmed layout gets walking routes from the entrances and bus stop, activity areas and seats. Three ways to plant the same 40 trees are compared on shade at 13:00, seats in shade and the longest unshaded walk. The chosen scheme can be checked in 3D through the day and exported as JSON.

## Method and limits

- Geometric shadow projection on a 2 m grid. Equinox only, at 11:00 / 13:00 / 15:00; each moment stands for 2 h. A tree canopy transmits 20 % of sunlight.
- Shade is not thermal comfort. Wind, UTCI and the annual sun path are not modelled yet.

## Run locally

Everything is static. Open `index.html` or `app.html` in a browser. The fonts and the 3D view load from Google Fonts, cdnjs and jsDelivr, so they need internet access.
