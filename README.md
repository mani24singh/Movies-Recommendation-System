# Movies Recommendation System
- This Project repository is based on Building a movies recommendation system clone 

## Dataset Details:
The Dataset used for building this recommendation engine is mentioned as below: 
- **Dataset used   :** MovieLens dataset
- **Download Dataset   :** Download Dataset from these following links 
     - Download MovieLens dataset hosted on Kaggle then use [kaggle link](https://www.kaggle.com/rounakbanik/the-movies-dataset/data "Dataset Link")
     - Download MovieLens dataset from its official website then use [GroupLens link](https://grouplens.org/datasets/movielens/latest/ "Dataset Link")
- **Dataset File Format  :** CSV File (Comma-separated values). **NOTE:** Download and save dataset inside input_data folder
- **Types of dataset  :**
     - **The full dataset :** This dataset consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with         12 million relevance scores across 1,100 tags.
          - **NOTE:** We will build a simple Recommendation for movies using The full dataset.
     - **The small dataset :** This dataset comprises of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users. 
          - **NOTE:** All personalised recommender         systems will make use of the small dataset **(due to the limited computing power of our system)**. 
- **Data description  :**
It contains 100004 ratings and 1296 tag applications across 9125 movies. These data were created by 671 users between January 09, 1995 and October 16, 2016. This dataset was generated on October 17, 2016.Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.
- **Data Files Content :**
     - credits.csv
     - keywords.csv
     - links.csv
     - links_small.csv
     - movies_metadata.csv
     - ratings.csv
     - ratings_small.csv
- **List of other dataset available :**
     - MovieLens - Movie Recommendation Data Sets [click link](https://grouplens.org/datasets/movielens/)
     - Netflix Prize Dataset [click link](https://academictorrents.com/details/9b13183dc4d60676b773c9e2cd6de5e5542cee9a)
     - Yahoo! - Movie, Music, and Images Ratings Data Sets [click link](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r)
     - Cornell University - Movie-review data for use in sentiment-analysis experiments [click link](http://www.cs.cornell.edu/people/pabo/movie-review-data/)
     - MovieTweetings - [click link](https://github.com/sidooms/MovieTweetings)
     
## Dependencies Details: 
- Python >=3.5
- pandas
- numpy
- scipy
- scikit-learn
- scikit-surprise
- matplotlib
- seaborn
- jupyter notebook
- jupyter lab
- textblob

## Install dependencies :
### Windows OS :
- **Install Python3 (install python 3.6.4)**
   - Step 1: Download python form this [link](https://www.python.org/downloads/)
   - Step 2: Refer this [link](http://www.openbookproject.net/courses/webappdev/units/softwaredesign/resources/install_python_win7.html) or this [link](https://www.youtube.com/watch?v=V_ACbv4329E) in order to install python to your system.
- **Install anaconda**
   - Step 1: Download Anaconda 5.1 (python 3.6 version) using this [link](https://www.anaconda.com/products/individual#windows)
   - Step 2: See the installation instruction given on this [link](https://conda.io/en/latest/user-guide/install/windows.html#install-win-silent)
   - **Note:** If you have any other version of python then install anaconda which supports that particular version of python.
- **Install dependencies using conda**
   - nltk:             In-built installed with anaconda
   - numpy:            In-built installed with anaconda
   - scipy:            In-built installed with anaconda
   - scikit-learn:     In-built installed with anaconda
   - scikit-surprise:  $ conda install -c conda-forge scikit-surprise
   - Pandas:           In-built installed with anaconda
   - matplotlib:       In-built installed with anaconda 
   - seaborn:          In-built installed with anaconda
   - jupyter notebook: In-built installed with anaconda
   - jupyter lab:      In-built installed with anaconda
   - textblob:         $ conda install -c conda-forge textblob 
 
### Issues with installing surprise package :
- If you are facing issue for installing surprise then try the following links which can help you.
- If conda is not working then try to install surprise using pip
- See this [installation instructions](https://github.com/NicolasHug/Surprise#installation--usage)
- See these links if you have any issues.
   - [link 1](https://groups.google.com/a/continuum.io/g/anaconda/c/yLH46ilPQeo?pli=1)
   - [link 2](https://github.com/NicolasHug/Surprise/issues/89)
   - [link 3](https://github.com/NicolasHug/Surprise/issues/21)
   - [link 4](https://github.com/NicolasHug/Surprise/issues/99)
   - [link 5](https://stackoverflow.com/questions/62042317/cannot-install-scikit-surprise-on-my-jupyter-notebook)

### Install Pycharm IDE:
   - Step 1: Download pycharm IDE community edition by using this [link](https://www.jetbrains.com/edu-products/download/#section=idea)
   - Step 2: Install .exe file.

# Code credit:
- Reference Code Credit for creating this project are:
   - [shravan Kumar Veldurthi](https://in.linkedin.com/in/shravan-kumar-veldurthi-9778b522)
   - [letsupgrade](https://letsupgrade.in/)
   - [Rounak Banik](https://github.com/rounakbanik)
