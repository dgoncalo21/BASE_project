# BASE_project
Biofeedback Augmented Software engineering project which aims to assess/ predict different levels of cognitive effort in programmers using non-intrusive biosignals during software code inspection. Focus of my MSc thesis and research grant. MATLAB/ Python.

In my MSc thesis it was concluded that HRV (feature extracted from ECG) can be used to distinguish different code complexities through programmers' mental effort impact on the autonomous nervous system.
It was also possible to correlate programmers' mental effort with their perceived code complexity which didn't happen with the most used software engineering complexity metrics.
Best results were obtained with normalized mutual information algorithm and SVM with a radial basis function kernel, f1-score over 80% with a 10-fold cross validation (other options were tested for feature space reduction - PCA and classification - LDA). 
Significance tests were also conducted for the different HRV features.

For further information regarding my thesis and the overall project, the document "thesis presentation.pdf" is a summary of my findings that I presented in the 6th ENBENG 2019 in Lisbon.


During my research grant 3 scientific papers were published and 1 accepted with the help of the investigators and professors involved in the project:

-> ICSE - findings of my thesis;

-> EMBC - similar study was made but with the EEG signal that led to coherent results;

-> DSN - study that made use of pupilography with a analysis based on boxplots and outliers that resulted in similar findings;

-> ISSRE - study that used a density based cluster with a combination of HRV, pupillography and eye tracking to isolate problematic code lines and assess local cognitive effort.


Due to confidentiality reasons code and data cannot be shared.
