# A123_26650_m1b

This repository contains lab experimental data used for equivalent-circuit model parameterization for the following commercial A123 26650 2.5Ah battery:


<!-- ![alt text](https://github.com/aloisiohks/A123_26650_m1b/blob/main/a12326650.png?v=4&s=20) -->

<p align="center">
 <a href="https://github.com/aloisiohks/A123_26650_m1b/blob/main/a12326650.png"><img src="https://github.com/aloisiohks/A123_26650_m1b/blob/main/a12326650.png" width="200" height="100"/></a>
</p>

The files associated with this dataset are licensed under a Creative Commons Attribution 4.0 International license, which means that it can be shared, copied and modified as long as the appropriate credit is given. If you use this dataset in your publication, please cite this dataset as:

<a href="https://data.mendeley.com/datasets/p8kf893yv3/1">Kawakita de Souza, Aloisio (2021), “Lithium-ion Battery OCV and Dynamic Test Data of a LiFePO4 cylindrical cell”, Mendeley Data, V1, doi: 10.17632/p8kf893yv3.1!</a>

This dataset was collected at the High-Voltage Battery Research Lab at University of Colorado Colorado Springs using an Arbin BT2000 battery cycler and a Cincinnati Sub-zero thermal chamber. This dataset has been used for the model parameterization of a coupled electro-thermal equivalent-circuit model (CET model) in the following publications:

A. K. de Souza, G. Plett and M. S. Trimboli, "Lithium-Ion Battery Charging Control Using a Coupled Electro-Thermal Model and Model Predictive Control," 2020 IEEE Applied Power Electronics Conference and Exposition (APEC), 2020, pp. 3534-3539, doi: 10.1109/APEC39645.2020.9124431.

Kawakita de Souza, A. (2020). Advanced Predictive Control Strategies for Lithium-Ion Battery Management Using a Coupled Electro-Thermal Model [Master thesis, University of Colorado, Colorado Springs]. ProQuest Dissertations Publishing.

M. A. Xavier, A. K. de Souza and M. S. Trimboli, "An LPV-MPC Inspired Battery SOP Estimation Algorithm Using a Coupled Electro-Thermal Model," 2021 American Control Conference (ACC), 2021, pp. 4421-4426, doi: 10.23919/ACC50511.2021.9483433.

- The OCVdata and DYNdata folders contain the lab data that can be used with the ECM toolbox from Prof. Plett's book (Battery Management Systems, Volume I: Battery Modeling) to estimate the parameters of the Enhanced self-correcting model for the temperature range from -25 ℃ to 45 ℃ in increments of 10 ℃.
- The CCCV folder contains the CCCV data at 25 ℃ at four different charging C-rates (1C, 2C, 3C and 4C).
- The Miscellaneous folder contains:
      i) Experimental data for cell discharging using UDDS drive cycles at 25 ℃ and 35 ℃ used in the publications mentioned above. 
      ii) Periodic pulse data for thermal dynamics characterization used in the master thesis mentioned above. 

