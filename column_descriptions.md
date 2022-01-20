column\_descriptions
================

## Log\_standards.csv

| Column Position | Column Name | Description of Contents                    |
|-----------------|-------------|--------------------------------------------|
| A               | Compound    | Name of the compound run                   |
| B               | Log\_Conc   | Concentration of the compound in log scale |
| C               | Log\_Peak   | Peak area on the log scale                 |
| D               | Peak        | Raw peak area                              |

## Scent\_Full.csv

*For IUPAC compound names, please see Table S2.*

| Column Position | Column Name | Description of Contents                                                                                              |
|-----------------|-------------|----------------------------------------------------------------------------------------------------------------------|
| A               | Compounds   | Names of all compounds found in the dataset                                                                          |
| B - FO          | sample IDs  | Columns B through FO contain the data from a given sample. For meta data on the sample, see the Scent\_Meta.csv file |

## Scent\_Meta.csv

| Column Position | Column Name     | Description of Contents                                                |
|-----------------|-----------------|------------------------------------------------------------------------|
| A               | Population      | Name of the population. For details on populations, see Table S1       |
| B               | Sample\_ID\_old | Sample ID from Rong’s notebook                                         |
| C               | Sample\_ID      | Sample ID in a uniform format. Matches column names in Scent\_Full.csv |
| D               | Pop\_Plant      | Population and plant for use as random effect in models                |
| E               | Flower\_ID      | The number of the flower measured on the given plant                   |
| F               | Type            | Yes is the first flower on the plant, No is all other plants           |
| G               | Date            | Date the flower was sampled                                            |
| H               | Toluene\_Area   | Raw peak area of toluene, the internal standard                        |
| I               | Toluene\_Amt    | Amount of toluene in nanograms                                         |
| J               | Sample\_Vol     | Volume of the sample in nanoliters                                     |
| K               | No\_Hours       | Number of hours samples were collected for                             |
| L               | No\_Flowers     | Number of flowers included in the sample                               |
| M               | Fresh\_Mass     | Fresh mass of the sampled flower in grams                              |
| N               | Dry\_Mass       | Dry mass of the sampled flower in grams                                |

## Morph\_Full.csv

**For illustration of the morphological traits, see Figure S1**

| Column Position | Column Name          | Description of Contents                                                                                      |
|-----------------|----------------------|--------------------------------------------------------------------------------------------------------------|
| A               | Population           | Name of the population. For details on populations, see Table S1                                             |
| B               | Sample\_ID\_old      | Sample ID from Rong’s notebook                                                                               |
| C               | Sample\_ID           | Sample ID in a uniform format. Matches column names in Scent\_Full.csv                                       |
| D               | Pop\_Plant           | Population and plant for use as random effect in models                                                      |
| E               | Flower\_ID           | The number of the flower measured on the given plant                                                         |
| F               | Type                 | Yes is the first flower on the plant, No is all other plants                                                 |
| G               | Date                 | Date the flower was sampled                                                                                  |
| H               | M.Corolla\_D1        | Dimension measurement 1 of the corolla in mm, used to calculate average corolla width                        |
| I               | M.Corolla\_D2        | Dimension measurement 2 of the corolla in mm, used to calculate average corolla width                        |
| J               | M.Tube\_Flare        | Tube flare in mm                                                                                             |
| K               | M.Stamen\_Length     | Stamen length in mm, used to calculate herkogamy                                                             |
| L               | M.Style\_Length      | Style length in mm, used to calculate herkogamy                                                              |
| M               | M.Hypanthium\_Length | Hypanthium length in mm                                                                                      |
| N               | M.Pedicel\_Length    | Pedicel length in mm                                                                                         |
| O               | M.Leaf\_Number       | Leaf number                                                                                                  |
| P               | M.Leaf\_Length       | Leaf length in mm                                                                                            |
| Q               | M.Nectar\_Column     | Height of nectar in the capillary tube, used to calculate standing nectar volume (see Methods in manuscript) |
| R               | M.Percent\_Sugar     | Percentage sugar in nectar                                                                                   |
| S               | Fresh\_Mass          | Fresh mass of the sampled flower in grams                                                                    |
| T               | Dry\_Mass            | Dry mass of the sampled flower in grams                                                                      |
