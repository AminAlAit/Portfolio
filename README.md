## [The Big Game](https://github.com/AminAlAit/shows-big-game)
### [TV, Halftime Shows, and Football](https://github.com/AminAlAit/shows-big-game)
<span style="background-color: #DCDCDC">R</span> 
<span style="background-color: #DCDCDC">Data Visualization</span> 
<span style="background-color: #DCDCDC">Data Manipulation</span> 
<span style="background-color: #DCDCDC">Data Cleaning</span> 

### Questions we will touch upon:
1.    What are the most extreme game outcomes?
2.    How does point difference affect television viewership?
3.    How have viewership, TV ratings, and advertisement costs evolved?
4.    Who are the most prolific musicians in terms of halftime show performances?

In this notebook, I will be using the following package(s): 
1.    tidyverse

![](/images/superbowl.png)

________________________

## [VEISHE Riots](https://github.com/AminAlAit/VEISHEA-riots-2)
### [Part 2](https://github.com/AminAlAit/VEISHEA-riots-2)
<span style="background-color: #DCDCDC">R</span> 
<span style="background-color: #DCDCDC">Data Visualization</span> 
<span style="background-color: #DCDCDC">Data Manipulation</span> 
<span style="background-color: #DCDCDC">Data Cleaning</span> 
<span style="background-color: #DCDCDC">Date/Time Manipulation</span> 

1.    What day has the most tests?
2.    When are these tests being administered?
3.    Does football has something to do with BAC?
4.    Home advantage, alcohol disadvantage?
5.    Basketball, or football? Which has more influence on our data?
6.    How did the VEISHEA Cancellation affect the patterns?

The dataset contains the following variables: 
1.    DateTime - date & time of test (datetime, "America/Chicago")
2.    Location - who administered the test, Ames PD or ISU PD? (char.)
3.    Gender - gender (M,F) of person being tested (char.)
4.    Res1 - first breath alcohol reading (num.)
5.    Res2 - second breath alcohol reading (num.)

In this notebook, I will be using the following packages: 
1.    tidyverse
2.    lubridate
3.    ggridges
4.    ggplot2
5.    readr
6.    dplyr

![](/images/veishea_riots_2.png)

________________________

## [VEISHE Riots](https://github.com/AminAlAit/VEISHEA-riots-1)
### [Part 1](https://github.com/AminAlAit/VEISHEA-riots-1)
<span style="background-color: #DCDCDC">R</span> 
<span style="background-color: #DCDCDC">Data Visualization</span> 
<span style="background-color: #DCDCDC">Data Manipulation</span> 
<span style="background-color: #DCDCDC">Data Cleaning</span> 

1.    What is the busiest police department in Ames?
2.    Which hours of the day have the most and least breathalyzer tests? 
3.    Which month will have the most recorded tests?
4.    Whom is given more breath alcohol tests? Males or Females?

The dataset contains the following variables: year, month, day, hour, location, gender, Res1, Res2.

In this notebook, I will be using the following packages: 
1.    dplyr
2.    readr
3.    ggplot2
4.    lubridate

![](/images/veishea_riots.png)

________________________

## [Visualizing Inequalities in Life Expectancy](https://github.com/AminAlAit/life_exp)
### [A GGPlot2 Tutorial](https://github.com/AminAlAit/life_exp)
<span style="background-color: #DCDCDC">R</span> 
<span style="background-color: #DCDCDC">Data Visualization</span> 
<span style="background-color: #DCDCDC">Data Manipulation</span> 
<span style="background-color: #DCDCDC">Data Cleaning</span> 

1.    Do women live longer than men? How long? Does it happen everywhere? 
2.    Is life expectancy increasing? Everywhere? 
3.    Which is the country with the lowest life expectancy? Which is the one with the highest?
4.    How has life expectancy evolved by gender?

In this project, we will answer all these questions by manipulating and visualizing United Nations life expectancy data using ggplot2.

