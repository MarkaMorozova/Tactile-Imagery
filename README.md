# Tactile Imagery
This repository contains notebooks and data to generate final figures from the article XXX. We aimed to study the changes in the sensory processing of tactile (vibrational) stimuli during Tactile Imagery.

## Repository Structure
- [8-sec tactile stimulation&imagery.ipynb](https://github.com/MarkaMorozova/Tactile-Imagery/blob/main/1.%208-sec%20tactile%20stimulation%26imagery.ipynb): notebook to analyze Event-Related Desynchronizations (ERD) in response to 8-second Tactile Stimulation (TS) and Tactile Imagery (TI) epochs (learning of TI)
- [somatosensory ERP rest&imagery.ipynb](https://github.com/MarkaMorozova/Tactile-Imagery/blob/main/2.%20somatosensory%20ERP%20rest%26imagery.ipynb): notebook to analyze Event-Related Potentials (ERP) in response to 75 ms vibrational stimuli during Rest and TI
- [ERD to short tactile stimuli rest&imagery.ipynb](https://github.com/MarkaMorozova/Tactile-Imagery/blob/main/3.%20ERD%20to%20short%20tactile%20stimuli%20rest%26imagery.ipynb): notebook to analyze Event-Related Desynchronizations and Synchronizations (ERD and ERS) in response to 75 ms vibrational stimuli during Rest and TI
- [figs folder](https://github.com/MarkaMorozova/Tactile-Imagery/tree/main/figs): contains main figures from the notebooks

## How to use repository
- download zip-archive with the preprocessed data [here](https://drive.google.com/file/d/1NXV7dYO2dlHMTA_AOzInS16sbDLL1QZz/view?usp=sharing) 
- unzip archive, place the folder `preprocessed_data` in the same folder as notebooks
- run the notebooks

## Main findings
- mu-rhythm ERD during TS correlates with mu-rhythm ERD during TI

<img src="figs/correlation_ts_ti.jpg" alt="Metrics bgbGAT vs MLP" width="500">

- ERP to 75 ms vibrational stimuli consist of 3 main components P100, P200, P300
![Alt Text](https://github.com/MarkaMorozova/Tactile-Imagery/blob/main/figs/erps.jpg)
- TI modulates ERP to 75 ms vibrational stimuli, particularly, P100, P200 in ipsilateral hemisphere and P300 in contra- and ipsilateral hemispheres
![Alt Text](https://github.com/MarkaMorozova/Tactile-Imagery/blob/main/figs/rest_vs_imagery_erp.gif)
- Event-Related Time-Frequency changes to 75 ms vibrational stimuli consist of ERS in theta-frequency range and ERD in mu- and beta-frequency ranges, and ERS in theta-frequency range statistically significantly increases during TI
![Alt Text](https://github.com/MarkaMorozova/Tactile-Imagery/blob/main/figs/topomaps_powers_pulses.jpg)
