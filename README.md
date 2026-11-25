# moglob-1.2

Tile data for moglob, the 3D map at https://danbri.github.io/londat/docklands/ . This repository holds building cells
(3D Tiles 1.1, glTF) of the worldwide building layer, served by GitHub Pages at https://moglob.github.io/moglob-1.2/ .

- Plan and sizes: https://github.com/danbri/londat/issues/20 and https://github.com/danbri/londat/blob/main/docs/scale-estimate.md
- Builder: https://github.com/danbri/londat/blob/main/cwplans/tools/build-cell-tiles.mjs (layout `data/cells/<z-x-y>/`)
- Data register (sources, licences, credits): https://github.com/danbri/londat/blob/main/cwplans/DATA-REGISTER.md
- Size limit: about 900 MB in this repository (the Pages site stops at 1 GB).

Building data: © OpenStreetMap contributors, Overture Maps Foundation, Microsoft (ODbL 1.0); heights from GHS-BUILT-H
R2023A © European Union, JRC (CC BY 4.0). The full credit of each cell is in its tileset.json and features.json.
