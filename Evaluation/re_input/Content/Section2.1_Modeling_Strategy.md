The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](# 5 References)) Regarding the relevant anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([PK-Sim Ontogeny Database Version 7.3](# References)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([Schlender 2016](# 5 References)) or otherwise referenced for the specific process.

First, a base mean model was built using literature data including selected intravenous single dose studies with Ondansetron to find an appropriate structure to describe the pharmacokinetics in plasma. The mean PBPK model was developed using a typical European individual.



For clearance, first order process was assumed. Specific clearance and lipophilicity were optimized based on the observed plasma concentration vs. time coefficients using the Parameter Identification module provided in PK-Sim®. 

The model was then verified by simulating:

- plasma concentration vs. time profile 

Details about input data (physicochemical, *in vitro* and clinical) can be found in  [Section 2.2](#2.2	Data).

Details about the structural model and its parameters can be found in  [Section 2.3](#2.3 Model Parameters and Assumptions).

Details about model development was
described in Yun and Edginton (2019). 



