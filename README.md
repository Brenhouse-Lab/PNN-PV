# "EZM_PNN_Regressions_Loop"

## Language: R
## Date: August 2020
## Writters: Alissa Valentine, Kelesa Gildawie

#### This R script runs a multiple regression/interaction loop using PNN/PV data with the following notes:
#### - centered all of my PNN/PV measures around the means to solve any potential problems with multicolinearity.
#### - splitting the analyses by Sex because all of the literature warns me against running regressions with 4 IVs lol.
#### - run the regressions with every behavioral measure (5) with every PNN/PV measure (7 each for PL and IL)
#### - Algorithm: [behavioral measure] ~ [centered PNN/PV measure] + Rearing + Housing + [centered PNN/PV measure]:Rearing + [centered PNN/PV measure]:Housing + [centered PNN/PV measure]:Rearing:Housing separately for males and females
#### - a regression for each behavioral measure (time open, frequency to open, crossings, head pokes, and head poke duration) with each centered PNN/PV measure - the ones ending in "_c" - (PV count, PV intensity, PNN count, PNN intensity, PNN positive PV count, PNN positive PV intensity, PV positive PNN intensity) in the PL and IL ## - 140 regressions (5 behavior measure, 7 PNN/PV measures, 2 regions, 2 sexes)

#### Note:
#### File with data for running this loop is named EZM_PNN_Regressions.sav
