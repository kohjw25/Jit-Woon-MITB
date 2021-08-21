# Popularity of Airbnb Listings in Singapore
Social Analytics project - Investigating the popularity of Airbnb Listings in Singapore
1) Exploratory Data Analysis: 4 room types of listings (Private Room, Entire home, hotel room and shared room), Word cloud visualization of common words used in listing names
2) Conducted Sentiment Analysis using VADER and NLTK on reviews dataset to determine polarity of reviews
3) Network influence using centrality scores (degree, betweenness and pagerank centrality) to identify top 10 listings in each category and further investigate their attributes, compare with common attributes for each room category

Conclusion: 
- Popular listings tend to have favourable attributes (proximity to central locations, near the MRT, hosts with a personal touch)
- Some of the popular listings identified have unique attributes (eg. "lure of falling asleep under the stars")
- To improve on their offerings, Airbnb owners can emphasize on the uniqueness of their listing to capture the attention of users by appealing to emotions.

Points to consider:
- Can also identify the bottom 10 listings based on polarity scores from sentiment analysis, to investigate why listings have poor reviews
- Other than price, amenities and listing names, there are other factors which may affect popularity, such as neighbourhood group and whether the host is a superhost. A classification algorithm/multiple regression can be done to determine their relative importance to one another.
