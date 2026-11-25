Discovery card art
==================

Oholiab's web-sized card art (25 Nov 2026), copied as-is (600 x 838 WebP, RGBA,
transparent rounded corners, same spec as the earlier Wix promo fronts).

  discovery/cards/front/{period}-{event}-{slug}.webp     in-game picture side
  discovery/cards/back/{period}-{event}-{slug}.webp      in-game red side
  discovery/cards/mystery/{period}-{event}-{slug}.webp   unlock-reveal (no period/event numbers)
  discovery/cards/rules/53-… and 54-…                    two rules cards (not in the Discovery deck)

{period}-{event} is the card id from Solomon's card-index (period and event_number),
e.g. Creation of Heavens and Earth is 1-2, not the global set number 02.
{slug} is the lowercase hyphenated title from O's filenames (the part after NN-
and before -front / -back / -mystery-front).

Examples:
  cards/front/1-2-creation-of-heavens-and-earth.webp
  cards/back/1-2-creation-of-heavens-and-earth.webp
  cards/mystery/1-2-creation-of-heavens-and-earth.webp

All 52 Bible Event cards have front, back and reveal art in the data. A card is
only dealt when `playable` is true. The current playable pool is still the 13
promo cards (7 starter, one per period, plus 6 unlocks). Opening the full 52
is a small data change once the starter size is decided; do not flip that yet.
