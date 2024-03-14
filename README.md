# WineRatings

An anlysis of a WineEnthusiasts dataset scraped from "https://www.wineenthusiast.com/" in 2017. 
Dataset description:

wine_id	              Unique id for the wine
country	              The country that the wine is from
description	          A description of the wine 
designation	          The vineyard within the winery where the grapes that made the wine are from
points	              The number of points WineEnthusiast rated the wine on a scale of 1-100 (though they say they only post reviews for wines that score >=80)
price	                The cost of a bottle of wine
province	            The province or state that the wine is from
region_1	            The wine growing area in a province or state (ie Napa)
region_2	            Sometimes there are more specific regions specified within a wine growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank
taster_name	          The name of the taster of the wine
taste_twitter_handle	The twitter handle of the taster of the wine
title	                The title of the wine review
variety	              The type of grapes used to make the wine (ie Pinot Noir)
winery	              The winery that made the wine

The main aims of this study is to test prelimary models. The use of OLS and bagging to predict "points", and then use feature importance to uncover which variables are most predictive. Following which, textual analysis methods will be used to give a tailored recommendation based on keywords.

Future studies will involve using these methods to build a recommendation engine.
