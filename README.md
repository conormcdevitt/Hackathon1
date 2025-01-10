# Car Price Analysis

**Car Price Analysis** is a data analysis tool designed to show how different variables affect the price of cars.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* My dataset is based on Car Price Prediction, it was taken from https://www.kaggle.com/datasets/hellbuoy/car-price-prediction/data
* It includes 25 columns that include various different pieces of information on different cars that were purchased including their price.
* It includes 205 rows or entries for each column.


## Hypothesis and how to validate?
* After cleaning the data, I have reduced the number of columns down to 15. I expect a number of these variables to be strongly correlated with increased prices, and others not so much.
  For example: I expect variables like horsepower, enginesize, cylinder number, wheelbase, curbweight, carbody, drivewheel and aspiration to be very influential to the price.
               I expect variables such as fuelsystem, brand and mpg to be somewhat responsible for increased prices.
               I expect fuel type to not affect pricing too much and I feel engine location may have too entries with rear engines to draw too many conclusions.
* I would expect to be able to validate them throw plotting numerous types of graphs/charts and clearly visualising how certain variables show significant price changes depending on  
  how high/low they are when it comes to certain numeric variables, and by what type they are when it comes to certain categorical variables. I expect these graphs/chars to show less significant changes for certain variables, proving my hypotheses to be true.
## Project Plan

* I initially plan to download the dataset and load it into a dataframe using pandas, using various functions to get an idea of what kind of information is in the dataset.
* I will then try to clean the data by removing any missing values, duplicate values etc as well as encoding the categorical variables.
* I will then save the data to a new csv file and then use that data to create a few basic charts using matplotlib and seaborn.
* I will use plotly to create more interactive charts and graphs that convey information better.
* I will try try use the charts to explain the correlation between price and other variables.
* I chose these methods mainly based on what we had been taught through the LMS.




## Analysis techniques used


* Used pandas to extract data from the csv file into a dataframe and then edited the contents of the dataframe to suit my needs. 
* Used feature engine and pipeline in order to encode the categorical variables so that they could be used in charts/graphs more easily later in the project.
* Used matplotlib, seaborn and plotly in order to express the data from the dataframe in a visual format.
* Used generative AI to help decide which variables from the dataset I should drop, whether because they were redundant because of other variables present, or if they were just not related to price whatsoever. When I decided to drop even more variables than I had originally planned, I used AI to give me ideas on what variables I should prioritise keeping.
* When I was starting to make my charts/graphs, I felt I was running out of time so I used generative AI to get an idea of what variables I should prioritise when making comparisons as well as which charts/graphs I should use to display the information.



## Unfixed Bugs

* Did you recognise gaps in your knowledge, and how did you address them?

* In terms of gaps in my knowledge, there were a lot of things I knew I could do with pandas, seaborn, plotly etc. but when it came to implementing them, I was unsure of the correct notation/syntax to use at times and had to go back to the LMS or use AI(mostly when I couldn't find it in the LMS) in order to view the examples again in order to display/extract/edit the information I wanted.

## Development Roadmap

* The main challenge I faced was organising everything I had to do from start to finish as this is the first project of this kind/scale I have ever done in Data Analytics. I found myself getting too zoned in on what I was doing and had to do next at times and that led to me wasting time and having to go back and redo sections because I hadn't done things I was supposed to do before moving on to the next task.
* I spent a lot of time on the data cleaning stage of the project and because of the amount of different columns/variables I was going to end up with, I decided to drop a lot more columns than I had initially planned to, and also decided not to encode one variable because I felt it would've added too many new columns and also after asking AI what I should do in that regard I felt that it wasn't necessary because of the libraries I was using and the type of charts/graphs I was going to be showing.
* It was also a challenge remembering all the various function names for various purposes that we have covered so far during the course, I found I had to go back to the LMS or ask AI to get the names and syntax for certain functions that I was aware of, but had forgotten certain parts of it which led to errors in the code.
* I plan to try get a better understanding of featureengine and pipeline in order to minimize the time spent/wasted deciding on how to encode certain variables.
* I hope to get more experience using various graphs/charts so that I no longer have to defer to the LMS as much to look at examples.




## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.
* Pandas was used to create the dataframe and read/edit the data from the dataset, it was then used to create a new file for the 'clean' data.
* Matplotlib, seaborn and plotly were used to create various charts/graphs for visualisation of the data in the new csv file
* Used sklearn and pipeline from feature engine in order to convert some of the categorical variables using OneHotEncoder so that they were given numerical values so I could better utilise them in the visualisation stage.


## Credits 


### Content 

- Dataset was taken from https://www.kaggle.com/datasets/hellbuoy/car-price-prediction?resource=download
- Used chatgpt to get correct notation for the function for dropping columns from dataset, tried to find in LMS but was taking too long!
- Used chatgpt to see if any of the enginetype/fuelsystem abbreviations meant the same thing
- Used LMS for OHE transformation examples and replaced variable names
- Used chatgpt to decide what to do with CarName in terms of encoding, decided to leave it as is based on the information I received
- Used LMS for some examples when making graphs with matplotlib and seaborn
- Mostly used LMS for examples on the plots made using plotly, used chatgpt to edit the height/width of the scatter matrix as I couldn't find it in the LMS


