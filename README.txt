README for Analysis Project

Descriptions
---------------
This repository contains two Jupyter notebook and a README file (this one).
The project is used to analyse data from the given datasets and create a recommendation system from it.

# MAIN DATASETS #

BX-Books.csv
- **ISBN**: International Standard Book Number, a unique identifier for books.
- **Book-Title**: Title of the book.
- **Book-Author**: Author(s) of the book.
- **Year-Of-Publication**: Year when the book was published.
- **Book-Publisher**: Publisher of the book.
- Total Rows: 18,185

BX-Ratings.csv
- **User-ID**: Unique identifier for users.
- **ISBN**: International Standard Book Number, a unique identifier for books.
- **Book-Rating**: Rating given by users to books.
- Total Rows: 204,146

BX-Users.csv
- **User-ID**: Unique identifier for users.
- **User-City**: City where the user is located.
- **User-State**: State where the user is located.
- **User-Country**: Country where the user is located.
- **User-Age**: Age of the user.
- Total Rows: 48,299

# DATA SETS FOR RECOMMENDATION SYSTEMS #

BX-NewBooks.csv
- **ISBN**: International Standard Book Number, a unique identifier for books.
- **Book-Title**: Title of the book.
- **Book-Author**: Author(s) of the book.
- **Year-Of-Publication**: Year when the book was published.
- **Book-Publisher**: Publisher of the book.
- Total Rows: 8,924

BX-NewBooks-Ratings.csv
- **User-ID**: Unique identifier for users.
- **ISBN**: International Standard Book Number, a unique identifier for books.
- **Book-Rating**: Rating given by users to books.
- Total Rows: 26,772

BX-NewBooks-Users.csv
- **User-ID**: Unique identifier for users.
- **User-City**: City where the user is located.
- **User-State**: State where the user is located.
- **User-Country**: Country where the user is located.
- **User-Age**: Age of the user.
- Total Rows: 8,520

# JUPYTER NOTEBOOK #

final_recc_sys.ipynb
- Run pre-processing functions 
- Run 2 recommendation systems for the analysis, one is from Collobaration Filtering and the other is SVD-based system
- Run from top to bottom 



analysis.ipynb
- Run all pre-processing functions and visualizations of the dataset
- Run from top to bottom
- Only include already known Python packages (numpy, pandas, re, seaborn, sns)

Installations 
---------------------------------------------------
- For final_recc_sys.ipynb , make sure to install Surprise package (!pip install surprise)