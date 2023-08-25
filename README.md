# AI to identify arrhythmogenic sources in the heart from patient ECG

## Introduction:
### Atrial Fibrillation (AF), a heart condition which affects 2% of the UK population, causes adverse health problems such as increased risk of stroke and low blood pressure. AF is caused by abnormal sources of electrical activity in the Left Atria. Current treatment procedure involve burning the area of abnormal electrical activity using catheter ablation or cryoablation. Currently, the procedure has a probabilistic approach, where most likely areas are burnt first and then it is checked if this has had an effect. This approach leads to further problems such as recurrent AF, as the true abnormal source may not be fully treated. If we could identify exactly where the abnormal source was initiating using time-series data from patient ECG and burn directly, this would improve patient outcome by minimising the time of the procedure and lowering the risk of recurrent AF.

## Method:
### In order to determine whether this approach would be feasible, AF was simulated computationally in 2D (100 by 100) grid om Spyder IDE. This was done by solving the FitzHugh-Nagumo equations using Euler's method for the Laplacian and Central Difference methof for the derivative**. Because the 2D grid represents the Atria, the "ECG dataset" simulates only atrial depolarisation (p-wave). Sources of abnormal activity were initiated at different points in the 2D grid and ECGs were generated, based on the measured electrical activity at different heights which imitated electrode lead placements demonstrated in Figure %%. Deep learning algorithms (1D CNNs) were created to classify location of the abnormal activity and the accuracy of these models was checked. The network architecture can be seen in Figure %%, which consisted of ------------.

## Results:

### The simulationas and synthetic ECG collection ran well and initially the ECG datasets for 2 patches of rotors surrounding 30,30 and 70,70 were collected. Once this worked well, more points were chosen and ECGs collected around these points (points visualised in Figure %%. For these points focal initiations were also completed to have a completed dataset of Rotor and Focal points for all 9 initiation points.
### There were 3 main tasks for this project:
###   1) CNN for binary classification for 2 initiation points
###   2) Rotor vs Spiral binary classification
###   3) Rotor classification initiated at various locations
----------


## Conclusion:
### ----

theme: minima
