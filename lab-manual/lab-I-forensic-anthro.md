# Introduction to Lab Methods – Forensic Anthropology

### Additional Equipment

- Logger Pro Manual
- Meter sticks

### Objectives

Become familiar with the following equipment and methods:

- ABC Lab structure

- Logger Pro, the computer software we will be using throughout the semester
- Measurements and error calculations expected 

### Topics:

- ABC Lab structure
  - Expectations
  - Deadlines
  - C level, B level, A level
  - Grading/Grades

- Intro to Logger Pro
  - Logger Pro Manual
  - Manual Columns
  - Calculated Columns
  - Curve Fits
  - Region of Interest (ROI)
  - Statistics
  - Adding error bars to graphs
  - CNTRL R

- Measurements
  - Precision
  - Uncertainty/Error and "significantly different" values
  - Measuring increments smaller than your instrument can
  - Plots and "good" experiments

### Conceptual (C-level) DONE BEFORE LAB: Uncertainty/Error and "Significantly Different"

The best value and uncertainty are often written together in the following way: Best value ± uncertainty

Report your results this way.

When reporting best values and uncertainties, we will agree to use a slightly arbitrary but sensible rules:

Rule1: Write no more than 2 significant figures in the uncertainty, and round the best value to the smallest affected digit. 

Example: 30.6480.375 m

Solution: 

1. a)Start with the uncertainty and round it to 2 significant figures: 0.375 becomes 0.38.
2. b)Determine the place of the smallest digit in the uncertainty: the one hundredths place.
3. c)Round the best value to the smallest decimal place of the uncertainty: 30.650.38 m

When determining whether or not two uncertain data values are in agreement, we will use the rule below:

Rule 2: Two experimental values are said to be "significantly different" if the values are more than three error bars apart.

Example: Are 1.250.05 s and 3.21.9 significantly different?

Solution:

1. a)The best values are |3.2-1.25|=1.97 s apart.
2. b)The larger uncertainty is 1.9 s. 
3. c)The best values are therefore approximately one error bar apart. Applying the rule above, since the values are less than three error bars apart we would say the values are not significantly different, or that they "agree within experimental uncertainty"!
  - Are the values 7.210.01 m and 7.290.01 m significantly different? Why? Sketch the error bars.
  - Do the values 0.250.12 m and 0.450.02 m agree within uncertainty? Why? Sketch the error bars.

**Uncertainty in sensor measurements – DONE IN LAB**

Set up the force probe and Logger Pro. See the Logger Pro Manual for details. With a calibrated force probe, take several seconds of data and use the **statistic features** of LoggerPro to determine the uncertainty in the force measurements. Report your uncertainty.

# Basic Lab (B-level): Putting it all together: Forensic Anthropology – Bone length

Measure your femur (in cm) on yourself and record on your chart and on the board. You will record the class data as well. The equations below each bone are those used by forensic anthropologists to estimate height from a single bone. Record your actual height as well as your estimated height.

Create a plot in LoggerPro (NOT Excel!) of your measured femur lengths vs measured heights. To do this you will need to:

- Create four "Manual Columns" in LoggerPro, one for each of the Femur length, person's height, and the uncertainty for each of those measurements.
- Insert a plot, and choose what columns are on each axis (by clicking on the label on each axis).
- Create a "Calculated Column", which gives the "predicted" using the measured lengths of the bones. Do your predicted heights agree with your measured heights?.
- Perform a "curve fit" to your data. Look carefully at all of the types of curves you can use. What type makes the most sense in this situation?
- Do the values in your fit agree with the model in the table on the following page?
- Why do male and female measurements need to be analyzed separately?
- Why should a forensic anthropologist use more than one bone (if possible) to determine the height of an individual?
- 

| Ind. | Femur Manual Column | Femur Error Manual Column | Actual Height Manual Column | Actual Height Error Manual Column | Est. Height Calculated Column |
| --- | --- | --- | --- | --- | --- |
| Females |  |  |  |  |  |
|  |  |  |  |  | H = (L X 1.94) + 72.9 |
| 1 |  |  |  |  |  |
| 2 |  |  |  |  |  |
| 3 |  |  |  |  |  |
| 4 |  |  |  |  |  |
| 5 |  |  |  |  |  |
| 6 |  |  |  |  |  |
| 7 |  |  |  |  |  |
| 8 |  |  |  |  |  |
| 9 |  |  |  |  |  |
| 10 |  |  |  |  |  |
| 11 |  |  |  |  |  |
| 12 |  |  |  |  |  |
| 13 |  |  |  |  |  |
| 14 |  |  |  |  |  |
| 15 |  |  |  |  |  |
| 16 |  |  |  |  |  |
| Males |  |  |  |  |  |
|  |  |  |  |  | H = (L X 1.88) + 81.3 |
| 17 |  |  |  |  |  |
| 18 |  |  |  |  |  |
| 19 |  |  |  |  |  |
| 20 |  |  |  |  |  |
| 21 |  |  |  |  |  |
| 22 |  |  |  |  |  |
| 23 |  |  |  |  |  |
| 24 |  |  |  |  |  |
| 25 |  |  |  |  |  |
| 26 |  |  |  |  |  |
| 27 |  |  |  |  |  |
| 28 |  |  |  |  |  |
| 29 |  |  |  |  |  |
| 30 |  |  |  |  |  |
| 31 |  |  |  |  |  |
| 32 |  |  |  |  |  |

