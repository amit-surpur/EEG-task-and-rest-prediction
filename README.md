# EEG-task-and-rest-prediction
#Task1: PSD Analysis
  The images of graphs for comparison analysis are stored in PSD analysis forder
  PSD analysis in different bands generates continious spectrum after averaging it over channels and then over freq gives final average psd. The comparison graph are given as bar graph in PSD analysis folder images. The avegrage over channels is comparatively plotted in graphs Figure-1 to Figure-5 in their respective bands(delta, theta, alpha, beta, gamma) for more clear understanding.

  
#Task2: Model Training:
  The file train_model.ipynb provides training of EEGNet model where in-subject train_test_split provided accuracy of 75%(without normalising data) which after normalisation gave an accuracy of 78%.
  The cross subject accuracy remains at 75.04% for EEGNet model before and after normalising with an f1-score of 0.43 through both iterations of training.

  The file train_other.ipynb provided training of TSception model where the in-subject validation accuracy is 76%(for normalised data) and 74.22%(for original data).
