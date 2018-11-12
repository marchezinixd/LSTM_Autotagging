# Music Autotagging using LSTM

Each song has its characteristics,
whether they are genres (rock, emo), type of instruments (guitar, piano), emotional infor-
mation (sad, happy), etc. This information determines its classification or label. The large
number of songs, as well as their diversity, make manual labeling unfeasible, creating the
need to automate this process. Therefore, this work proposes to model and develop a method
of automatic labeling of music using a particular type of recurrent neural network called
Long Short Term Memory (LSTM), able to learn short- and long-term temporal patterns.
In the construction of the model, the bases of the Million Song and Last.fm, composed by
the characteristics of the songs and their respective labels were used. These bases were
divided into two sets, training, and test, following the division pre-established by the base
of labels. The used metric was the AUC (Area Under the ROC Curve).

This was a final project done in CEFET-MG Using the Million Song Dataset (MSD). 

It was build on top of AWS. 

The final version used GPUs to process faster.

The pdf is in portuguese, but it describe all the methodology and the tests made, with all the references used.

The Last.fm dataset and Million Song Dataset can be found in the link:

- https://labrosa.ee.columbia.edu/millionsong/

