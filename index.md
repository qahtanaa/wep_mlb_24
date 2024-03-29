# Machine Learning for Beginners

Machine Learning (ML) models are used in various applications, affecting
societies directly or indirectly in daily life. The Machine learning
(ML) field connects computer science and statistics, allowing computers
to use collected data or past experience to solve unseen problems. It’s
a must-have skill for every analyst and data scientist. It is also an
important skill for anyone who wants to draw conclusions and make
scientific suggestions based on collected raw data. A wide range of
successful ML applications exist, including systems to predict customer
behavior, support decision-making, recognize faces or spoken speech,
optimize robot behavior, and extract knowledge from biological data.
During this Workshop, participants will learn how to write and train ML
models that can help in their field of study. Attendees will have the
chance to learn the basics of Python and how to use it to build
machine-learning models. In this Workshop, we will use Google Colab as
our IDE, but students are free to use their favorite IDE.

The materials on this website are
[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) licensed.

![cc](https://mirrors.creativecommons.org/presskit/icons/cc.svg)
![by](https://mirrors.creativecommons.org/presskit/icons/by.svg)

## Lectures

| Day | Date       | Topic                                                                                                |
|----:|:-----------|:-----------------------------------------------------------------------------------------------------|
|   1 | 2024-01-07 | [Basics of Programming](https://qahtanaa.github.io/wep_mlb_24/lectures/day_1/WEP24_Day1_Basics.pdf)  |
|   2 | 2024-01-08 | [Regression](https://qahtanaa.github.io/wep_mlb_24/lectures/day_2/WEP24_Day2_Regression.pdf)         |
|   3 | 2024-01-09 | [Classification](https://qahtanaa.github.io/wep_mlb_24/lectures/day_3/WEP24_Day3_Classification.pdf) |
|   4 | 2024-01-10 | [Clustering](https://qahtanaa.github.io/wep_mlb_24/lectures/day_4/WEP24_Day4_Clustering.pdf)         |
|   5 | 2024-01-11 | [Text Mining](https://qahtanaa.github.io/wep_mlb_24/lectures/day_5/WEP24_Day5_TextMining.pdf)        |

## Exercises

| Day | Date       | Topic                 | HTML                                                                                          | Notebook                                                                                           |
|----:|:-----------|:----------------------|:----------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------|
|   1 | 2024-01-07 | Basics of Programming | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_1/WEP_24_Day1_Basics.html)         | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_1/WEP_24_Day1_Basics.ipynb)         |
|   2 | 2024-01-08 | Regression            | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_2/WEP_24_Day2_Regression.html)     | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_2/WEP_24_Day2_Regression.ipynb)     |
|   3 | 2024-01-09 | Classification        | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_3/WEP_24_Day3_Classification.html) | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_3/WEP_24_Day3_Classification.ipynb) |
|   4 | 2024-01-10 | Clustering            | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_4/WEP_24_Day4_Clustering.html)     | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_4/WEP_24_Day4_Clustering.ipynb)     |
|   5 | 2024-01-11 | Text Mining           | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_5/WEP_24_Day5_TextMining.html)     | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_5/WEP_24_Day5_TextMining.ipynb)     |

## Answers

| Day | Date       | Topic                 | HTML                                                                                                  | Notebook                                                                                                   |
|----:|:-----------|:----------------------|:------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------|
|   1 | 2024-01-07 | Basics of Programming | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_1/WEP_24_Day1_Basics_Answers.html)         | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_1/WEP_24_Day1_Basics_Answers.ipynb)         |
|   2 | 2024-01-08 | Regression            | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_2/WEP_24_Day2_Regression_Answers.html)     | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_2/WEP_24_Day2_Regression_Answers.ipynb)     |
|   3 | 2024-01-09 | Classification        | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_3/WEP_24_Day3_Classification_Answers.html) | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_3/WEP_24_Day3_Classification_Answers.ipynb) |
|   4 | 2024-01-10 | Clustering            | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_4/WEP_24_Day4_Clustering_Answers.html)     | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_4/WEP_24_Day4_Clustering_Answers.ipynb)     |
|   5 | 2024-01-11 | Text Mining           | [HTML](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_5/WEP_24_Day5_TextMining_Answers.html)     | [Notebook](https://qahtanaa.github.io/wep_mlb_24/tutorials/day_5/WEP_24_Day5_TextMining_Answers.ipynb)     |

## Google Colab

During the workshop, we will use [Google
Colab](https://colab.research.google.com/) as our IDE. We will start by
creating a new notebook.

#### Checking the Python version and installing different versions

For checking the version of Python that is already installed, we run the
command:

    !python --version

If we need to install a different version of Python (e.g. 3.7), we can
use:

    !apt-get install python3.7

#### Installing more Libraries

Most of the important libraries that we may need are already installed
in the Google Colab environment. However, if you would like to install
additional libraries, you can use the `pip` command. For example, to
install `py_stringmatching`, you can use the command:

    !pip install py_stringmatching

**Note:** when running system commands in Google colab, we use `!`
before the command. This is common for running system commands in any
notebook environment (you may also use the % symbol
`%pip install py_stringmatching`).

#### Running simple Python code

Run the following Python code and explain what the code is doing:

    t, f = True, False
    print(t and f) 
    print(t or f)  
    print(not t)   

------------------------------------------------------------------------

## About the Speaker

Abdulhakim Qahtan is an assistant professor at the Data Intensive
Systems (DIS) Group, Information and Computing Sciences Department.
Before joining Utrecht University, he worked as a Postdoctoral
Researcher at Qatar Computing Research Institute (QCRI), Hamad Bin
Khalifa University (HBKU), Qatar (2016-2019). Dr. Qahtan earned his PhD
degree from the Machine Intelligence & kNowledge Engineering (MINE) Lab
at King Abdullah University of Science and Technology (KAUST) (2016).  
He completed his B.S. and M.S. in Computer Science at Cairo University,
Egypt and King Fahd University of Petroleum and Minerals (KFUPM), Saudi
Arabia, respectively. He worked as a teaching assistant at Taiz
university, Yemen and a lecturer at KFUPM, Saudi Arabia.  
His current research focuses on data cleaning, data stream mining, time
series analysis, algorithmic fairness and explainable machine learning.

Website: https://www.uu.nl/staff/AAAQahtan

LinkedIn: https://www.linkedin.com/in/hakimqahtan/

Email: a.a.a.qahtan(at)uu.nl
