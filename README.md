# Paracetamol-dosing-optimisation
Paracetamol Dosing Optimisation
Models how paracetamol concentration in the blood changes after single and repeated doses, using the Bateman equation and superposition of multiple pill doses. I built an objective function that rewards concentrations staying in the therapeutic range, then ran a grid search over dose size and dosing interval to find the combination that keeps the drug in that range for the longest stretch over 4 days. Mainly a way to combine some pharmacokinetics I was reading about with numerical optimisation in Python (numpy, matplotlib).
Not medical advice — just a model.

License MIT — see LICENSE.

<img width="1200" height="600" alt="top_angled_view" src="https://github.com/user-attachments/assets/7bd52916-a504-4f50-bbee-195ca7420bcb" />
<img width="1200" height="600" alt="contour_view" src="https://github.com/user-attachments/assets/dbf0bd61-a62a-4356-b32b-e0faa77ee361" />
