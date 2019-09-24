FLIXNET

From our three original ideas, we have decided to pursue the Flixnet database. As stated before, this database will be comprised of five entities: Movies, TV, Actors, DVDs, and Users. This service allows users to stream both movies and tv shows, so our team decided it was best to separate the two entities. In the “Movie” entity, we will include all the information regarding movies available, including title, length, year of release, genre, director(s), cast, and maturity rating. In the “TV” category, we will include all the information regarding the tv-shows available, including title, number of seasons, number of episodes, year the show began, genre, cast, and maturity rating. Our next entity is “Actors,” since users are able to search by actor or actress. The attributes would include name, movies, shows, and similar actors. In addition, the DVD entity is home to attributes such as DVD title, DVD ID number, Location ID, address, and recipient (a.k.a. where the DVD is being sent). The dynamic entity that our database will hold is “Users”. This end-user table will include subscription status, watch history, ratings, search history, total streaming time, profile name, and age restriction as its attributes. Now that we have described the entities in our database and the coinciding attributes to each, we will explain the relationship between them and whether any constraints exist. Our Users watch Movies at a many-to-many relationship. The only constraints we found necessary for the “User” table is that the subscription status cannot be inactive. Our Users watch TV shows with the same many-to-many relationship. Both TV and Movie entities would have a constraint requiring that year of release be before 2020. The two differ in the fact that the “Movies” entity will require a constraint that the length not be less than 20 minutes, and the “TV” entity will require a constraint that the number of seasons can not be less than one and number of episodes can not be less than one. The DVD entity can encompass a variety of relationships, such as many DVDs to one user or one DVD to one user (1:1 or M:M).  Lastly, Actors can appear in Movies and TV shows at a many-to-many relationship, and have no constraints. The “Actors” entity does not have constraints since Flixnet still includes actors and actresses in the database and search results, even if he or she does not have any streaming material on Flixnet. 

From this information we will also expand on the original idea and add more entities to the database to create a more versatile user experience. Additional entities will include: directors, and production company. These two entities will allow individuals to further specify their desires and will give our database more information on their tendencies, thus allowing us to give them better recommendations in the future. 

From these added entities, more relationships can be drawn as well. Production company has a one-to-one relationship with any specific TV show or Movie on the database. In addition, a specific director has a one-to-one relationship with a given TV show or Movie as well. Constraints added will include the user only being able to search one production company or director at a given time. If we allow users to search multiple entities, the search will provide information that is much too broad. 