The dataset can be found [here](http://data.un.org/Data.aspx?d=GenderStat&f=inID:37&c=1,2,3,4,5,6&s=crEngName:asc,sgvEngName:asc,timeEngName:desc&v=1) and contains the average life expectancies of men and women by country (in years). It covers four periods: 1985-1990, 1990-1995, 1995-2000, and 2000-2005.

In this notebook, I will be using the following packages: 
1.    dplyr
2.    tidyr
3.    ggplot2

![](/images/lifeexp.jpg)
Picture source: worldatlas.com

________________________

## [FIFA 2019 Women's World Cup](https://github.com/AminAlAit/19wwc)
### [A Data Tour Around Venues & Attendance Numbers](https://github.com/AminAlAit/19wwc)
<span style="background-color: #DCDCDC">R</span> 
<span style="background-color: #DCDCDC">Data Visualization</span> 
<span style="background-color: #DCDCDC">Data Manipulation</span> 
<span style="background-color: #DCDCDC">Data Cleaning</span> 

We are going on a de·tour to determine which match and stadium had the highest attendance during the 2019 FIFA Women's World Cup. 
Why? because we can, of course. 
We'll bring out our data importing and cleaning skills to dig through the dirty data, clean it up, and present it in the form of informative polished graphs.

We'll go over questions like: 
1.    What match had the highest attendance?
2.    In what stadium was the match with the highest attendance played?

In this notebook, I will be using the following packages: 
1.    readr
2.    dplyr
3.    tidyr
4.    ggplot2

![](/images/19wwc.jpg)

________________________

## [Nobel Prize Winners](https://github.com/AminAlAit/nobel_prize)
### [A Visual History & Analysis](https://github.com/AminAlAit/nobel_prize)
<span style="background-color: #DCDCDC">R</span> 
<span style="background-color: #DCDCDC">Data Visualization</span> 
<span style="background-color: #DCDCDC">Data Manipulation</span> 
<span style="background-color: #DCDCDC">Data Cleaning</span> 

The Nobel Prize is perhaps the world's most well known scientific award. Every year it is given to scientists and scholars in chemistry, literature, physics, medicine, economics, and peace. The first Nobel Prize was handed out back in 1901, and at that time the prize was Eurocentric and male-focused, but nowadays it's not biased in any way. Surely, right?

Well, let's find out about that! We'll go over questions like: 
1.    What characteristics do the prize winners have? 
2.    Which country gets it most often? 
3.    Has anybody gotten it twice?

The [dataset](https://www.kaggle.com/nobelfoundation/nobel-laureates) used in this project is from The Nobel Foundation on Kaggle.

In this notebook, I will be using the following packages: 
1.    lubridate
2.    tidyverse
3.    ggplot2

![](/images/nobel.jpg)

________________________

## [Crime Study](https://github.com/AminAlAit/crime_study_sf)
### [Data Science for Social Good](https://github.com/AminAlAit/crime_study_sf)
<span style="background-color: #DCDCDC">R</span> <span style="background-color: #DCDCDC">Data Visualization</span> <span style="background-color: #DCDCDC">Data Manipulation</span> <span style="background-color: #DCDCDC">Data Cleaning</span> <span style="background-color: #DCDCDC">Case Studies</span>

Quantitative analyses can have a significant impact on initiating change within one's community. When analyzed responsibly, data can provide evidence to understand difficult social issues correctly. In this project, you will leverage publicly available data to interpret crime patterns within the city of San Francisco.

The dataset used in this project is hosted on [Kaggle](https://www.kaggle.com/san-francisco/sf-police-calls-for-service-and-incidents) and updated daily. 
Note: some of the original column names are altered for adherence to a standard naming scheme.

In this notebook, I will be using the following packages: 
1. lubridate
2. tidyverse
3. ggplot2
4. ggmap

![](/images/sf_crime_study.png)

________________________

## [Candy Crush Saga](https://github.com/AminAlAit/candycrush_difficulty)
### [Studying Level Difficulty in Candy Crush Levels](https://github.com/AminAlAit/candycrush_difficulty)
<span style="background-color: #DCDCDC">R</span> <span style="background-color: #DCDCDC">Data Visualization</span> <span style="background-color: #DCDCDC">Data Manipulation</span> <span style="background-color: #DCDCDC">Data Cleaning</span> <span style="background-color: #DCDCDC">Case Studies</span> <span style="background-color: #DCDCDC">Probability</span> <span style="background-color: #DCDCDC">Statistics</span>

Candy Crush Saga is a hit mobile game developed by King (part of Activision-Blizzard) that is played by millions of people all around the world.

In this Project, you will get to work with a real Candy Crush dataset and use this data to estimate level difficulty. This Project assumes you can manipulate data frames using dplyr and make plots using ggplot2.

This project uses data from anonymous players playing one "episode" of the game, in the year 2014.

In this notebook, I will be using the following packages: 
1. readr
2. dplyr
3. ggplot2

![](/images/candycrush.png)

________________________

## [Kaggle](https://github.com/AminAlAit/exploring_kaggle)
### [Exploring the Data Science Survey](https://github.com/AminAlAit/exploring_kaggle)
<span style="background-color: #DCDCDC">R</span> <span style="background-color: #DCDCDC">Data Visualization</span> <span style="background-color: #DCDCDC">Data Manipulation</span> <span style="background-color: #DCDCDC">Case Studies</span>

When beginning a career in data science, one often wonders what programming tools and languages are being used in the industry, and what skills one should learn first. By exploring the 2017 Kaggle Data Science Survey results, you can learn about the tools used by 10,000+ people in the professional data science community.

This project uses a subset of the 2017 Kaggle Machine Learning and Data Science Survey dataset.

In this notebook, I will be using the following packages: 
1. tidyverse
2. dplyr
3. tidyr
4. ggplot2

![](/images/Kaggle.png)

________________________

## [Phyllotaxis](https://github.com/AminAlAit/phyllotaxis)
### [Drawing Flowers Using Mathematics](https://github.com/AminAlAit/phyllotaxis)

<span style="background-color: #DCDCDC">R</span> <span style="background-color: #DCDCDC">Data Visualization</span> <span style="background-color: #DCDCDC">Data Manipulation</span> <span style="background-color: #DCDCDC">Case Studies</span>

> "The scientist does not study nature because it is useful; he studies it because he delights in it, and he delights in it because it is beautiful." 
> \- Henri Poincaré

There are many examples of natural facts that can be described in mathematical terms. Nice examples are the shape of snowflakes, the fractal geometry of romanesco broccoli or how self-similarity rules the growth of plants.

In this notebook, I will be using the ggplot2 package. This package is home to many important features that will be useful not only to do art but also to represent data in real-life problems.

![](/images/Phyllotaxis.png)
