# NEURO140_FinalProject

This is my final project for the NEURO 140 class, and I decided to train ShallowFBCSPNet using the Braindecode toolkit to decode EEG data from four different datasets. Each file starting with "dataset" corresponds to each dataset I used, and they contain code written to modify their respective dataset into an appropriate format, train the model according to that dataset, and output the results. The file called "comparison.ipynb" contains all the paired t-tests and other statistical measures I used to compare the datasets with each other. In order to do that, I needed to upload the accuracies for each dataset in a separate file, which are the files starting with "acc" (E1/E2 indicates experiment 1/2 and the last part of the file name indicates which dataset it belongs to). 

Below are the citations for each dataset: 

BCI 2000 Dataset:
“EEG Motor Movement/Imagery Dataset v1.0.0,” physionet.org, 2009. https://physionet.org/content/eegmmidb/1.0.0/ (for the actual data)

G. Schalk, D. J. McFarland, T. Hinterberger, N. Birbaumer, and J. R. Wolpaw, “BCI2000: A General-Purpose Brain-Computer Interface (BCI) System,” IEEE Transactions on Biomedical Engineering, vol. 51, no. 6, pp. 1034–1043, Jun. 2004, doi: https://doi.org/10.1109/tbme.2004.827072. (for the official citation) 

Weibo 2014 Dataset:
W. Yi et al., “Evaluation of EEG Oscillatory Patterns and Cognitive Process during Simple and Compound Limb Motor Imagery,” Europe PMC (PubMed Central), vol. 9, no. 12, pp. e114853–e114853, Dec. 2014, doi: https://doi.org/10.1371/journal.pone.0114853.

Nguyen 2017 Dataset:
C. H. Nguyen, G. K. Karavas, and P. Artemiadis, “Inferring imagined speech using EEG signals: a new approach using Riemannian manifold features,” Journal of Neural Engineering, vol. 15, no. 1, p. 016002, Nov. 2017, doi: https://doi.org/10.1088/1741-2552/aa8235.

KARA ONE Dataset: 
“The KARA ONE database,” Toronto.edu, 2015. https://www.cs.toronto.edu/~complingweb/data/karaOne/karaOne.html (accessed May 04, 2025). (for the actual dataset)

S. Zhao and F. Rudzicz, “CLASSIFYING PHONOLOGICAL CATEGORIES IN IMAGINED AND ARTICULATED SPEECH,” 2015. Accessed: May 04, 2025. [Online]. Available: https://www.cs.toronto.edu/~complingweb/data/karaOne/ZhaoRudzicz15.pdf (for the official citation)

The code in the file braindecode.ipynb was written by following the tutorial on their website, very few changes were made:

“Basic Brain Decoding on EEG Data — Braindecode 0.8.1 documentation,” Braindecode.org, 2018. https://braindecode.org/dev/auto_examples/model_building/plot_bcic_iv_2a_moabb_trial.html (accessed May 04, 2025).
