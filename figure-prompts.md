# Image prompts — 932 Pocahontas Drive report figures

Paste each prompt into Gemini, then drop the result onto the matching placeholder in the report.
Ask for a **16:9 or 3:2 PNG with a transparent or #08080B background**. If Gemini renders text
incorrectly, re-run with "render all labels exactly as written, no other text."

---

## Shared style block (prepend to every prompt)

> A clean, minimal data figure for a professional real estate market analysis. Dark background
> (#08080B, nearly black), no gridlines, no 3D, no glow, no drop shadows, no decorative icons,
> no gradients behind the data. Only three colors: off-white (#EEF1F5) for structure and neutral
> data, bright blue (#0099FF) for the highlighted data, and a deep red (#FF0033) used once for the
> single most important value. All labels set in a monospaced typeface, uppercase, generously
> letterspaced, small relative to the graphic. Flat vector look, precise alignment, generous
> empty space. Editorial, restrained, engineering-drawing quality — not an infographic, not a
> dashboard, no emoji, no clip art.

---

## FIGURE 1 — Days on market (section 04)

> [shared style block]
> Create a horizontal dot-plot with two rows on one shared horizontal axis representing days on
> market, 0 to 200 days.
> Top row, labeled "SOLD": six solid bright blue dots clustered tightly between 6 and 45 days on
> the left. Small caption under this cluster: "6–45 DAYS TO CONTRACT".
> Bottom row, labeled "ACTIVE, UNSOLD": four hollow off-white circles clustered between 139 and
> 190 days on the far right. Small caption: "139–190 DAYS, STILL LISTED".
> A single vertical dashed blue line at 60 days, labeled "60 DAYS".
> The visual point: two separated clusters with a wide empty gap between them.
> Title above the figure: "THERE IS NO MIDDLE GROUND".

## FIGURE 2 — Convergence on value (section 07)

> [shared style block]
> Create a convergence diagram. Three horizontal lines enter from different positions on the left
> and right and all terminate on one shared vertical line about three quarters across the frame.
> Line 1 starts at a point labeled "$825,000" and runs right to the vertical line.
> Line 2 starts further right at a point labeled "$900,000" and runs right to the vertical line.
> Line 3 starts at the far right at a point labeled "$1,250,000" and runs LEFT to the same vertical
> line, so the three arrivals converge from both directions.
> The lines and their start points are off-white; the vertical convergence line is deep red and
> slightly thicker, labeled in red: "INDICATED MARKET VALUE $1,075,000".
> The visual point: three independent starting values landing on one number.

## FIGURE 3 — Search brackets (section 08)

> [shared style block]
> Create a diagram of two overlapping price-search ranges on a horizontal price axis.
> An upper horizontal bar, filled in translucent off-white, spans from the left edge to the center
> and is labeled "SEARCH UP TO $1.1M".
> A lower horizontal bar, same treatment, spans from the center to the right edge, labeled
> "SEARCH FROM $1.1M UP".
> At the exact center, a vertical dashed off-white line marks $1.1M. A bright blue dot sits on that
> center line inside BOTH bars, labeled in blue: "$1,100,000 — IN BOTH".
> A hollow off-white dot sits slightly left of center inside the upper bar only, labeled in muted
> off-white: "$1,099,000 — IN ONE".
> The visual point: the round number is visible to two audiences, the number just under it to one.

---

## Optional — parcel map figure (section 02)

The parcel placeholder is best filled with a real county parcel map screenshot with annotations.
If you want Gemini to draw a stylized version instead:

> [shared style block]
> Create a simple top-down schematic of a single deep waterfront lot. A tall narrow rectangle,
> wider at the bottom (road) end than at the top (water) end, drawn in thin off-white lines on a
> near-black background. The top edge is water, indicated by a few thin horizontal blue lines and
> labeled "CINCO BAYOU · 53 FT FRONTAGE". A small blue rectangle at the top edge marks a dock and
> boathouse. A house footprint sits in the upper third of the lot. A dimension arrow runs the full
> length of the lot labeled "436 FT DEEP", and an area label reads "0.85 ACRES". No trees, no
> texture, no perspective — a survey diagram.
