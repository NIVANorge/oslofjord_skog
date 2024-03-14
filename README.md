# Osloskog: Modelling the effects of forest harvesting on nutrient fluxes to the Oslofjord

Project for Landbruksdirektoratet in collaboration with NIBIO.

## Workflow

 * **[Merge SR16beta](https://nbviewer.org/github/NIVANorge/oslofjord_skog/blob/main/merge_sr16beta.ipynb)**. Combining the raster tiles for NIBIO's SR16beta dataset into a single vector layer.

 * **[1000 Lakes logging](https://nbviewer.org/github/NIVANorge/oslofjord_skog/blob/main/1000_lakes_logging.ipynb)**. Screening for human activities (including harvesting) within the "1000 Lakes" catchments.

 * **[Harvesting coefficients](https://nbviewer.org/github/NIVANorge/oslofjord_skog/blob/main/coeff_curves.ipynb)**. Exploring options to represent the effects of harvesting on background runoff concentrations.

 * **[Modelling the effects of harvesting](https://nbviewer.org/github/NIVANorge/oslofjord_skog/blob/main/harvesting_effects.ipynb)**. Using TEOTIL3 to model additional nutrient fluxes due to harvesting.
