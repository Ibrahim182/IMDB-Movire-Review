# launch on <a href='https://www.kaggle.com/code/ibrahimelsayed182/full-pipeline-of-text-preprocessing-bow-model'>Kaggle</a>, <a href='https://colab.research.google.com/drive/1AHhj8BR3KGJ-dtf-Glc6uPitJs-1D8tM?usp=sharing'>Colab</a>
# IMDB-Movie-Review
# The Full pipeline to go from the raw form to the prepared form

__A - Text preprocessing__

  - Data sequencing: each sentence be sequence (list) of words
  - Data cleaning: This step varies from task to task. For some tasks it's better to remove special characters and punctuations, for other they are critical (emotiocons).
  - Text normalization: in general text morphology is a big issue in NLP. Upper and lower cases, stemming and lemmatization, ... etc. It's task dependent.
  - Padding (model dependent): Dense and CNN. RNN can skip this step.

__B- Text preparation__

  - (Binarization/vectorization/digitization): transform words into numbers according to a vocab index.
