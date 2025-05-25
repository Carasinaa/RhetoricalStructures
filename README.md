# RhetoricalStructures
This repository contains code for NERs extraction and analysis from American newspapers published in times of Russo-japanese war. All data and results areused in the term paper 'A study of rhetorical structures in the American Press during the Russo-Japanese War'.

# Requirements
In order for the code to run properly you need to install dpendencies from the file [requirements.txt](https://github.com/Carasinaa/RhetoricalStructures/blob/main/requirements.txt) from this repository.

# Data samples
The Data Samples folder contains samples of data needed to run the code.

[sample_1904_1.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1.json) - contains a samplof 50 news published injanuary of 1904

[clean_sample_1904_1.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/clean_sample_1904_1.json) -contains a sample ofcleaned news


[sample_1904_1_ents.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_ents.json) - contains lists of NERs for each sentences from the news sample

[sample_1904_1_sents.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_sents.json) - contains lists of corresponding sentences from the news sample


[sample_1904_1_dependencies.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_dependencies.json) - contains extracted and sorted NERs and corresponding parts of speech


[data_samples/sample_1904_1_gpe.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_gpe.json) - contains sorted lists of GPEs with their dependent parts of speech and their frequency

[sample_1904_1_locations.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_locations.json) - contains sorted lists of LOCs with their dependent parts of speech and their frequency

[data_samples/sample_1904_1_people.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_people.json) - contains sorted lists of PERSs with their dependent parts of speech and their frequency

[sample_1904_1_organisations.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_organisations.json) - contains sorted lists of ORGs with their dependent parts of speech and their frequency

[sample_1904_1_norps.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_norps.json) - contains sorted lists of NORPs with their dependent parts of speech and their frequency

[sample_1904_1_jp_sentiment.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_jp_sentiment.json) - contains data about the number of positive and negative sentences according japan in january of 1904

[sample_1904_1_ru_sentiment.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/data_samples/sample_1904_1_ru_sentiment.json) - contains data about the number of positive and negative sentences according russia in january of 1904

# Visualization Data
The Visualization Data folder contains data, needed to visualize the charts. This folder also contains a subfolder with frequencies for different parts of speech for selected months.

[data_gpe_1904.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_gpe_1904.json), [data_gpe_1905.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_gpe_1905.json) - contain sorted lists of GPEs with their dependent parts of speech and their frequency in years 1904 and 1905 respectively

[data_locations_1904.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_locations_1904.json), [data_locations_1905.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_locations_1905.json) - contain sorted lists of LOCs with their dependent parts of speech and their frequency in years 1904 and 1905 respectively

[data_norps_1904.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_norps_1904.json), [data_norps_1905.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_norps_1905.json) - contain sorted lists of PERSs with their dependent parts of speech and their frequency in years 1904 and 1905 respectively

[data_organisations_1904.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_organisations_1904.json), [data_organisations_1905.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_organisations_1905.json) - contain sorted lists of ORGs with their dependent parts of speech and their frequency in years 1904 and 1905 respectively

[data_people_1904.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_people_1904.json), [data_people_1905.json](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/data_people_1905.json) - contain sorted lists of NORPs with their dependent parts of speech and their frequency in years 1904 and 1905 respectively


[japan_1904.csv](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/japan_1904.csv) - contains a df of frequnecies of positive and negative sentences according japan in year 1904

[russia_1904.csv](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/russia_1904.csv) - contains a df of frequnecies of positive and negative sentences according russia in year 1904

[japan_1905.csv](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/japan_1905.csv) - contains a df of frequnecies of positive and negative sentences according japan in year 1905

[russia_1905.csv](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization/russia_1905.csv) - contains a df of frequnecies of positive and negative sentences according russia in year 1905

# Files for code usage
The repository contains following files:

[parser.ipynb](https://github.com/Carasinaa/RhetoricalStructures/blob/main/parser.ipynb) -- for extracting data from Chronicling America

[rhetorical_analysis.ipynb](https://github.com/Carasinaa/RhetoricalStructures/blob/main/rhetorical_analysis.ipynb) -- for processing and analysing extracted data

[visualization.ipynb](https://github.com/Carasinaa/RhetoricalStructures/blob/main/visualization.ipynb) -- for visualizing processed data
