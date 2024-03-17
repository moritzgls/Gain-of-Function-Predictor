# Gain-of-Function-Predictor

Problem: 
Identifying substitution mutations that cause increase enzyme activity is important for precision oncology, since physicians have to know exactly what a mutation does to an enzyme in order to administer targeted inhibitors. But none of the current Variant Effect Predictor offer such a prediction.

Solution:
Learning from Pair Representations derived from AlphaFold structures and being trained on Mass Assays of Variant Effect (MAVEs) the model learns to output a score from -1 to 1, where 0 means is unaltered, wildtype-like activity and 1 is increased activity.

Please note that the model is still under development and the current training runs only focus on finding the best architecture for the problem
