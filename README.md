# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?

    100 million cases during the covid pandemic

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

    3 million deaths during the covid pandemic

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

    California has the highest amount of cases and Maryland has the lowest amount of cases

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

    The total number of cases is 102070172 and the total number of deaths is 1115001 did suprise me since I thought covid was a lot more more severe than it.
    I'm not suprised that California has the highest number of case because it is the most populated state and the lowest cases American Samoa doesn't suprise me either because I've never heard of it.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

    The county with the highest number of cases in Washington is King's county and this is not suprising because King's county is very big and covid can easily spread here.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

    There are more observations in counties because there are counties that tied with the lowest deaths. Deaths are a lot less common/variable so tied for the lowest amount of deaths can happen more often.


## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

    Even though there are 27 rows that are inconsistent, that is only 27/844. 3.2% of the data is not exact but the other
    96.8% is. Even when it is inaccurate, it is also not off by too much and so people should still use this data.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

    I'm interested in this particular question because it is interesting to see which state had the most deaths and the follow up states. Whether
    it was a larger population or fewer amount of vaccinations, we can understand it more by ranking it.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

    On the news, it keep stating that people were dying a lot so I was curious on how many deaths there were exactly and why I chose that question by state. Nothing really suprised me and next time I would view each variable after I made it to check on each answer.