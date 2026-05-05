# Preterm-Birth-Prediction-Using-EHG

# Abstract

Preterm birth (PTB) affects around 15 million
infants every year and causes major health issues, making it
a worldwide health concern [4]. The demand for precise early
prediction methods has motivated researchers to explore the
use of Electrohysterogram (EHG) signals. EHG is a promising
approach for predicting preterm labor as it is a non-invasive
and affordable method for monitoring uterine activity. This study
aims to build a strong PTB prediction model with explainable
AI using the publicly accessible TPEHG dataset (300 recordings, 38 preterm). The validation of the model is performed
with the TPEHGT dataset (13 preterm and 13 term samples).
We employed a graph neural network (GNN) that efficiently
aggregates local neighborhood information in graphs and is
based on the GraphSAGE architecture. The GraphSAGE model
achieved 99.2% accuracy by training with stratified 10-fold
cross-validation. This was validated through confusion matrices,
ROC, and precision-recall curves. In order to guarantee model
transparency, the most important factors influencing predictions
were found using Shapley Additive explanations (SHAP) analysis,
which offered insightful information about the decision-making
process. This study emphasizes the value of explainable AI in
enhancing clinical decision-making, as well as the possibility of
GNNs for PTB prediction.
