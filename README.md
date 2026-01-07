# NovaPrime_E103A
AI-Driven Transparency for Opaque Platform Pay Formulas
<br>
Authors: Prajit B, Ragulkanna VU, Nimalan S
<br>
<br>
Abstract
<br>

Gig economy platforms like Uber, Instamart generally relies on properietary algorithms like rule based pay algorithms, multiplier algorithms and etc, that are primarily based on simple decision making rules. The problem with these traditional algorithms lies not on their effectiveness, but in their rigidity when applied in a scale and also on the lack of interpretability. Although such models were initially designed to ensure operational efficiency and demand supply balance, they provide little to no transparency into how individual decisions are made, leaving workers unable to understand the factors influencing their earnings or task allocation. 
<br>

The proposed project aims at developing a worker-focused transparency system that uses AI for analyzing task level as well as payment levels to identify the underlying logic used in assignment and payment algorithms on a platform-based pay system. The system applies gradient boost decision tree models to identify non-linear as well as rule-based payment structures, which then enable it to identify the underlying compensation algorithms using a high level of accuracy. Accountability as well as interpretability are achieved using SHAP, SHapley Additive exPlanations, as the main explanatory model for AI.
<br>

The system also integrates temporal change detection based on comparisons of model explanations over time intervals for the purpose of detecting unseen changes in the algorithm. The fairness analysis layer of the system investigates the distribution of contributions indicated by SHAP values for different groups of workers for the purpose of detecting discriminatory treatment of the different groups when they are treated similarly. All results are presented in a multilingual visual report.
<br>

In this manner, the algorithmic decision-making process that was once opaque for the gig workers can be made clear, data-driven insights with the use of the system, which in turn empowers the gig workers.
