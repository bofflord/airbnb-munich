# airbnb-munich
Evaluation of Munich Airbnb data

1. Installations
  import numpy as np # linear algebra
  import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
  import matplotlib.pyplot as plt
  # magic word for producing visualizations in notebook
  %matplotlib inline
  # import pandas profiling
  import pandas_profiling
  # import libraries for linear regression
  from sklearn.model_selection import train_test_split 
  from sklearn.linear_model import LinearRegression
  from sklearn import metrics
  # import standard scaler
  from sklearn.preprocessing import StandardScaler
  # import PCA
  from sklearn.decomposition import PCA

2. Project Motivation
  The main purpose of this data science project on Airbnb Data of Munich, Germany is educational. This blog post and analysis was done as a project within the Udacity Data Science Nanodegree. The CRISP-DM process model is applied in practice. As part of this analysis several data science methods (e.g. supervised learning, pca) are applied
  Since the author is currently a resident of Munich, there is also a private interest in understanding how Airbnb in Munich works.
  
3. File Descriptions
  "190818_project4_airbnb_munich.ipynb": Jupyter Notebook used for analysis of Munich Airbnb data.
  "190522_Airbnb_Munich_calendar.zip": zipped csv file with calendar data. Data was downloaded on May 22nd, 2019 from on http://insideairbnb.com/get-the-data.html.
  "190522_Airbnb_Munich_other-data.zip" other zipped csv files with data on listings, listings_detailed, neighbourhoods and reviews.Data was downloaded on May 22nd, 2019 from on http://insideairbnb.com/get-the-data.html.
  "LICENSE": GNU General Public License v3.0
  
4. How to Interact with your project
  Since the main purpose of this analysis is educational, I would really appreciate any feedback on possible improvements in code, modeling and general problem-solving approach. Otherwise it would be may pleasure if my files could serve as orientation or base for other projects.

5. Licensing, Authors, Acknowledgements
  As mentioned above the content is available under the GNU General Public License v3.0.
  I would like to thank first and foremost the team of Inside Airbnb for making the underlying data available.
