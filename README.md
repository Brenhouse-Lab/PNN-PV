# Elevated Zero Maze Data Analysis for PNN/PV Data

## Language: R
## Date: September 2020
## Writers: Alissa Valentine, Kelesa Gildawie

#### These R scripts run a multiple regression loop using PNN/PV data for both the interaction and the main effects with the following notes:
#### - centered all PNN/PV measures around the means to solve any potential problems with multicolinearity.
#### - splitting the analyses by Sex because all of the literature warns me against running regressions with 4 IVs lol.
#### - run the regressions with every behavioral measure (3) with every PNN/PV measure (4 each for PL and IL)
#### - Interaction/3 Way ANOVA Algorithm: [behavioral measure] ~ [centered PNN/PV measure] + Rearing + Housing + [centered PNN/PV measure]:Rearing:Housing (separately for males and females)
#### - Main Effects Housing Algorithm: [behavioral measure] ~ [centered PNN/PV measure] + Rearing + Housing + [centered PNN/PV measure]:Housing (separately for males and females)
#### - Main Effects Rearing Algorithm: [behavioral measure] ~ [centered PNN/PV measure] + Rearing + Housing + [centered PNN/PV measure]:Rearing (separately for males and females)

#### Note:
#### File with data for running this loop is named EZM_PNN_Regressions.sav
