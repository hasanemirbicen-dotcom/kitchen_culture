# What the Table Says

**30 Day Map Challenge · Day 13 · Interactions**

Does a region's kitchen predict its temperament? This is a tongue-in-cheek interactive map of Europe and Türkiye that crosses two things: how intense the table is, and how expressive the people around it are said to be.

**Live map:** https://hasanemirbicen-dotcom.github.io/kitchen_culture/

## What it shows

- **Bivariate map** of 43 European countries and Türkiye's seven regions. Redder means a more intense table, bluer a more expressive character, dark aubergine both.
- **Türkiye close-up** with the seven geographic regions labelled.
- **Reading panel** for each place: its kitchen, signature dishes, paired scores and a short interpretation. Hover to read, click to pin.
- **Scatter plot** of every place on the two axes, which also serves as the map legend.

## How the scores work

Each place gets six scores from 0 to 10.

| On the table | Around it |
| --- | --- |
| Spice and heat | Expressiveness |
| Shared plates | Open-door hospitality |
| Time at the table | Spontaneity |

The map colour crosses the average of each column, split into low (under 4), mid (4 to 6.5) and high (6.5 and over).

## Caveats

- The scores are **editorial judgments** drawn from culinary tradition and popular reputation. They are not survey data.
- They describe table customs and stereotypes, never individual people.
- Region borders inside Türkiye are approximated from province centres and do not match the official boundaries exactly.
- Russia, the Caucasus and other hatched areas are not scored.

## Files

- `index.html` is the whole map in a single file. The boundary data is embedded, so it needs nothing else. Open it in a browser or serve it with GitHub Pages.

## Credits

- Boundaries: [Natural Earth](https://www.naturalearthdata.com/) via [world-atlas](https://github.com/topojson/world-atlas)
- Built with [D3](https://d3js.org/) and [TopoJSON](https://github.com/topojson/topojson)
- Fonts: Bricolage Grotesque, Instrument Sans, DM Mono (Google Fonts)
