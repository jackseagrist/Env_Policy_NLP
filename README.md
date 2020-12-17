# Environmental Policy NLP - Named Entity Recognition

This respository contains the data and notebook used to train a Google AutoML NER network. The goal of this project was to train a network that could help with the analysis of policy documentation related to climate change and the environment. Documents were obtained from govinfo on the [House Select Committee on the Climate Crisis](https://climatecrisis.house.gov/).

[Link to Data](https://www.govinfo.gov/committee/house-climate?path=/browsecommittee/chamber/house/committee/climate/collection/CHRG/congress/116)

## Outline of Repository
1. 0_Deprecated - Old documents

2. 1_Raw_Climate_Crisis_Text - Hearing transcript txt files from the House Select Committee on the Climate Crisis

3. 2_Processed_Data - Final annotated txt files in jsonl format and accompanying csv files used for the dataset creation in Google Cloud Platform

4. document_data_prep.ipynb - Notebook used to process raw txt files to final jsonl formatted txt files

By: Jack Seagrist
