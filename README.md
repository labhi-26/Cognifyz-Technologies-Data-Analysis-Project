# Cognifyz-Technologies-Data-Analysis-Project

##  Level 1 Task 1
### Task: Top Cuisines
### Determine the top three most common cuisines in the dataset
#### 1. **North Indian**: This cuisine appears 936 times, indicating a predominant presence in the dataset.
#### 2. **North Indian, Chinese**: This combination of cuisines is the second most common, occurring 511 times.
#### 3. **Chinese**: Standing alone as the third most common cuisine, it appears 354 times in the dataset.

### Calculate the percentage of restaurants that serve each of the top cuisines
#### 1. **North Indian**: Approximately 9.80% of the restaurants in the dataset serve this cuisine.
#### 2. **North Indian, Chinese**: Around 5.35% of the restaurants offer a combination of North Indian and Chinese cuisines.
#### 3. **Chinese**: Approximately 3.71% of the restaurants specialize in Chinese cuisine.


## Level 1 Task 2
### Task: City Analysis
### Identify the city with the highest number of restaurants in the dataset
#### The city with the highest number of restaurants in the dataset is New Delhi, boasting a total of 5473 restaurants. This indicates New Delhi's significant presence within the dataset and underscores its importance in the culinary landscape captured by the data.

### Calculate the average rating for restaurants in each city
#### **City**: This column lists the name of each city included in the dataset.
#### **Aggregate rating**: This column represents the average rating of restaurants in each city. The ratings are typically on a scale of 1 to 5, with 5 being the highest.
For example, in Abu Dhabi, the average rating for restaurants is approximately 4.3, indicating that restaurants in Abu Dhabi tend to receive high ratings. Conversely, in cities like Albany, the average rating is lower at around 3.55.
This data provides insights into the overall satisfaction level of diners across different cities, offering valuable information for individuals seeking dining experiences in these locations.

### Determine the city with the highest average rating
#### The city with the highest average rating for restaurants in the dataset is Yorkton, with an impressive aggregate rating of 4.9. This indicates that, on average, restaurants in Yorkton tend to receive exceptionally high ratings from diners, making it a noteworthy culinary destination within the dataset.


## Level 1 Task 3
### Task: Price Range Distribution
### Create a histogram or bar chart to visualize the distribution of price ranges among the restaurants
![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/9361a0b1-8988-4774-a8ae-f15f25a378f3)

### Calculate the percentage of restaurants in each price range category
#### **Price Range Category 1**: Approximately 46.53% of the restaurants fall into this category.
#### **Price Range Category 2**: About 32.59% of the restaurants are classified under this category.
#### **Price Range Category 3**: Around 14.74% of the restaurants belong to this category.
#### **Price Range Category 4**: Approximately 6.14% of the restaurants are in this category.


## Level 1 Task 4
### Task: Online Delivery
### Determine the percentage of restaurants that offer online delivery
#### The analysis reveals that approximately 25.66% of the restaurants in the dataset offer online delivery services. This statistic provides valuable insight into the prevalence of online delivery options among the restaurants, highlighting the extent to which such services are available within the dataset.

### Compare the average ratings of restaurants with and without online delivery
#### **Restaurants with Online Delivery**: These establishments have an average rating percentage of 11%. This indicates that among restaurants offering online delivery, the average rating tends to be lower.
#### **Restaurants without Online Delivery**: Conversely, restaurants that do not offer online delivery services have a higher average rating percentage of 27%. This suggests that restaurants without online delivery may receive higher ratings on average.

This comparison underscores the potential correlation between online delivery services and customer satisfaction, indicating that restaurants without online delivery services may tend to receive higher ratings from diners.


## Level 2 Task 1
### Task: Restaurant Ratings
### Analyze the distribution of aggregate ratings and determine the most common rating range
![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/e86029e2-f915-4d7c-b6f7-7112eb752e79)

#### The most common rating range among the restaurants in the dataset falls between 3.0 and 4.0, inclusive, with a total of 4388 restaurants falling within this range. This finding highlights the prevalence of ratings clustered around this range, indicating a common level of satisfaction or perception among diners towards these establishments.

