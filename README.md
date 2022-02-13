# What are the main sources of dietary fat by country?

This code was used to generate a plot which is found in the Supplementary Material of the publication:

    Bojana Bajželj, Federica Laguzzi, Elin Röös,
    The role of fats in the transition to sustainable diets,
    The Lancet Planetary Health,
    Volume 5, Issue 9,
    2021,
    Pages e644-e653,
    ISSN 2542-5196,
    https://doi.org/10.1016/S2542-5196(21)00194-7.
    (https://www.sciencedirect.com/science/article/pii/S2542519621001947)

    In comparison with protein, dietary fat receives little attention in the food system sustainability literature, although we calculate that the average consumption of fats in many populous regions of the world is below nutritional recommendations. Animal products are the major source of dietary fat, particularly in regions with excess fat consumption. We estimate that an additional 45 Mt of dietary fat per year need to be produced and consumed for the global population to reach recommended levels of fat consumption, and we review different strategies to fill this gap sustainably. These strategies include diverting oils currently used for energy production to human consumption, increasing palm oil and peanut oil yields while avoiding further deforestation, developing sustainable cropping systems for the production of rapeseed and soybean oils, increasing the consumption of whole soybeans and derived products, and expanding the use of animal fats already produced.

## Data sources

Data used is from FAO:

==> data/FAOSTAT_ct_fat_items.csv <==

    Domain Code,Domain,Country Code,Country,Element Code,Element,Item Code,Item,Year Code,Year,Unit,Value,Flag,Flag Description

==> data/FAOSTAT_data_10-25-2019.csv <==

    "Country Code","Country","M49 Code","ISO2 Code","ISO3 Code","Start Year","End Year"

You also need the following:

- Download country outlines from https://datahub.io/core/geo-countries#resource-geo-countries_zip

- Download country codes from http://www.fao.org/faostat/en/#definitions

## Dependencies

Written using Python 3.7 and the following:

- jupyter notebook
- pandas
- geopandas
- matplotlib