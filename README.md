# Envision.github.io

# "Tuning into your tastes": Exploring popular song features and trends
___

## Executive Summary:


## Motivation:
Streaming services have brought about a significant transformation in the music industry, offering users convenient and cost-effective access to a vast catalog of songs. These services play a pivotal role in shaping artist visibility, revenue streams, and listening preferences. Moreover, the publicly available APIs provided by streaming platforms like Spotify, Apple Music, and Amazon Music offer unparalleled insights into various dimensions, including geography, audio features, and time, shedding light on trends among both artists and listeners.<br>
<br>
Throughout our project, we embarked with a set of guiding questions:<br>
* What are the most popular audio features, and how have they evolved over time?<br>
* How has the popularity of artists changed over time?<br>
* Is there a correlation between the evolution of audio features among top artists and the overall trends in popular music?<br>
<br>
While not all of these questions fell strictly within the scope of our analysis, they served as initial guiding points. Ultimately, our deep passion for music and curiosity propelled us to undertake this project, as we sought personal enjoyment and a deeper understanding of the subject matter.



## Aims & Objectives:
### Main objectives:


## Data and Data Challenges:
We used two sources of data for our research:<br>
* Billboard (Billboard API) via Python Package (pypi.python.org/pypi/billboard.py) 
* Spotify (Spotify API) (https://developer.spotify.com/documentation/web-api)<br>

### Data Challenges:
Throughout the data collection section of our investigation our team encountered several challenges.<br>

#### Step 1 Challenges
In Step 1, our objective was to investigate the top 10 artists of the past 5 years using Billboard’s weekly ‘Billboard Hot 100’ charts. 
INSERT PHOTO OF BILLBOARD 100 CHART 

Challenge|Solution|Outcome
:---|:---|:---
A major hurdle we faced was the absence of a direct Billboard API to access the required data. In fact, the Billboard API was officially terminated in May 2013. As a result, we couldn't retrieve the aggregated data or directly aggregate it through Billboard's resources.Our direct search for the most popular artists proved unsuccessful since the Billboard Hot 100 primarily features popular songs rather than individual artists.|Fortunately, we discovered a Python package called Billboard.py that proved instrumental in creating code to aggregate the data. This enabled us to identify the artists with the most entries on the weekly charts over the past five years.However, we identified a strong correlation between the number of songs an artist had entered and their popularity. For example, Drake had 800 songs entered over the five-year period.|This challenge provided valuable insight into the importance of seeking out existing solutions to overcome problems in data analysis.This challenge deepened our understanding of the nature of imperfect data and the necessity to make justifiable statistical leaps when drawing conclusions, a common task for data scientists.



## Methodology:


## Data Visualisation:


## Challenges:


## Conclusion: 
