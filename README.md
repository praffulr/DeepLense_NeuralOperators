# DeepLense_NeuralOperators
DEEPLENSE GSoC 2026 - Neural Operators test

Test doc link - https://docs.google.com/document/d/10APh49fvayGoSftzO4fGXs2HP3uvYSzG-fSrq4xHL1w/edit?tab=t.0#heading=h.9vj3xjy2bpky

Common Test I. Multi-Class Classification

Task: Build a model for classifying the images into lenses using PyTorch or Keras. Pick the most appropriate approach and discuss your strategy.

Dataset: dataset.zip - 

Dataset Description: The Dataset consists of three classes, strong lensing images with no substructure, subhalo substructure, and vortex substructure. The images have been normalized using min-max normalization, but you are free to use any normalization or data augmentation methods to improve your results.
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve) 

Specific Test IV. Neural Operators

Task: Build a model for classifying the images into lenses using a neural operator architecture such as a Fourier Neural Operator (FNO) or DeepONet as the backbone, implemented in PyTorch or Keras. Your model should replace or augment the standard convolutional feature extractor with a neural operator layer that operates in function space (e.g., spectral convolutions via FFT for FNO). Compare the performance of your neural operator-based classifier against your Common Test I result. Pick the most appropriate approach and discuss your strategy, including your choice of operator architecture and how it differs from standard CNNs for this task.