### Calculate the average number of votes received by restaurants
#### The average number of votes received by restaurants in the dataset is approximately 156.91. This statistic provides insight into the level of engagement and interaction with diners, indicating the typical number of votes that restaurants receive on the platform.


## Level 2 Task 2
### Task: Cuisine Combination
### Identify the most common combinations of cuisines in the dataset
#### The table presents the most common combinations of cuisines found in the dataset along with their respective frequencies:
1. **(North Indian,)**: This single cuisine category tops the list with 936 occurrences.
2. **(Chinese, North Indian)**: The combination of Chinese and North Indian cuisines follows closely with 616 occurrences.
3. **(Mughlai, North Indian)**: Another popular combination is Mughlai and North Indian cuisines, appearing 394 times.
4. **(Fast Food,)**: Fast Food as a standalone cuisine is also prevalent, with 354 occurrences.
5. **(Chinese,)**: Similarly, Chinese cuisine alone also appears 354 times in the dataset.

These findings shed light on the culinary preferences and trends within the dataset, showcasing the most common combinations of cuisines offered by restaurants.

### Determine if certain cuisine combinationstend to have higher ratings
#### The provided data showcases the average ratings for various cuisine combinations found in the dataset. Here's how to interpret it:

- **Cuisines**: This column lists the combination of cuisines.
- **Count**: This represents the frequency or count of the respective cuisine combination within the dataset.
- **Rating**: This column displays the average rating associated with each cuisine combination.

Observations:
- Cuisine combinations such as ('Desserts', 'Ice Cream') and ('Chinese', 'Continental', 'North Indian') tend to have higher average ratings, with ratings of 2.90 and 3.03 respectively.
- On the other hand, cuisine combinations like ('Mughlai',) and ('North Indian',) have comparatively lower average ratings, with ratings of 1.56 and 1.67 respectively.

These findings suggest that certain cuisine combinations may indeed correlate with higher or lower average ratings, indicating potential preferences or perceptions among diners towards these combinations.


## Level 2 Task 3
### Task: Geographic Analysis
### Plot the locations of restaurants on a map using longitude and latitude coordinates
![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/1981a4ea-39c8-4a24-98e1-0bf2ea9d7c01)

### Identify any patterns or clusters of restaurants in specific areas
![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/5ccc2ef7-ac31-4868-b466-d703d74d1ecf)

#### Based on the cluster counts and the characteristics of Cluster 0, it seems to be the largest cluster with 8316 restaurants. Here are some observations and potential insights:

1. **Cluster Size**: Cluster 0 dominates the dataset, containing a significant portion of the restaurants.

2. **Location**: The restaurants in Cluster 0 are predominantly located in Makati City and Mandaluyong City in the Philippines.

3. **Cuisine Variety**: The cuisine types vary widely within this cluster, ranging from French and Japanese to Seafood and Filipino.

4. **Rating and Popularity**: Restaurants in this cluster generally have high ratings, as indicated by the 'Rating text' column, with many being rated as 'Excellent' or 'Very Good'. They also have a considerable number of votes.

5. **Delivery Options**: Most restaurants in this cluster do not offer online delivery or ordering options.

6. **Price Range**: The price range for restaurants in this cluster varies, but there seems to be a concentration around the mid to high range.

Based on this information, Cluster 0 appears to represent a diverse range of restaurants located in urban areas of Makati City and Mandaluyong City in the Philippines, offering a variety of cuisines with generally high ratings and moderate to high price ranges. This cluster may cater to both local residents and tourists visiting these urban centers.

![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/c51905e4-c55c-465d-8f07-baa3ee825727)

#### Based on the characteristics of Cluster 1, here are some observations and potential insights:

1. **Cluster Size**: Cluster 1 contains 438 restaurants, making it smaller than Cluster 0 but still significant.

2. **Location**: The restaurants in Cluster 1 are located in Albany, Georgia, USA.

3. **Cuisine Variety**: The cuisine types in this cluster include BBQ, American, Mexican, and Coffee and Tea, among others.

4. **Rating and Popularity**: Restaurants in this cluster have average ratings, mostly falling in the 'Average' category. The number of votes for each restaurant varies.

