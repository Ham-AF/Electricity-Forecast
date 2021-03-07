    So for this project i settled on trying to see if i could make a good forcasting model trying to predict differences in electrical consumption post covid. I got the data after searching online from this competition website. The data had spanned 3 years, which i was excited about. However when I decided to look through the data, a lot of the column data was taken in different intervals, and there were some large gaps and outliers in the data. By the time i got the data in a workable state i had only a couple of days left.
    After i took care of these things I was left with less data than i assumed, but i took to modeling anyway. I fit all the models i knew, though going any deeper wasnt really possible so as soon as i got a score i just moved on.


EDA
    In this notebook youll find a series of 'scripts' thats cleans the data and displays a certain chunk of the large data sets. This wasnt intention, but there were some programming loops i had to run through where i couldnt set an index as a period without setting it as a date time index first, which causes some repeats just to get certain code blocks running. I tried to go into detail about what the process was and why i chose to only stick with certain csvs.
    
Modeling
    In the modeling notebook youll find me fitting all the basic time series models i know on to the cleaned data
    the ones that were tried were:
    Holt Forcast
    Exponential Smoothing
    Auto Exponential Smoothing
    
    And with the multivariate data i fit:
    SARIMAX
    and a basic Neural Net
    
