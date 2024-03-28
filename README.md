# Fuel Prices Pre Election: Impact of the 2023 Elections in Poland

This repository contains an analysis of fuel prices in European countries, including Poland. The analysis explores the impact of the 2023 elections in Poland on fuel prices and highlights instances of suppressed prices within the country.

## Data Source

The data was sourced from the European Commission's Energy Observatory Reports. Specifically, the dataset utilized is the Oil Bulletin Prices History, which provides prices with taxes per CTR for various European countries.
[Data source](https://ec.europa.eu/energy/observatory/reports/) 

https://ec.europa.eu/energy/observatory/reports/ ->  Oil_Bulletin_Prices_History.xlsx -> Prices with taxes, per CTR

### Country mapping:

```
country_mapping = {
    'AT': 'Austria',
    'BE': 'Belgium',
    'BG': 'Bulgaria',
    'CY': 'Cyprus',
    'CZ': 'Czechia',
    'DE': 'Germany',
    'DK': 'Denmark',
    'EE': 'Estonia',
    'ES': 'Spain',
    'FI': 'Finland',
    'FR': 'France',
    'GR': 'Greece',
    'HR': 'Croatia',
    'HU': 'Hungary',
    'IE': 'Ireland',
    'IT': 'Italy',
    'LT': 'Lithuania',
    'LU': 'Luxembourg',
    'LV': 'Latvia',
    'MT': 'Malta',
    'NL': 'Netherlands',
    'PL': 'Poland',
    'PT': 'Portugal',
    'RO': 'Romania',
    'SE': 'Sweden',
    'SI': 'Slovenia',
    'SK': 'Slovakia'
}
```

### Mapping columns names:
```
new_column_names = {
    'Unnamed: 1': 'Date',
    'Unnamed: 2': 'Rate to Euro',
    'Unnamed: 3': 'Euro-super 95',
    'Unnamed: 4': "Gas oil automobile",
    'Unnamed: 5': 'Automotive gas oil',
    'Unnamed: 6': 'Automotive gas oil',
    'Unnamed: 7': 'Automotive gas oil',
    'Unnamed: 8': 'LPG'
```
Contributions and suggestions for improvement are always welcome!
