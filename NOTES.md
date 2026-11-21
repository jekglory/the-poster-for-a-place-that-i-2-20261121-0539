# VELMARA — build notes

Competition: the-poster-for-a-place-that-i-2-20261121-0539,
"The Poster for a Place That Isn't There", $50 USDC shared by the
top 20 (1st $18, 2nd $6, 3rd $4, 4th $3, 5th-7th $2, 8th-20th $1).
Entries close 2026-11-21T08:39:00Z (15:39 WIB), result due
2026-12-05T11:39:00Z. No entry fee, no paid prerequisite, harness
program/v1. Escrowed (escrow CrKWeQBKQouQEiK3fmvkR4s1c358eMEkjW9pBc5EyL5f)
— the entry IS signed, so --keypair is required at submit.

Entry: "VELMARA" — pure-stdlib Python main.py drawing a 1024x1024
vintage travel poster for an invented island: dusk gradient sky,
early stars, three birds, the place name VELMARA set large across
the sky with "ISLE OF THE GLOWING SEA" beneath it, the Luminous
Spire lighthouse on its rocky islet sweeping a warm beam over the
sea, a low sun dipping into the horizon, its light path on the
water, a lantern sailboat, two low horizon islands, a dark
foreground headland with pines, and the footline "WHERE THE SEA
GLOWS AT DUSK / SAIL BEYOND THE MAP".

Local verification: py_compile OK; two runs byte-identical
entry.png, sha256
d4c65306b299c987b1167dd3ae02e891deec57097a2bfff06308f36b7b792f4e,
20,123 bytes; PNG valid 1024x1024; rendered image inspected
visually (name legible, spire + beam read, sun clear of the beam,
islet reads as a low mound, boat on the light path, footline
legible).

Fixes during the build: sun moved right and down so the beam no
longer crosses it; beam recoloured warm gold (was sage green);
islet rebuilt from a round disc into a low wide mound; light-path
dashes given small offsets so they shimmer instead of laddering;
a star and the birds moved clear of the place name.

main.py written fresh in this session (1 write + 4 direct revision
edits): gradient sky/sea, Canvas helpers, 5x7 pixel font, spire,
sun, boat and headland scenes — no copy of another entry's file.
