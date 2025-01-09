# Project XYZ

**Project XYZ** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* Describe your dataset. Choose a dataset of reasonable size to avoid exceeding the repository's maximum size of 100Gb.
* My dataset is based on Car Price Prediction, it was taken from https://www.kaggle.com/datasets/hellbuoy/car-price-prediction/data
* It includes 25 columns that include various different pieces of information on different cars that were purchased including their price.
* It includes 205 rows or entries for each column.


## Hypothesis and how to validate?
* List here your project hypothesis(es) and how you envision validating it (them) 
* After cleaning the data, I have reduced the number of columns down to 15. I expect a number of these variables to be strongly correlated with increased prices, and others not so much.
  For example: I expect variables like horsepower, enginesize, cylinder number, wheelbase, curbweight, carbody, drivewheel and aspiration to be very influential to the price.
               I expect variables such as fuelsystem, brand and mpg to be somewhat responsible for increased prices.
               I expect fuel type to not affect pricing too much and I feel engine location may have too entries with rear engines to draw too many conclusions.
* I would expect to be able to validate them throw plotting numerous types of graphs/charts and clearly visualising how certain variables show significant price changes depending on  
  how high/low they are when it comes to certain numeric variables, and by what type they are when it comes to certain categorical variables. I expect these graphs/chars to show less significant changes for certain variables, proving my hypotheses to be true.
## Project Plan
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

* I initially plan to download the dataset and load it into a dataframe using pandas, using various functions to get an idea of what kind of information is in the dataset.
* I will then try to clean the data by removing any missing values, duplicate values etcu

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- Dataset was taken from https://www.kaggle.com/datasets/hellbuoy/car-price-prediction?resource=download
- Used chatgpt to get correct notation for the function for dropping columns from dataset, tried to find in LMS but was taking too long!
- Used chatgpt to see if any of the enginetype/fuelsystem abbreviations meant the same thing

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.