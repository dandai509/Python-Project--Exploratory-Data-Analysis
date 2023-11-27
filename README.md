# Exploratory Data Analysis on AirBnb Amesterdam
## Business Problem
Client wishes to invest in an Airbnb property in Amsterdam. He would like to see some data about Airbnb performance in Amsterdam’s neighbourhoods that supports a clear recommendation for an investment in a specific neighborhood. 
## Data Cleaning 
The analysis will be conducted on a dataset obtained from Airbnb, containing information on listings in Amsterdam. The dataset includes details such as property characteristics, host information, pricing, reviews etc. Irrelevant and duplicate data is first removed. The correct data type is checked for analysis. The null value is filled with 0. Extreme high price value ( outlier) has also been excluded.
## Data Analysis
Top 10 hosts as shown below with the highest revenue of $1400/per night. Average Airbnb price $129/night 

![1](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/fed8c479-28a3-4e0e-8966-e27061d3ac79)

Centrum-west has the highest median price per night, Bijlmer-Oost/Bijlmer-Centrum has the lowest price per night, Ijburg-Zeeburgereiland stands out with the second highest price of $275 per night

![2](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/9e7a347f-caa7-48bd-aa50-1b43bc10c7e1)

The most reviewed property types are Chalet, Dorm, and Earthouse. The most popular type is apartments with over 6000 lists, the second most popular list is House around 711

![3](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/d6fe6584-4627-4e1d-8462-752bae5720fb)
![4](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/c78f3c27-cb76-41af-8d82-230479984898)

Centrum-west has the most listing 1,426, Oostelijk has the least listing 206. As we can see in the heat map, Centrum-west has the most heated area with color orange, also the closer it gets to city centre, the more lists it has.

![5](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/36de489b-092e-4ba4-9cd0-ef2f68e15db8)
![6](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/a98ba561-be86-435b-b9f7-7b05d5d52751)

Gaasperdam has the highest rating However only about 10 lists, Cenntrum-West has the most lists and rated number 6th, De Pijp has the second-highest rating with 2nd most lists, De Aker has the lowest number of lists and also has a very low rating.

![7](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/591c9f88-2932-42f7-b22b-bfa886df154d)

Entire home/apartment the most popular option, Private room also popular due to the price difference, Shared room is very rare.

![8](https://github.com/dandai509/Python-Project--Exploratory-Data-Analysis/assets/106848444/68f9c0f3-ee8e-4fef-b1e3-fba6b9474fca)

## Summary
Top Airbnb hosts make about $291,200/year, average Airbnb hosts make $20,124/year, and the average rent in Amsterdam is $17,880/year. Apartments are the most popular Airbnb-type property and are likely to have good reviews, whereas houses are not too popular in Amsterdam and the average ratings are lower than apartments. Centrum West is where the most listing is and tends to have the highest rental price(revenue). De Pijp has the second-highest rating on the 4th most lists. It’s the second-best choice after the central region.
Overall, Airbnb is a good option, the average Airbnb property income is more than the average rental income in Amsterdam. With only renting the property out of 156 days per year. Recommended investment to my client: An apartment locates in the Centrum west area, that has more bedrooms and rent it out as an entire apartment/house. This type of property has the highest yield and is more likely to have positive reviews.
