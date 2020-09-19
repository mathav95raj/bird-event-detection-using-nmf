# bird-event-detection-using-nmf

Implementation the paper "Masked Non-negative Matrix Factorization for Bird
Detection Using Weakly Labeled Data" by
Iwona Sobieraj, Qiuqiang Kong, Mark D. Plumbley

Masked Non negative matrix factorization for identifying presence of bird sounds in a given wav file. Masked nmf is used to learn a joint dictionary model of bird and non bird sounds. Using the trained dictionary, activation matrices of test data are obtained and pooled over time and given as input feature to a random forest classifier

Masked NMF was used to learn discriminative dictionaries of bird and non bird Mel spectrogram features from a weakly labeled freefield1010 bird audio dataset. The resultant dictionaries were used to extract  features from test dataset that resulted in an accuracy of 86.3 % using random forest as classifier

dataset : http://dcase.community/challenge2018/task-bird-audio-detection
