# review_meta

##Data Collection

Data collection was done by scrubbing information from Metacritic and gamerankings. The collected data includes the publisher, critic review score, critic review count, public review score, public review count, year of publication. There are no new plans to add more sources such as opencritic.

##Data Wrangling

Dataset was processed to water down the overall information to few key variables. Publisher was transformed to AAA (1 being a AAA publisher, 0 to not), multiple entries of the same game were merged together. For the review scores, due to the inevitability of overcounting, the entry with the largest review count in either category (critic or public) was selected. The file analysis.csv represents the processed version of the dataset.

