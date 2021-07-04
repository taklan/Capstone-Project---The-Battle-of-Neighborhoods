# Capstone-Project---The-Battle-of-Neighborhoods

Business Problem

Introduction

This project aims to help us in suggesting location to open a Japanese Sushi restaurant in Toronto, Canada. In other words, this project will be delivering a reference in venue for people who are interested in opening a Sushi store in Toronto, Canada.

Toronto is one of the diversified and wealthiest cities in Canada. The multi-cultural city attracts many restaurants with different cuisines. In this project, we will only focus on all areas in Toronto. We will conclude the existing Sushi restaurants compared to all other restaurants, and will use clustering to find similar areas in Toronto regarding restaurants of each borough. The preferred area shall be distant from existing restaurants. We will use data science tools to fetch the raw data, visualize it then generate a few most promising areas based on the above criteria. We will also explain the advantage and traits for the candidates, so that stakeholders can make the final decision base on the analysis.


Data

Based on the definition of our problem, factors that may impact our decision are number of existing restaurants in the neighborhood and nearby. Restaurant data in every neighborhood will be obtained using Foursquare API. We will extract the coordinates of all restaurants and their scoring, With the information about venues around a given neighborhood, we can create a dataframe where we can see what kind of venue appears around the neighborhoods in that city and their frequency of appearance. These frequencies are weighted. We can then weight the frequency of these venues in our dataframe for each neighborhood.
