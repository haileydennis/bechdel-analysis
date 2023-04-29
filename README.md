## Data
* https://github.com/fivethirtyeight/data/blob/master/bechdel/movies.cshttps://github.com/fivethirtyeight/data/blob/master/bechdel/movies.csv
* https://www.themoviedb.org/?language=en-US

## To Run
* Have a MySQL server running
* Open Bechdel_Analysis_ALL.ipynb
* Install PyMySQL (in Data Storage section - pip install pymysql)
* Configure the Data Storage section with your MySQL info
* Click 'run all'

## Dependencies
* MySQL Server
* PyMySQL
* Pandas
* NumPy
* scikit-learn
* Matplotlib

## Good-to-Knows
* We will be deleting rows with missing values so long as there are very few.
* We will be deleting columns with missing values so long as there are many missing.
* Please note that changes were made after combining files, so the individual files may not be the final result for that section. The Bechdel_Analysis_ALL.ipynb is our polished final product.
