# Magnetite2026
Data and technoeconomic analysis supporting the results and discussion for Shekhar et al. 2026

A Jupyter notebook is available to view and modify the model assumptions used to estimate a simplified levelized cost of Fe. 

Cost estimates for the stack and balance-of-plant (BOP) were derived from published data on chlor-alkali and metal-electrowinning processes.

Konovalova, A.; Goldman, A. C.; Shekhar, R.; Triplett, I.; Moutarlier, L. J.; Kwak, M.; Kempler, P. A. Pathways to Electrochemical Ironmaking at Scale Via the Direct Reduction of Fe2 O3. ACS Energy Lett. 2025, 10 (4), 1851–1857. https://doi.org/10.1021/acsenergylett.5c00166

Hofmann, M.; Müller, R.; Christidis, A.; Fischer, P.; Klaucke, F.; Vomberg, S.; Tsatsaronis, G. Flexible and Economical Operation of Chlor‐alkali Process with Subsequent Polyvinyl Chlo-ride Production. AIChE J. 2022, 68 (1), e17480. https://doi.org/10.1002/aic.17480.

Klaucke, F.; Müller, R.; Hofmann, M.; Weigert, J.; Fischer, P.; Vomberg, S.; Tsatsaronis, G.; Repke, J.-U. Chlor-Alkali Process with Subsequent Polyvinyl Chloride Production─Cost Analysis and Economic Evaluation of Demand Response. Ind. Eng. Chem. Res. 2023, 62 (19), 7336–7351. https://doi.org/10.1021/acs.iecr.2c04188.

A simplified levelized cost of iron, X_Fe, was calculated based on the levelized cost of capital and operating costs and an annual revenue for co-sale of Cl2 (Equation 4, Supporting Information)
X_Fe = ∑_i (C_i) -R_Cl2

Raw data is sorted by figures available in the manuscript.
an-Fe2O3 refers to a low surface area hematite sample
pc-Fe2O3 refers to a high surface area hematite sample
bf-Fe2O3 refers to a blast-furnace grade iron ore concentrate
np-Fe3O4 refers to a synthetic magnetite sample
prec-Fe3O4 refers to a reprecipitated iron ore concentrate which was high surface area.
