# Investigating-Optimal-Visual-Inputs-newline-for-Cortical-Neurons

---
This group research is committed to employing deep learning techniques to identify and generate the Most Excitatory Input (MEI) for a single neuron in the visual system of a mouse, specifically through the use of end-to-end trained Convolutional neural networks (CNNs).
Most Excitatory Inputs (MEIs) represent the specific visual stimuli that are designed to maximally activate the neurons. These in silico stimuli are pivotal for delineating the functional characteristics of a neuronal single-cell, highlighting the features within a neuron's receptive field to which it is most responsive.
By adopting this methodology, we aim to construct a stimulus that, by successfully combining the stimuli's features, is most likely to trigger the highest firing rates in neurons. Finally, we seek to investigate some properties of these artificially optimized stimuli and try to test the robustness of our findings using Gabor filters as benchmarks.
My part for the project was developing the code, which creates the MEIs given a CNN, which predicts the neural response of an image.

This work has been inspired by [1] and it was applied on AllenSDK dataset[2].

---
# Bibliography
[1] W. et al, “Inception loops discover what excites neurons most using deep predictive models”, Nature Neuroscience, 2019.
[2] https://allensdk.readthedocs.io/en/latest/index.html
