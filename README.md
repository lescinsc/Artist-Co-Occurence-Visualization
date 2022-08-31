# Artist-Co-Occurence-Visualization

This project focuses on music listening habits and identifying artists that have high co-occurrence on playlists with another artist from a different genre.  For example, are there certain Hip-Hop artists that fans of rock tend gravitate toward?  Additionally, popularity data is shown for artists, genres, and tracks.  There are two target audiences for this project.  First, anyone who likes music and is interested in learning about other music they might like.  Second, music industry producers.  By using this tool, producers will be able to identify artists who have spanned multiple demographic markets.  Producers may look to emulate the style of an artist who is liked by everyone in order to make their music more popular.  This data is particularly suited for visualization due to its immense nature and non-technical audience who may not otherwise have the skill to process the data.

The project was completed with a publicly available dataset from Spotify (link below).  Spotify provides a database of 1 million user created playlists from 2010 to 2017.  The database is broken into a number of useful categories including the artist, track, length and album of each entry of each playlist.  Additionally, given the size of the database, a large amount of the data was filtered.  This project focuses only on 5 genres and 50 of the top artists from the thousands in the dataset to keep the project manageable.  

The visualization is organized into two layers, the overall genre layer and the artist layer.  The overall top layer is shown above.  The key to the top layer is that it serves as a central navigation to all of the artist layers.  Navigation buttons are implemented and blended onto the color of each genre.  Clicking the button will bring the user to artist information within that genre.  The size channel is used to denote the number of artists in each category and is also approximately represents the proportion of that genre in the top 50 artists.  A tooltip is used to provide immediate information on the top artists in each genre and the number of times they appear in the data set.  The main advantage of organizing the vis in this way is that it helps with scalability.  Instead of viewing all 50 artists at once, the user can focus in on a specific genre for analysis on a smaller scale.    

The final vis yielded some interesting results.  For example, for a set of pop artists, having hip hop artists in your playlists tended to correlate more with also having Ed Shereen while having artists of any other genre in your playlist tended to correlate more with having Chris Brown.  So this raises the question of what qualities of Ed Sheeran resonate with hip hop fans.  It also might suggest that if you are a hip hop artist or an agent for a hip hop artist, a collaboration with Ed Sheeran to maximize your audience in both the hip-hop and pop crowds. 

![image](https://user-images.githubusercontent.com/78234265/187776844-101e72c4-f052-4bae-b5fd-dff6c979d574.png)

![image](https://user-images.githubusercontent.com/78234265/187776884-b524a441-2f23-465b-9a71-5029236f6b59.png)

![image](https://user-images.githubusercontent.com/78234265/187776901-3cde3db8-1fc6-45bb-9357-92d71b8a0ad6.png)

https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge
