Discovery card art drop folder
================================

Mystery (unlock reveal) fronts, already in this repo:
  discovery/cards/mystery/{period}-{event}-{slug}.webp

Normal (in-game) fronts, to be added when Oholiab delivers web versions of all 52:
  discovery/cards/front/{period}-{event}-{slug}.webp

Size and format (match the current promo fronts served from Wix):
  600 x 838 pixels, WebP, RGBA, transparent rounded corners.

{period}-{event} is the card id from Solomon's card-index (period and event_number),
e.g. Creation of Heavens and Earth is 1-2, not the global set number 02.
{slug} is the lowercase hyphenated title, the same slug O used on the mystery
files (the part after the leading NN- and before -mystery-front).

Examples:
  cards/mystery/1-2-creation-of-heavens-and-earth.webp
  cards/front/1-2-creation-of-heavens-and-earth.webp
  cards/front/1-1-gods-plan-to-create-a-holy-family.webp

A card joins play only when it is marked playable and has both a front and a back.
The 13 promo cards already play with their existing Wix fronts and backs.
When a new front is dropped here, set that card's `front` to this path and
`playable` to true, and add a `back` (a back image is also required before it
can be dealt). Do not change the current playable pool until that art is in.
