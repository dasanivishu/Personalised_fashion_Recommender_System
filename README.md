# Project Name: Personalised Fashion Recommendation System

A Deep learning based streamlit web app which can recommened you various types of fasion products with respect to your choices.

Recommender systems are the systems that are designed to recommend things to the user based on many different factors. These systems predict the most likely product that the users are most likely to purchase and are of interest to. Companies like Netflix, Amazon, etc. use recommender systems to help their users to identify the correct product or movies for them. 

The recommender system deals with a large volume of information present by filtering the most important information based on the data provided by a user and other factors that take care of the user’s preference and interest. It finds out the match between user and item and imputes the similarities between users and items for recommendation. 

Both the users and the services provided have benefited from these kinds of systems. The quality and decision-making process has also improved through these kinds of systems.






This is a methods of identifying similar products check various aspects on pictures, including: shape, colors, edges, features (including the lighting of the photo) and euclidean distance of vectors in a 'n' dim features space.

# Dataset has been used:

 - [High Resolution Dataset link](https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset)
 - [Low Resolution Dataset link](https://www.kaggle.com/paramaggarwal/fashion-product-images-small)





# STEPS to run this project:



## STEP 01: 
Clone the repository or copy the code


## STEP 02: 
Create an environment


```bash
conda create -n fasion python=3.7 -y
```

## STEP 03: 
Install the requirements


```bash
pip install -r requirements.txt
```

## STEP 04: 
Download the data from the link and keep it in your project directory. Make sure all the images should be in just one folder called data, like that



## STEP 05: 
Just execute this command & wait, it may take some time


```bash
python run.py
```

## STEP 06: 
Now to start the webapp run the following command


```bash
streamlit run --server.fileWatcherType none app.py
```

yes!! Now you can start predicting 🙂

# Authors:
```bash
Author: Vishal Dasani,Bikash Dutta

Email: vishaldasani1999@gmail.com
```
