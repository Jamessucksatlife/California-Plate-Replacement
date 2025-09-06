# California Plates Pack (FiveM, Runtime Texture Replacement)

This resource replaces ALL GTA V license plates with **California plates** (NPC + player vehicles).
No .ytd editing needed — it uses runtime texture replacement, so it's fully drag-and-drop.

## Install
1) Drop the `caliplates` folder into your server's `resources`.
2) Add `ensure caliplates` to your `server.cfg`.
3) Restart the server.

## Included Styles (mapped to GTA slots)
- plate01 → California Standard (white)
- plate02 → California Sunset (white with gradient accent)
- plate03 → CA Legacy Blue
- plate04 → CA Legacy Black
- plate05 → CA Exempt

## Notes
- vMenu/custom plate text still works (this only changes the background textures).
- If your game build uses additional plate slots (plate06, yankton), you can duplicate a mapping in `client.lua` and point it to another image.
- You can swap any image by replacing the PNG in `images/` and restarting the resource.

## Credits
- Pack made by Jamessucksatlife.
- Textures are simplified California-style designs for RP use.
