# Rio de Janeiro Airbnb Data Analysis

#### Content
1. [What is necessary](#what)
2. [Why I did this](#why)
3. [How I did this](#how)
4. [What I found](#results)
5. [Licensing, Authors, and Acknowledgements](#lic)


## What is necessary <a name="what"></a>

The code was developed in python version 3.8.  
These libraries will be needed to run properly:
-	Pandas ( pip install pandas )
-	NumPy ( pip install numpy )
-	Sklearn ( pip install sklearn )
-	Langdetect ( pip install langdetect )

## Why I did this <a name="why"></a>

The pandemic is/was a terrible moment for one of the most pleasure human activity: travel.  
There is a signal that things getting back to normal.  

Airbnb stands out for easy place booking and its data has a lot of interesting information.  
Taking the Rio de Janeiro data from public data repository of company (it can be found [here](http://insideairbnb.com/get-the-data.html)), I've had tremendous curiosity in answer some questions.  

Specially, I'd like to know:

1. For future months, will there any tendency for booking?  
1. Is there Brazilians different neighborhood preference for stay?
1. What does weight for the price value? What features of accommodations most impact?

## How I did this<a name="how"></a>

All the process of answering these questions was carried out with CRISP-DM methodology.  
CRISP-DM has 6 phases:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment  

In sight of my questions, numbers 1 and 2 was worked using with phases 1, 2, 3 and 6. No model was constructed.  
Different for question 3, which a linear model was training to predict price and, therefore, was evaluated, contemplating phases 4 and 5.  

The file in this repository **AirBNB Rio de Janeiro.ipynb** contains all code wrote to analyze data and answer the questions.  

## What I found <a name="results"></a>

Through entire jupyter notebook file, markdowns cells and comments discuss part of the interesting results. More explanation of findings you can read in this [blog post](nolink).   

But, in resume:
1. Yes, there's a tendency and it is related with big events on the city
2. Yes again. Nationals has a kind of different taste for the city
3. Something obvious was found: whole place is expensive.   

## Licensing, Authors, and Acknowledgements<a name="lic"></a>

Data is from Airbnb. Grateful for the availability. All information about it can be found [here](http://insideairbnb.com/about.html).   
The code can be used as you like.
