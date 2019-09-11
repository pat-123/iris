This is a classification problem, to predict the flower type given the petal width/length and sepal width/length

Few points worth mentioning regarding directory structure:
-csv is placed under data/raw/
- Processed csv is places under data/processed after computation
- Test predictions are available under data/submitted
- Notebook is present in notebooks folder
- irir is a package which load all initial packages(__init__.py) and sets data file paths under config.py
  ++ Abstracts the messy paths in the main notebook to here, so that cleaner view can be provided
- scripts folder is a placeholder for future purposes

How to run this?
  ++ start Anaconda prompt and go to this folder's parent locationr and type jupyter notebook
  ++ notebook starts with the parent folder as the base location and you can navigate to different projects from there



-------------------------------------------------- 
what is in there?
--------------------------------------------------
- used scatterplot to visualize the decision boundary
- Used SVC to classify with an accuracy of 96% at best
- Use varying values for gamma and regularization
