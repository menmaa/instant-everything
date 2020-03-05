# instant-everything
Removes the annoying animation and skips the progress bar for enchanting, upgrading, repairing, soulbinding, dismantling, and merging items.

Each mode can be toggled by using the in-game command `instant [mode]`, with `[mode]` being `enchant`, `upgrade`, `repair`, `soulbind`, `merge`, or `dismantle`.

### Installation Instructions

1. Download and extract into the `mods` folder of your TERA Toolbox.
2. Copy files from `defs` folder into `[toolbox folder]\node_modules\tera-data\protocol`
3. (TERA EU ONLY) Add the following lines to the `[toolbox folder]\node_modules\tera-data\map\protocol.365098.map`:

```
C_REGISTER_REPAIR_ITEM 54157
C_REQUEST_REPAIR_ITEM 62308
C_START_REPAIR_ITEM 30374
```
