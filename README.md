# Machine Learning for Predictive Maintenance - A Regression Model of Damage Deterioration for Spur Gears

This model uses sliding windows and proxy labels with heath indicator to achieve a pseudo remaining useful life (RUL) prediction.

## Dataset
The dataset is a sample subset of the [PHM North America 2026 Conference Data Challenge](https://data.phmsociety.org/phm-north-america-2026-conference-data-challenge/). The dataset can be dwnloaded [here](https://gtc-data.synology.me:51111/sharing/uIrAvzqEh). 

This dataset is a collection of sensor measurements from seven accelerated life experiments on spur gears. Each experiment captures the data of a spur gear with 28 teeth that is operated until failure.  All tests are conducted on a simple one‑to‑one ratio gearbox, with failure defined as the point at which the gear becomes unusable, resulting in lifetimes ranging from approximately 30 to 90 hours. Each experiment includes multiple runs, typically around six hours long, during which vibration data are collected using axial and radial accelerometers, the latter being more sensitive and used to derive classical condition indicators. In addition to high‑frequency vibration signals, the dataset contains lower‑rate context variables, computed condition indicators, and signal transforms, all stored in HDF5 format. 

 Additionally,  tooth surface images captured after each run provide ground truth for damage progression. However, these will not be used in the scope of this project. Instead, proxy labels are generated which indicate the health of the gears. These labels are created based on the first run and the last run of each gear. 


## Experiment Setup
### Preprocessing
### Sliding Windows
### Proxy Labels


## Results

## Evaluation

