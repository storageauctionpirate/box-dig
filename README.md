# Storage Pirate: Box Dig (prototype)

Open a storage unit, grab a box, dig the grid for treasure. Numbers show how many hazards touch a square.
Call it a wrap to bank the box's haul, or keep digging and risk busting it all.

Play: https://storageauctionpirate.github.io/box-dig/

Single file: `index.html`. Tune odds/grid sizes/payouts in the `CONFIG` object at the top.
Core logic is in `window.BoxDig` (`BoxDig.core.newBox`, `BoxDig.mountBox`, `BoxDig.start(config, onFinish)`) so it can be plugged into a bigger game later.
