# Electroporation

# This code is a Python program, which is used for the theoretical calculation of the degree at which ITV occurred on the cell surface and the percentage of electroporated cell surface area for applied electric field ranging from 400 V/cm up to 1500 V/cm when: 1. cancer cell is alone and when it is among cluster of cancer cells. 2. when the electric field applied along three directions.

For more information about this project, see “ https://www.researchsquare.com/article/rs-3861412/v1 OR https://doi.org/10.21203/rs.3.rs-3861412/v1 ” (Salim Mirshahi & Ameneh Sazgarnia), which is currently under review in the Journal of Molecular Modeling.

Electroporation is a technique that creates electrically generated pores in the cell membrane by modifying transmembrane potential. In this work, the finite element method (FEM) was used to examine the induced transmembrane voltage (ITV) of a spherical-shaped MCF-7 cell, allowing researchers to determine the stationary ITV. A greater ITV than the critical value causes permeabilization of the membrane. Furthermore, the present study shows how a specific surface conductivity can act as a stand-in for the thin layer that constitutes a cell membrane as the barrier between extracellular and intracellular environments. Additionally, the distribution of ITV on the cell membrane and its maximum value were experimentally evaluated for a range of applied electric fields. Using Molecular Dynamics (MD) simulations of palmitoyloleoyl-phosphatidylcholine (POPC), pores in cell membranes exposed to external electric fields were numerically investigated. The dependence on electric field was estimated and developed, and the amount of the electroporated cell surface area matches the applied external electric field. Consequently, the entire cell surface area was electroporated 66% and 68% for MD and FEM, respectively, when the external electric field of 1500 V/cm was applied to the cell suspension using the previously indicated numerical methods. Furthermore, the lipid bilayers' molecular structure was changed, which led to the development of hydrophilic holes with a radius of 1.33 nm. Applying MD and FEM yielded threshold values for transmembrane voltage of 700 and 739 mV, respectively.

Exposing biological cells to an external electric field results in an induced transmembrane voltage (ITV) on the cell membrane, which, under the right conditions may result in reversible permeabilization. This process, called electroporation, has been used to deliver drugs during cancer therapy, DNA transfection or transformation, direct transfer of plasmids between cells and gene therapy. Given the broad importance of these applications, fundamental understanding and optimization of electroporation is critically needed. Towards this goal, this work utilizes machine learning techniques to study the influence of cell-cell interactions on ITV during electropermeabilization. In the first part of the study, the ITV of a cell positioned at the center of a cell cluster is studied. An adaptive neuro-fuzzy inference system (ANFIS) model combined with finite-element simulations is used to develop a tool to predict the electroporated cell surface area (ECSA) without the need for cumbersome measurements or time-intensive simulations. The finite-element simulations were used to compute the electric potential distribution in the media during electroporation of a single cell or cluster of cells. This approach is shown to be able to accurately predict the ECSA during electroporation. Results indicate that the packing ratio (PR) of the cell cluster plays a key role in determining the ITV, particularly when the PR is less than 3. The sensitivity is much reduced for larger values of PR. The ANFIS model showed a 96.6% coefficient of determination (R2= 96.6%) and 1.46 root mean square error representing that the ANFIS model is an accurate and robust approach for prediction of ECSA. Moreover, a higher amplitude of AEF is needed to have higher ECSA when PR decreases. Insights gained from this work may contribute towards investigating other types of cancer with various cell densities with the aim of determining optimal electric field parameters. 

We obtained the maximum value of ITV for a variety of different applied electric field in the experiment and the distribution of ITV on the cell membrane for the case of applying electric field of 1500 V/cm. The maximum value of transmembrane potential for applying electric field of 1500 V/cm is 2730 mV. For this purpose, it was necessary to determine the electric potential differential between each spot on a biological cell membrane's interior and exterior, based on the results achieved in COMSOL software package. The threshold ITV can be determined as the maximum ITV when electric field of 400 V/cm was applied to the cell membrane. The quantity of the threshold ITV is equal to 739 mV. The threshold value of ITV on a spherical cell during electroporation was previously measured by Firoozabadi using a potentiometric fluorescent dye. Based on their results, this value was around 690 mV. The relationship between applied electric field (X) and the maximum ITV was formulated as:
                  
                           ITV=6701sin⁡(0.000281X–0.002243), 400<X

The relationship between applied electric field (X) and the critical angle (θc) was formulated as: 

θ_c = 111.3sin⁡(0.003311X-1.943)+92.95sin⁡(0.006613X-2.106)+48.38sin⁡(0.008088X-5.824), 400<X<1500

Also, the relationship between the applied electric field (X) and electroporated cell surface area (S) was as follows:

S = 93.52sin⁡(0.003003X-1.741)+56.68sin⁡(0.00592X-1.447)+23.28sin(0.007647X-6.261), 400<X<1500

Moreover, the relationship between applied electric field (X) and the critical angle (θc) was based on this formula:

θ_c = 122.3sin⁡(0.003425X-2.05)+106.3sin⁡(0.006472X-1.97)+52.49sin(0.007981X-5.925), 400<X<1500

and the relationship between the applied electric field (X) and electroporated cell surface area (S) was shown here.

S = 97.78sin⁡(0.003004X-1.741)+62.88sin⁡(0.005941X-1.503)+27.32sin⁡(0.007487X-6.376),400<X<1500

The relationship between applied electric field and the critical angle (θc) for different PRs is formulated using curve fitting based on data extracted from Table 3, as follows:

PR= 2, θ_c = 5.3×10^(-6)X^3-0.01134X^2+8.06X-1865 for 500<X<800

PR= 3, θ_c = 5.481×10^(-6)X^3-0.01161X^2+8.217X-1892 for 500<X<800

Where X is the applied electric field.

 The relationship between the applied electric field and electroporated cell surface area (ECSA) for different PRs was formulated as following as well:

PR= 2, ECSA=1.481×10^(-6)X^3-0.003257X^2+2.445X-592    for 500<X<800

PR= 3, ECSA=1.111×10^(-6)X^3-0.002471X^2+1.892X–462.1  for 500<X<800

PR= 4, ECSA=1.111×10^(-6)X^3-0.002471X^2+1.892X–462.1  for 500<X<800

