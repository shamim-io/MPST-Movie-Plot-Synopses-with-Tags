# MPST-Movie-Plot-Synopses-with-Tags
MPST: Movie Plot Synopses with Tags

1.1 Sources and Refernces:
Data Source : https://www.kaggle.com/cryptexcode/mpst-movie-plot-synopses-with-tags#mpst_full_data.csv (https://www.kaggle.com/cryptexcode/mpst-movie-plot-synopses-with-tags#mpst_full_data.csv)
Research paper : https://www.aclweb.org/anthology/L18-1274 (https://www.aclweb.org/anthology/L18-1274)
Research paper : http://ritual.uh.edu/mpst-2018/ (http://ritual.uh.edu/mpst-2018/)

1.2 Business Constraints:
1. Predict as many tags as possible with high precision and recall. 2. Incorrect tags could impact customer experience. 3. No strict latency constraints.

2. Machine Learning Problem:
Contains all the IMDB id, title, plot synopsis, tags for the movies. There are 14,828 movies' data in total. The split column indicates where the data instance resides in the Train/Dev/Test split.
Columns imdb_id
IMDB id of the movie title:- Title of the move
plot_synopsis:- Plot Synopsis of the move
tags:- Tags assigned to the move
split:-Position of the movie in the standard data split
synopsis_source:-From where the plot synopsis was collected
