# DS6021-ML-Final-Project

## NEEDS: 
- 6-8 slide presentation
- original dataset in csv or excel format
      - raw & clean versions
- compiled code
- published app


**who is the most “attractive” in the cohort?**


Notes from meeting with Sheng (10/06): 
- https://github.com/Aksoylu/GoldenFace
- training model on random face data then test data is the cohort pics? 
- open cv = another good library
    - image processing functions have been embedded in here
    - good processing times
    - most efficient 

- landmarks = locations of nose, corner of nose/corner of mouth
    - open cv = has existing functions 
    - facial attractiveness classification

- look at paper from sheng
- could do something like make face more attractiveness (extra credit) 
- racial bias?
      - eastern vs western (because there is bias in golden ratio for western faces)
      - a sub-question
- feminine vs masculine vs androgynous
    - what is considered the most objectively attractive? 

  ## data
  7.2k photos
  https://www.kaggle.com/datasets/ashwingupta3012/human-faces/data


  597 unique photos
  https://www.chicagofaces.org/


## timeline 

oct 6: indivudally research the documentation for open cv & also the papers that sheng sent

oct 13: pull numeric data for multilinear regression 

oct 20: have multilinear regression built out by end of week

oct 27: logit model (figure out what that means)

nov 11: have KNN model built out by end of week

nov 16: have K means model built out by end of week 

dec 1: have MLP model built out by end of week 


continually build out shiny/dash app throughout process 
PRESENTATION BY DEC 

## Oct. 29, 2025 

Plan! 

Make Google Form - Make cookies with Sophie on Tuesday

↳ Send to class

↳ https://forms.office.com/r/Y97GA6zShT

↳ Collect headshots

Cat Vars

↳ Odds of golden ratio

↳ Expression – happy, sad

↳ Gender

↳ Race

Num Var

↳ Face width

↳ Face height

↳ Face eye dist

↳ Face mouth width

Random Questions?
- is the golden ratio biased toward gender, race, or expression ?
- 


## Oct 29: 


DATA COLLECTION + WRANGLING

-sent out google form, incetivized
-deleted repeats, incorrect form usage, edited/omitted photos where face was blocked. 
-added instructors manually
-more time on data engineering rather than defining stuff

-overall face shape: face height should be 1.618x larger than face width
-eye spacing: distance between eyes should be approx equal to width of one eye
-lip fullness: lower lip should be 1.18x larger than volume of upper lip
-nose length: lenght of nose should be in proportion to the distance from the nose to the chin 

- target variable: average the ratios and then compare to ideal ratio(?)

multiclasss logistic regression?
numeric value of beauty?


NEED TO - 
* LINEAR/GLM- lip fullness 
* LOGIT- golden ratio (how close to golden ratio- 5 levels of classification)
    **  Based on X,Y Predictors, what category of golden ratio does this
    **  How Biased is it towards gender/race
* KNN- ^^
* KMEANs-
* PCA-




## Nov 5 - next steps (data engineering)

- Bella and Sophie to talk to Kropko about webscraping code for sharepoint pictures to have everything in the same "place"
      - figure out how to webscrape (ethically)

- Once all faces are in "one" place, data engineer with opencv to get measurements of facial features
        - Variables unknown
- **FINISHED BY** 11/19



