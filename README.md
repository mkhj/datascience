# Data science

## Getting started

* [Download Anaconda Distribution](https://www.anaconda.com/download/#macos)
* [Installing Anaconda on Mac OS X](https://www.datacamp.com/community/tutorials/installing-anaconda-mac-os-x)

#### Troubleshooting
If the path for you anaconda distrubition is not showing when _'echo $PATH'_ try executing _'source ~/.bash_profile'_

## Tips & Tricks

#### Cheatsheats

* [Data science](https://github.com/mkhj/Data-science/tree/master/Cheat%20sheets)
* [Python Debugger](https://github.com/mkhj/Data-science/blob/master/Cheat%20sheets/Python%20Debugger%20Cheatsheet.pdf)
* [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - [Table generator](https://www.tablesgenerator.com/markdown_tables)

## Articles

* [How to Write a Spelling Corrector - Peter Norvig](http://norvig.com/spell-correct.html)

## Books

* [Pattern Recognition and Machine Learning - Christopher M. Bishop](https://www.amazon.com/Pattern-Recognition-Learning-Information-Statistics/dp/0387310738)
* [Python Data Science Handbook - Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
* [Applied Text Analysis with Python](https://www.amazon.com/Applied-Text-Analysis-Python-Language-Aware/dp/1491963042)

#### Online resources from books

* [Applied Text Analysis with Python](https://github.com/foxbook/atap)
* [Real-World Machine Learning](https://github.com/brinkar/real-world-machine-learning)
* [Practical Machine Learning with Python](https://github.com/dipanjanS/practical-machine-learning-with-python)
* [Programming Collective Intelligence](https://github.com/arthur-e/Programming-Collective-Intelligence)
* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook)

## Version control

* [Using GitHub Desktop with GitLab](https://community.reclaimhosting.com/t/using-github-desktop-with-gitlab/876)

## Datasets

* [FiveThirtyEight: Data and code behind the articles and graphics](https://github.com/fivethirtyeight/data)
* [Kaggle datasets](https://www.kaggle.com/datasets)
* [KDnuggets Dataset](https://www.kdnuggets.com/datasets/index.html)
* [Seaborn datasets](https://github.com/mwaskom/seaborn-data)
* [UCI's Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.html)
* [World Bank](https://data.worldbank.org/)
* [World Health Organization](http://www.who.int/gho/en/)
* [Canada's Open Data Exchange](https://codx.ca/)
* [UK Government Data](https://data.gov.uk/)
* [US Government Data](https://www.data.gov/)
* [UNICEF Data](https://data.unicef.org/)
* [IBM Sample Data Sets](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/)

## Useful packages

* [strip output from Jupyter and IPython notebooks](https://github.com/kynan/nbstripout)
* [scrubadub - Remove personally identifiable information from free text](http://scrubadub.readthedocs.io/en/stable/index.html)

## Resources for online courses

* [Introduction to data science in python](https://github.com/sidsriv/Introduction-to-Data-Science-in-python)

## Natural language processing (NLP)

### SpaCy

#### Guide
* [Introduction to spaCy for NLP and Machine Learning](https://github.com/NSchrading/intro-spacy-nlp)

## Database & ORM

### SQLAlchemy
* [Introduction to SQLAlchemy and Jupyter Notebooks](https://github.com/LeeBergstrand/Jupyter-SQLAlchemy-Tutorial/blob/master/Jupyter-SQLAlchemy.ipynb)
* [Connect to Microsoft SQL Server](https://docs.sqlalchemy.org/en/latest/dialects/mssql.html#module-sqlalchemy.dialects.mssql.pyodbc)

#### Guide
* [Parameterize Database Queries](https://security.openstack.org/guidelines/dg_parameterize-database-queries.html)
* [SQL Expression Language Tutorial](https://docs.sqlalchemy.org/en/latest/core/tutorial.html) 

#### SQLAlchemy Troubleshooting

##### Error message: Library not loaded: /usr/local/opt/unixodbc/lib/libodbc.2.dylib
If you get the above error when trying to connect to a MSSQL database using SQLAlchemy then follow the link to install MS ODBC driver
* [Installing the Microsoft ODBC Driver for SQL Server on Linux and macOS](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-2017)

##### Error message: ylibc++abi.dylib: terminating with uncaught exception of type std::runtime_error
* Try using "ODBC Driver 13 for SQL Server" if you receive this error when using "ODBC Driver 17 for SQL Server"
