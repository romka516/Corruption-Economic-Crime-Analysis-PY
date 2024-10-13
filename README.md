# Corruption & Economic Crime-Analysis

The aim of this project is to analyze the distribution of data shared by region from the Corruption & Economic Crime dataset provided by the United Nations. I will explore which crimes are more prevalent than others and, based on these insights, focus on analyzing specific types of crimes in regions or countries that can be further examined and commented on. Below, you can find the project phases that will be analyzed.

## Analysis Steps

1. Initially, data exploration, cleaning, and data wrangling (transforming raw data into an analyzable form) were performed.
2. Then, a box plot will be drawn for the five continents, with subregions on the x-axis and the amount of crime data for each country on the y-axis. This will be interpreted to understand the distribution.
3. Next, a function will be created where the first column represents the year, and the remaining columns represent crime types, with values indicating the amount of data available. The function will include a region attribute, and when we input a continent, subregion, or country, it will display a table sorted by year from past to present, with the crime types that have the most data listed first.
4. Crimes related to theft in Türkiye from 2003 to 2014 will be analyzed, and bar charts will be drawn based on crime rates per 100,000 people, as well as total crimes, and these will be interpreted. Following this, bar charts comparing Türkiye's crime rates per 100,000 people with those of Europe and the world will be created and analyzed.
5. Human trafficking crimes worldwide from 2016 to 2020 will be analyzed, and a line graph will be created and interpreted. Afterward, Türkiye and the United States will be analyzed and compared similarly.
6. Finally, technology-related crimes in Northern and Western Europe will be analyzed and interpreted using line and bar charts.

## Development Tools

Python data analysis libraries such as NumPy, Pandas, and Seaborn have been used in this project.

## Acknowledgments

I would like to extend my special thanks to [Assoc. Prof. Erhan ÇENE](https://avesis.yildiz.edu.tr/ecene) for encouraging us to find and analyze data in his class.

## Reference

UNODC (2023), UNODC Research - Data Portal – Corruption and Economic Crime. https://dataunodc.un.org/dp-crime-corruption-offences (Accessed on [05-2024])

## License

This project is licensed under the [MIT License](LICENSE).