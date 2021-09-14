## Problem desscription

The file “dataminesrocks.csv” contains 208 patterns obtained by 1)bouncing sonar signals off a metal cylinder at various angles and under various conditions, and 2) from bouncing sonar signals off rocks under similar conditions. The transmitted sonar signal is a frequency-modulated chirp, rising in frequency. The data set contains signals obtained from a variety of different aspect angles, spanning 90 degrees for the cylinder and 180 degrees for the rock.

Each pattern is a set of 60 features in the range 0.0 to 1.0. Each feature representing the energy within a particular frequency band, integrated over a certain period of time. 

The label associated with each record contains "Rock" or "Mine".

Three trained human subjects were each tested on 100 signals, chosen at random from the set of 208 returns used to create this data set. Their responses ranged between **88% and 97%** correct. However, they may have been using information from the raw sonar signal that is not preserved in the processed data sets presented here.

Can we design a model that improves the above performance?

References: 

[](https://datahub.io/machine-learning/sonar#readme)
[](https://www.openml.org/d/40)

# Classifiers used on the data:
1. Supprt Vector Machine (SVM) with linear kernel
2. SVM with radial kernel
3. Logistic regression
