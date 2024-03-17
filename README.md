# 2024_scouting_data

WildRank scouting data collected during our 2024 Crescendo competitions.

## What is WildRank?

[WildRank](https://github.com/wildstang/wildrank) is our scouting app. 

### Application Versions

This repo contains data collected with WildRank 3 during the official competition season. The versions or Git hashes of the app used to collect the data can be found below. Any data collected with version 3 should be compatible with any version 3 release of the app, but forward/backward compatibility is not guaranteed.

| Event                         | Version |
| ----------------------------- | ------- |
| Central Illinois Regional     | 3.0.1   |
| Midwest Regional              | 3.TBD   |

## How do I read this data?

The best way is with WildRank where you can upload a zip archive of the results using the "Transfer Raw Data" page. Otherwise, the data is all in JSON, easily parsable with most programming languages. The results are all stored by match-team as key-value pairs. Cycles are stored as a list of recurring pairs.

## Data Integrity

This is raw data from our scouters. The quantitative data has not been modified, but qualitative data has been removed. This means there are known (and unknown) errors in the data. We chose not to correct our data after the events, first because it would be too time consuming and second to offer us uncleaned data for future testing/learning purposes. If in the future this data is cleaned the cleaned data will be posted alongside the raw data here.

## Thanks

As always, thank you to all the scouters who spent countless hours in the stands contributing to this data.
