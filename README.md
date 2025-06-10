# PitchingPredictionModel
A frequentist approach to pitch prediction and tendencies

* Uses current savant pitching data to build heatmaps and most likely pitch tables for each pitcher based on hitter handedness and counts.

* "Most Likely Pitch" function can extend infinitely (or technically up to the number of pitch types * 14 zones). Found in 'PitchingPredictionModel/LASTNAME/'

* Each chart contains pitch type, zone, number of times that pitch has been thrown in that zone in that count, and the % that that pitch has been thrown in that zone in that count. This data is stored in the 'PitchingPredictionModel/LASTNAME/aggregate/' folder. 

* TTO charts contains information for pitching tendencies in each count for each handedness. Can be found in '/PitchingPredictionModel/LASTNAME/TTO/L' and '/PitchingPredictionModel/LASTNAME/TTO/R' for left- and right-handed hitters.

* Working on creating charts for extended at-bats (i.e. multiple foul balls)

Goals limited by current data available:

* X,Y positions for pitches so that a contour plot can be created

* A metric which I'm calling "Pitcher effectiveness" which uses various advanced datasets to determine where the pitcher meant to throw the ball and where it ended up.
