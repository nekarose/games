# Now, Labs — game links

Served at https://nekarose.github.io/games/

| Path | What it does |
|---|---|
| `/games/` | Every game, with a button for this device's store |
| `/games/dumbodrop/` | Dumbo Drop: iPhone → App Store, Android → Google Play, PC → both buttons |
| `/games/dumbojump/` | Dumbo Jump (Google Play shows "coming soon" until the listing is public) |

Add `?src=tiktok` (or `instagram`, `youtube`, …) to any link. On Android it reaches Google Play as the
install referrer, so Firebase Analytics reports it as the first-user source.

These files are generated. Edit `build_site.py` (kept in `~/Documents/store/nowlabs_site/`) and rebuild;
don't edit the HTML here by hand.

Official material (app-ads.txt, privacy policies) lives in the root site repo `nekarose.github.io`, not here.
