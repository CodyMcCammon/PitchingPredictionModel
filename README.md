# PitchingPredictionModel
A frequentist approach to pitch prediction and tendencies

Uses current savant pitching data to build heatmaps and most likely pitch tables for each pitcher based on hitter handedness and counts. Only requires dates specified and pitcher name to generate data.

"Most Likely Pitch" function can extend infinitely (or technically up to the number of pitch types * 14 zones).

Each chart contains pitch type, zone, number of times that pitch has been thrown in that zone in that count, and the % that that pitch has been thrown in that zone in that count.

~~Includes TTO data for 1st through 4th time through the order.~~ Issue with way TTO is calculated, or more specifically, the way it interprets Statcast at_bat_number. I believe it will be an easy fix and will fix it soon.
