# Star Trek Dialogue Analysis Proposal
## Data Sources:
https://www.kaggle.com/datasets/birkoruzicka/startrekdialoguetranscripts/data
https://github.com/BirkoRuzicka/Star-Trek-Dialogue-Analysis/tree/main/additional_data

## Context & Goals:
Analyzing the dialogue of all Star Trek series as a data analysis project provides a unique opportunity to explore the evolution of societal and technological themes over decades. By examining the language used by each character, how often language is used and by whom, etc., I would like to potentially answer the following:

### Character importance:
longer lines = more important characters? Who has the longest lines the most often?
which characters are in the most episodes?
which characters are referenced in series that they are not actually in?
what kind of starfleet officers (captain, first officer, engineer, etc) have the most and least dialogue
how consistent is each character's dialogue length across episodes or series?
how do certain characters' dialogue lengths change over the course of a series or between series?

### Character connection:
**create a network analysis
How often a character's name is used by other characters
How oft

### Gender:
how much more or less do female characters speak/are spoken to?
how did the amount of female dialogue change over time?
how many times were female vs male characters the most important character?

### Text analysis:
recurring themes or topics in the dialogue of each character *TOPIC MODELING
each character's top "catch phrase" (keyword frequency?)
analyze text for character sentiment
do some characters use a broader range of words?

### Technology:
what star trek specific technology (ex: transporters, tricorders, replicators) are mentioned most frequently?

### Additional:
how much does total dialogue vary by series/by episode?
how often do "REDSHIRT"s get to talk?


## Key Data Concepts:
### Series and Episodes: 
The data is organized by different Star Trek series (e.g., TOS, TAS, TNG) and further divided into episodes. Each episode contains information about characters and their dialogues.
Characters: Dialogues are associated with specific characters from the Star Trek universe. The main cast for each series is defined, and dialogues spoken by characters outside the main cast are filtered out.
### Dialogues: 
Dialogues are the spoken lines of characters in the Star Trek series. The length of each dialogue is calculated and stored.¶
### Additional Data: 
Additional data sources (e.g., 'tos_data.csv', 'tos_gender.csv') are used to enrich the dataset. This additional data includes information like season, year, title, and gender, and is merged into the main dataset.
