What if we had a website that recommends songs based on our musical tastes? The music recommender is the main product of this site. The idea is that when a person visits the site, they can play a song they like and, in return, receive a playlist of recommended songs.

However, recommending songs solely based on the musical genre does not allow for a satisfactory recommendation. In light of this, the idea is to use various variables that pertain to the characteristics of a particular song, beyond the genre.

We have access to a database with various songs and their characteristics. From this database, our music recommender was built following several steps:

Explore the database, that is, understand what information it contains and how it functions;

Create clusters, that is, different groupings that relate songs to other characteristics beyond the genre;

Use the clusters to build the recommender and generate a new playlist for our website.

Since we have a large database, and considering performance, we will use PySpark, which is ideal for these cases.

# Music_recommender
