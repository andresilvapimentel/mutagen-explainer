# mutagen-explainer

<img src="DNA_emoji_1.jpeg" alt="drawing" width="200"/>

Mutagen Explainer is a code to generate structural alerts using Local Interpretable Model-Agnostic Explanations (LIME) of machine learning models from the Bursi and Hansen Ames mutagenicity datasets.

The Mutagen Explainer framework is highly versatile (coded in Google Colab), with options that can be further developed and optimized by the users: it can accept any user-defined datasets (or datasets available in any repository), can use different fingerprints, data splitters, cross-validation methods, and any classification model from DeepChem or sklearn library.

There are two codes to analyze the data generated from BBBP Explainer: BBBP(0)_explainer.ipynb and BBBP(1)_explainer.ipynb
1) mutagenicity_lime_ExtraTrees.ipynb explains the substructures important to the Bursi Ames mutagenicity dataset;
2) mutagenicity_lime_RandomForest.ipynb explains the substructures important to the Bursi Ames mutagenicity dataset;
3) hansen_lime_ExtraTrees.ipynb explains the substructures important to the Hansen Ames mutagenicity dataset;
2) hansen_lime_RandomForest.ipynb explains the substructures important to the Hansen Ames mutagenicity dataset.

The Bursi and Hansen Ames mutagenicity datasets are provided here. DeepChem tools may also be used to upload any dataset in MoleculeNet or user-defined dataset. However, the Bursi and Hansen Ames mutagenicity datasets were curated removing duplicate and triplicate compounds, unifying compounds with two lables, and fixing smiles with RDKit issues. The Bursi and Hansen Ames mutagenicity datasets were cross-validated to get the most robust models.

The mutagen explainer was used with two classifiers: ExtraTrees, and Random Forest. And, these models were analyzed with different metrics (precision, accuracy, recall, and F1 scores) and with the confusion matrix. The models were optimized using hyperparameterization approach to get the best hyper parameters from each model and output the best results.

# Installation instructions

Mutagen Explainer is 100% compatible with Google Colab platform developed in Microsoft Windows using Python version 3.10.

Mutagen Explainer has the following dependencies: Lime, RDkit, DeepChem, Pandas, Matplotlib, sklearn, mols2grid, IPython and XlsxWriter.

# Documentation

The complete documentation about how to run the Mutagen Explainer protocol and several tutorials is being developed.

# Get help

Mutagen Explainer is being actively developed and some issues may arise or you may need extra help to run Mutagen Explainer. In those cases, there are two main ways to get help:

1) Open a new issue in this repository
Or 
2) write an email to André Silva Pimentel (a_pimentel@puc-rio.br) (I will do my best to answer your questions as soon as possible).

# License

Mutagen Explainer is available under MIT License. See license document for more details. URL and DOI: https://github.com/andresilvapimentel/mutagen-explainer (https://doi.org/10.5281/zenodo.10459427)

# Contributors

This code was written under collaboration:
Lucca Caiaffa Santos Rosa (Undergraduate student) and Andre Silva Pimentel (supervisor).
