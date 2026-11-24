# Melt9 AR Menu - simple pizza + REAL smoke picture (v34)

Based on v33, with the steam fixed the way BOSS asked.
No dome, no glass box, no cylinder - just the pizza,
appearing on the target photo, with real smoke rising.

Steam (dishes/steam.png):
- This is BOSS's own smoke.jpg picture, not a drawing.
  Its black background was turned into transparency,
  so only the white curling wisps show.
- Weight comes from the picture itself (bright, thick
  curling wisps) + opacity 0.65 - NOT from plane size.
- 5 small planes only (0.30 wide x 0.60 tall), across
  the pizza, staggered 700 ms apart, speeds 3.6-4.4 s,
  fading in at the bottom and out at the top.
- Steam rises straight up, it does NOT spin with the pizza.

Why v33 looked ugly: 12 planes, 0.36 wide, opacity 0.90 -
too big and too many, so the square edges of the planes
showed and the steam became a white block over the pizza.
Bigger size does not make smoke heavier - it makes it ugly.

Kept: fixed AR label, Add to cart + Photo in AR,
1-second flash, auto-spin, soft shadow + dark shadow
under the pizza (v33), self-hosted libs/ engine.
iOS (Quick Look) + Android (MindAR camera scan).

To change the steam: in index.html, search "REAL STEAM".
Heavier = raise "to: 0.65" (try 0.80). Lighter = 0.45.
