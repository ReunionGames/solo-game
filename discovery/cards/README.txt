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

All 52 Bible Event cards are playable and have front, back and reveal art.
New players start with the original 13 promo cards (STARTER_IDS). The other 39
join the deck one at a time after a perfect run.
