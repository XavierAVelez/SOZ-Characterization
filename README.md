# Seizure Onset Zone Characterization via Graph Neural Networks

### Authors: Tyler Albarran & Xavier Velez

In this work, we propose a method using graph neural networks (GNNs) to infer epileptic network dysfunction via interpretable spatiotemporal brain connectivity.  We evaluate our approach in both supervised and unsupervised settings and find that: (1) incorporating spatial graph structure improves classification performance, (2) inferred connectivity patterns reveal clinically plausible seizure-generating networks, and (3) unsupervised learning enables the use of larger unlabeled datasets, promoting generalization to new patients.

This work uses the open-source dataset found \hyperlink{here}{https://openneuro.org/datasets/ds004080/versions/1.2.4}.

The established pipeline to run this code is as follows:

1. Download the full dataset from OpenNeuro

2. Run the ieeg_processing.ipynb notebook to run the preprocessing pipeline.

3. Run the *ieeg_spectral_classifier.ipynb, ieeg_network_classifier, or ieeg_gcvae_final.ipynb based on which method you would like to test.

*Note that the assets provided include the extracted features for the spectral classifier, and do not need to be recomputed.