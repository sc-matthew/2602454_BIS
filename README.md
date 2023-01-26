# 2602454: Business Intelligence System
---
* github: https://github.com/prasertcbs/454_2566.git
* [cheat sheet](https://github.com/prasertcbs/cheatsheet) 
# Week 1: 11-Jan-2023
* [ ] [week 1 clips](week1_clips.md)
## books
- [Python for Data Analysis, 3E](https://wesmckinney.com/book/)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
	- [Jupyter Notebook on github](https://github.com/jakevdp/PythonDataScienceHandbook)
- [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems 2nd Edition](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646?crid=IKBDA8I0HK7M&keywords=ML+with+Scikitlearn+and+Tensorflow&qid=1665199008&s=books&sprefix=ml+with+scikitlearn+and+tensorflow,stripbooks-intl-ship,167&sr=1-1&linkCode=sl1&tag=thuvu07-20&linkId=9ae74f9edc4575bb1ad3147409df4a53&language=en_US&ref_=as_li_ss_tl)
- [The Machine Learning Simplified: A Gentle Introduction to Supervised Learning](https://www.amazon.com/dp/B0B216KMM4/qid=1653304321)
## [How to ask question](https://stackoverflow.com/help/how-to-ask)
## [Stack Overflow Survey 2022](https://survey.stackoverflow.co/2022/#technology-most-popular-technologies)
## Intro to data science
* [ ] [Job market](https://www.facebook.com/skooldio/photos/a.457984764545584/1643356276008421/)
* [ ] [Data Science in Business](./cheatsheet/ds%20for%20business.pdf)
* [ ] [CRISP model: CRoss-Industry Standard Process for data mining](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining#/media/File:CRISP-DM_Process_Diagram.png)
* [ ] [machine learning](https://jakevdp.github.io/PythonDataScienceHandbook/05.01-what-is-machine-learning.html)
* [ ] TARGET teenage pregnancy case 2012
  * [ ] [New York Times](https://www.nytimes.com/2012/02/19/magazine/shopping-habits.html)
  * [ ] [Forbes](https://www.forbes.com/sites/kashmirhill/2012/02/16/how-target-figured-out-a-teen-girl-was-pregnant-before-her-father-did/?sh=5199355b6668)
  * [ ] [video clip](https://nyti.ms/2kH3YzT)
* [ ] [Netflix: the social dilemma](https://www.netflix.com/th-en/title/81254224)
* [ ] [Netflix: the great hack](https://www.netflix.com/th-en/title/80117542)
    * [ ] [wiki](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal)
* [ ] explore data
  * [ ] sample data:
    * [ ] [bigmac index](example/bigmac_index.csv)
    * [ ] [telecom customer churn](ml/telecom-churn-prediction.ipynb)
    * [ ] [food nutrition](example/nutrients.csv)
    * [ ] [interactive notebook](example/interactive_dataframe_mcdonald.ipynb)
* [ ] pandas vs sql
    * [ ] [pandas](https://www.youtube.com/watch?v=f3CLdRl-zyQ&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz)
    * [ ] [from SQL to pandas](example/postgres_sql_vs_pandas.ipynb)
* [ ] Install Python and packages
  * [ ] installation:
    * [ ] [Install Python using miniconda](https://www.youtube.com/watch?v=NxIwWGKuSco&list=PLoTScYm9O0GH4YQs9t4tf2RIYolHt_YwW&index=4)
```sh
pip install -U nodejs
pip install -U jupyterlab ipywidgets
pip install -U pandas matplotlib seaborn scipy scikit-learn joblib lxml beautifulsoup4 pillow sqlalchemy openpyxl xlrd statsmodels tabulate pandas-datareader
pip install -U plotly
pip install -U psycopg2-binary
pip install -U ipython-sql pgspecial
pip install -U graphviz
pip install -U xgboost catboost lightgbm shap
pip cache purge
```
#### Clone class materials
* [ ] [install git](https://www.git-scm.com/)
  * [ ] [how to use github](https://www.youtube.com/watch?v=hSQgAA8bj6I&list=PLoTScYm9O0GGsV1ZAyP4m_iyAbflQrKrX)
  * [ ] Windows (`cmd`)
    * [ ] clone repository
      ```bat
      cd %userprofile%
      git clone https://github.com/prasertcbs/454_2566.git beagle
      ```
    * [ ] pull latest files from git repo
      ```bat
      cd %userprofile%\beagle
      git pull
      ```
  * [ ] mac/Windows (`PowerShell`)
    * [ ] clone repository
      ```sh
      cd ~
      git clone https://github.com/prasertcbs/454_2566.git beagle
      ```
    * [ ] pull latest files from git repo
      ```sh
      cd ~/beagle
      git pull
      ```
### Basic Command line
#### [Windows command line](https://www.youtube.com/watch?v=C5fCLAA7Mmc&list=PLoTScYm9O0GGpQRdTu3Y8sGA8MsBuojhV)
* [ ] `dir`: list files
* [ ] `md`: make directory
* [ ] `cd`: change directory
* [ ] `copy`: copy file
* [ ] `move`: move file
* [ ] `del`: delete file
#### [macOS Terminal command line](https://www.youtube.com/watch?v=-5SI3xFM_3E&list=PLoTScYm9O0GGWXd_4sYsADmM4og6vU1Zh)
* [ ] `ls`: list files
* [ ] `mkdir`: make directory
* [ ] `cd`: change directory
* [ ] `cp`: copy file
* [ ] `mv`: move file
* [ ] `rm`: delete file
* [ ] `man`: command manual
### Video tutorials
* [ ] [Python programming](https://www.youtube.com/watch?v=bu6kwrpOqFM&list=PLoTScYm9O0GH4YQs9t4tf2RIYolHt_YwW)
* [ ] [JupyterLab](https://www.youtube.com/watch?v=3PkMNsUCAM0&list=PLoTScYm9O0GEour5CiwfSnoutg3RyA76O)
* [ ] [learn pandas](https://www.youtube.com/watch?v=f3CLdRl-zyQ&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz)
* [ ] [learn numpy](https://www.youtube.com/watch?v=ts2L5mtMMi8&list=PLoTScYm9O0GFNEpzsCBEnkUwgAwOu_PWw)
* [ ] [learn matplotlib](https://www.youtube.com/watch?v=WOEOH8OV99k&list=PLoTScYm9O0GGRvUsTmO8MQUkIuM1thTCf)
* [ ] [learn seaborn](https://www.youtube.com/watch?v=TJ2xK3AV5RQ&list=PLoTScYm9O0GGC9QvLlrQGvMYatTjnOUwR)
* [ ] [learn scikit-learn](https://www.youtube.com/watch?v=AdDvPCarDyI&list=PLoTScYm9O0GH_3VrwwnQafwWQ6ibKnEtU)
* [ ] [basic command line](https://www.youtube.com/playlist?list=PLoTScYm9O0GFpyK3BixJNjkPBUhJuPCl-)
* [ ] [basic github](https://www.youtube.com/watch?v=hSQgAA8bj6I&list=PLoTScYm9O0GGsV1ZAyP4m_iyAbflQrKrX)
### Recommended resources
* [ ] [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
  * [ ] [Jupyter Notebook on github](https://github.com/jakevdp/PythonDataScienceHandbook)
* [ ] [cheat sheet](https://github.com/prasertcbs/cheatsheet)
* [ ] [pandas documentation](https://pandas.pydata.org/docs/)
* [ ] [Kaggle](https://www.kaggle.com/)
# Week 2: 18-Jan-2023
* [ ] [week 2 clips](./week2_clips.md)
## intro to pandas
## [Read data techniques](https://www.youtube.com/watch?v=fNJb52eMLNg&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=97)
* [ ] separator
* [ ] na_values
## Data selection
* [ ] [Series](https://www.youtube.com/watch?v=dX6COdB7yRo&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=22)
  * [ ] index (as dictionary), slice
* [ ] [DataFrame](https://www.youtube.com/watch?v=NrcAJFJo1R4&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=23)
  * [ ] index, slice
  * [ ] [loc](https://www.youtube.com/watch?v=k5rjyOhG3kg&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=74)
  * [ ] [iloc](https://www.youtube.com/watch?v=2mRwQ2_p0Ws&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=76)
## Data types
* [ ] number (int, float)
* [ ] object
  * [ ] [to_numeric](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_numeric.html)
## EDA
* [ ] describe()
* [ ] aggregate functions
* [ ] correlation
* [ ] visualizing data
  * [ ] histogram
  * [ ] boxplot
  * [ ] scatterplot
## Extra:
* [ ] Customize your `terminal`
  * [ ] `Windows` (PowerShell)
    * [ ] Install Windows Terminal from Microsoft Store
    * [ ] [Install PowerShell 7](https://www.youtube.com/watch?v=FFLrObUKgwg)
    * [ ] [Install Oh-my-posh](https://www.youtube.com/watch?v=Soiqw0ooFRM)
    * [ ] [Customize Windows Terminal](https://www.youtube.com/watch?v=hgx1JnU5B4k)
  * [ ] `macOS`
    * [ ] [Install homebrew](https://www.youtube.com/watch?v=48oicKQ2qgQ)
    * [ ] Install iterm2 via homebrew
      * [ ] `brew install --cask iterm2`
    * [ ] [Install Oh-my-zsh](https://www.youtube.com/watch?v=-5SI3xFM_3E)
---
---
# Week 3: 25-Jan-2023
* [ ] [week 3 pandas clips](./week3_clips.md)
* [ ] [week 3 visualization with seaborn clips](./4%20seaborn.md)
## team assignment 1 due @10:30
## [Read data techniques](https://www.youtube.com/watch?v=fNJb52eMLNg&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=97)
* [ ] nrows
* [ ] parse_dates
* [ ] sample
* [ ] transpose
* [ ] read Excel from URL
  * [ ] [disney](https://github.com/prasertcbs/basic-dataset/raw/master/disney_movie/clean/disney.xlsx)
* [ ] read html table from web
  * [ ] [most-followed Instagram accounts](https://en.wikipedia.org/wiki/List_of_most-followed_Instagram_accounts)
## Save data technique
* [ ] csv
* [ ] Excel
## Data types
* [ ] [category](https://youtu.be/ulDIl1E_VVA)
  * [ ] astype('category')
* [ ] [datetime](https://youtu.be/Zfp5YVZtwYc)
  * [ ] [to_datetime](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html)
## Missing values
* [ ] [sample data](https://github.com/prasertcbs/basic-dataset/raw/master/msleep.csv)
## Data cleansing
* [ ] basic regular expression
---
# Week 4: 1-Feb-2023
* [ ] [week 4 clips](./week4_clips.md)
## Internship
* [ ] ~ 2 months (~300 hours) 
  * [ ] during summer (June-August)
  * [ ] during first semester (August-December)
## Build your data science portfolio
* [ ] [Kaggle](https://www.kaggle.com/)
  * [ ] create account
    * [ ] kaggle_user_id: `mis6xxxxxxxx`
  * [ ] notebook
    * [ ] create
      * [ ] [Top 200 common passwords Data](https://www.kaggle.com/prasertk/top-200-common-passwords-in-2021/data)
    * [ ] copy & edit
      * [ ] [Apple product price lists Data](https://www.kaggle.com/prasertk/apple-product-price-list-from-26-countries-2022)
      * [ ] [Apple product price lists Notebook](https://www.kaggle.com/prasertk/clean-apple-product-price-lists-across-countries)
    * [ ] download
    * [ ] upload
  * [ ] share notebook
    * [ ] private
    * [ ] public
  * [ ] download data
    * [ ] [Apple product price lists](https://www.kaggle.com/prasertk/apple-product-price-list-from-26-countries-2022)
  * [ ] create data
    * [ ] private
    * [ ] public
      * [ ] [Retirement-Index-2022-Final-Scores.csv](https://internationalliving.com/the-best-places-to-retire/)
## Regular expression (regex)
* [ ] concepts
* [ ] [regex101](https://regex101.com/)
  * [ ] [Sample data](https://regex101.com/r/clQQFg/1)
  * [ ] [lookbehind](https://regex101.com/r/ptNCNj/1)
    * [ ] `(?<=\d)o`
* [ ] [cheat sheet](https://cheatography.com/davechild/cheat-sheets/regular-expressions/pdf/)
### pandas str.*
* [ ] str.split
* [ ] str.replace
* [ ] str.contains
* [ ] str.match
* [ ] str.extract
* [ ] str.extractall
## Keyboard shortcuts
| Action          | Shortcut                                        |
|-----------------|-------------------------------------------------|
| Select line     | <kbd>Ctrl</kbd>+<kbd>L</kbd>                    |
| Unindent code   | <kbd>Ctrl</kbd>+<kbd>[</kbd>                    |
| Indent code     | <kbd>Ctrl</kbd>+<kbd>]</kbd>                    |
| Move line up    | <kbd>Alt</kbd>+<kbd>Up</kbd>                    |
| Move line down  | <kbd>Alt</kbd>+<kbd>Down</kbd>                  |
| Copy line down  | <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Down</kbd> |
| Format document | <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>F</kbd>    |
---