5. **Delivery Options**: Similar to Cluster 0, most restaurants in this cluster do not offer online delivery or ordering options.

6. **Price Range**: The price range for restaurants in this cluster varies, but there seems to be a concentration around the lower end.

Based on this information, Cluster 1 represents a variety of restaurants located in Albany, Georgia, USA, offering different cuisines with average ratings and mostly catering to local dining preferences. Let's visualize the geographical distribution of restaurants in Cluster 1:
![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/1ece8dbb-0be8-40fd-9a85-9c1c8a8cfbc4)


#### Based on the characteristics of Cluster 2, here are some observations and potential insights:

1. **Cluster Size**: Cluster 2 contains 617 restaurants.

2. **Location**: The restaurants in Cluster 2 are located in Brasília, the capital city of Brazil.

3. **Cuisine Variety**: The cuisine types in this cluster include Fast Food, French, Cafe, Bakery, Brazilian, and Pizza, among others.

4. **Rating and Popularity**: Restaurants in this cluster have varying ratings, with some being rated as 'Good' and others as 'Average'. The number of votes for each restaurant is relatively low.

5. **Delivery Options**: Similar to the previous clusters, most restaurants in this cluster do not offer online delivery or ordering options.

6. **Price Range**: The price range for restaurants in this cluster varies, but there seems to be a concentration around the mid-range.

Based on this information, Cluster 2 represents a variety of restaurants located in Brasília, Brazil, offering different cuisines with varying ratings and price ranges. Let's visualize the geographical distribution of restaurants in Cluster 2:
![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/8b6d9f94-fbac-47ab-b24f-457cc7dea4b3)

#### Based on the characteristics of Cluster 3, here are some observations and potential insights:

1. **Cluster Size**: Cluster 3 contains 64 restaurants.

2. **Location**: The restaurants in Cluster 3 are located in various cities across Australia, including Armidale, Balingup, Beechworth, Dicky Beach, and East Ballina.

3. **Cuisine Variety**: The cuisine types in this cluster include Bar Food, Steak, Modern Australian, Pizza, Cafe, and Coffee and Tea, among others.

4. **Rating and Popularity**: Restaurants in this cluster have varying ratings, with some being rated as 'Excellent', 'Very Good', or 'Good', while others are rated as 'Average'. The number of votes for each restaurant varies.

5. **Delivery Options**: Similar to the previous clusters, most restaurants in this cluster do not offer online delivery or ordering options.

6. **Price Range**: The price range for restaurants in this cluster varies, with a concentration around the mid-range.

Based on this information, Cluster 3 represents a variety of restaurants located across different cities in Australia, offering different cuisines with varying ratings and price ranges. Let's visualize the geographical distribution of restaurants in Cluster 3:
![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/20cf1a1d-95e4-4c72-ac03-21f464453917)

#### Based on the characteristics of Cluster 4, here are some observations and potential insights:

1. **Cluster Size**: Cluster 4 contains 116 restaurants.

2. **Location**: The restaurants in Cluster 4 are located in various cities, including New Delhi and Noida in India, and Birmingham in Europe.

3. **Cuisine Variety**: The cuisine types in this cluster include Chinese, Lucknowi, North Indian, South Indian, Italian, Continental, Fast Food, Cafe, British, and Steak, among others.

4. **Rating and Popularity**: Restaurants in this cluster have varying ratings, ranging from 'Not rated' to 'Very Good'. The number of votes for each restaurant varies as well.

5. **Delivery Options**: Some restaurants in this cluster offer online delivery, while others do not.

6. **Price Range**: The price range for restaurants in this cluster varies, with a concentration around the mid-range.

Based on this information, Cluster 4 represents a variety of restaurants located across different cities in India and Europe, offering different cuisines with varying ratings and price ranges. Let's visualize the geographical distribution of restaurants in Cluster 4:

![image](https://github.com/labhi-26/Cognifyz-Technologies-Data-Analysis-Project/assets/137891712/de587fd2-1f69-422b-8c5f-d625ec8c0e16)


## Level 2
### Task 4
### Task: Restaurant Chains
### Identify if there are any restaurant chains present in the dataset
















