# Microsoft_Over-The-Moon

Lunar Mission Data Analysis
This Python script analyzes data related to lunar missions, focusing on rock samples collected during the Apollo missions. It uses the Pandas library to manipulate and analyze the data from the 'rocksamples.csv' file. The analysis includes:

Data Preprocessing:

Conversion of rock sample weights from grams to kilograms.
Renaming and reorganizing columns for clarity.
Mission-level Analysis:

Aggregating total sample weight for each mission.
Calculating the difference in sample weight between consecutive missions.
Lunar Module (LM) and Command Module (CM) Analysis:

Incorporating information about the lunar module's mass and its change over missions.
Including details about the command module's mass and its change over missions.
Total Weight and Difference Calculation:

Computing the total weight of the lunar module and command module for each mission.
Calculating the difference in mass for both modules.
Introduction of New Missions:

Adding information about hypothetical Artemis missions with estimated total weight and payload.
Sample-to-Weight Ratios:

Calculating various ratios related to the weight of rock samples concerning the mission's payload and crewed area.
Remaining Rock Samples:

Determining the remaining weight of rock samples based on their pristine percentages.
Summary Statistics:

Displaying summary statistics for the rock samples.
Identification of Low-Quality Samples:

Identifying rock samples with a weight above 0.16 kg and pristine percentage below 50%.
Print Total Sample Weight:

Printing the total weight of all rock samples.
Usage
Ensure you have Python and the required libraries installed.

Run the script:

bash
Copy code
python Microsoft_Over-The-Moon
.py
Results
The script provides insights into the rock samples collected during lunar missions, their weights, and mission-level details.
