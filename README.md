# Recipe ratings against nutritional values
Project on a given data for Recipe and Ratings for DSC80


## Introduction
The following report is based off of data from food.com. The main topic of interest is whether or not the different variables a food contains (calories, fats, sugar, etc.) may potentially play a part in the ratings given to each recipe by any users. This could help conclude whether how a food is appreciated by a person on food.com may also come in part as being a specific factor in a variable (such as high or low in calories, or low/high on fats). Of course there may obviously be other factors that could play importance, but currently we're interested in specifically nutrients may play an importance to ratings (if at all). We'll be working with 83,782 rows of data and our main two columns of focus will obviously be "nutrition" (contains a list of numerical values on a nutrients' level in a food based on:  [calories (#), total fat (PDV), sugar (PDV), sodium (PDV), protein (PDV), saturated fat (PDV), carbohydrates (PDV)], where pdv stands for "percentage of daily value") and "average_ratings_per_recipe" (just a numerical of specifically the average rating of all ratings that were done of the given recipe). Other potentially important columns include "name" (recipe name), "submitted" (when recipe was submitted to food.com), and "description" (description of the recipe). The names and descriptions of recipes may help explain certain nutrition variable patterns which in turn may also affect ratings of specific food types. Submission dates may seem non-important however in case of duplicate food values, it may be important to compare nutrition values and rating relationships between these food values as time of submission may play a likely factor how they may differ.
