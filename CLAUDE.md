# CLAUDE.md: moglob-1.2

Tile data repository of the moglob org. Follow londat's CLAUDE.md (data policy, data register, dataflow rule, ASD-STE100
reports to the owner, full URLs): https://github.com/danbri/londat/blob/main/CLAUDE.md . The tools that write here live in
londat (`cwplans/tools/build-cell-tiles.mjs`); register each set in londat's data register. Layout: `data/cells/<z-x-y>/`.
Keep the repository under about 900 MB; a rebuild replaces history rather than stacking copies.
