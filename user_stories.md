# USER Stories

1) As an admin I want to be able to remove movies and log potential duplicates , so that their is no repetitive information
2) As an admin, I want to verify the users email, so that someone is not spamming our systems.
3) As a user I want to rate movies as I like them or don’t like them, so that i can get recommendations of what other movies i might like
4) As a user, I would like to follow a friend, so i can see what movies we might enjoy watching together (or input someone’s email and then match that way)
5) “As a user of (name of our project), I want to determine which upcoming movies will do well based on the movies I’ve liked. I’m a college student so time and money are limited and I’d want to pick the best possible choice.”
6) “As a user of (name of our project), I love watching and following actor-director collaborations. (name of our project) allows me to find movies that certain actor-directors have worked together on. For example, a list of Leonardo DiCaprio and Martin Scorsese movies while also recommending other collaborations.” 
7) “I am a film producer, and (name of our project) allows me to see which movie genres are doing well. They provide the metrics by user rating, critic reception, and budget to box-office earnings. This helps me to see which projects to invest in next.”
8) “I love using (name of our project) because it helps me as a film writer with my work. I want my current projects to do well and (name of our project) predicts if a movie will do well in certain demographics. If I'm writing for the action-comedy genre, it provides which subject matter do well and which ones don’t and gives me the average screen time of movies that do well. 
9) As, Max, I want to find other people who shares the same interest so we can enjoy movies together
10) As Frances, I want to organize movies, so I can find what I have already watched and  plan on what I movies I want to watch next
11) As Celeste, I want to know the production behind a movie, so that I can find their other works
12) As Charmaine, I want to invite my friends, so we can find new  movies to watch together

# Exceptions

1) If a user rates a movie with a metric that was not interended (ex. 11/10), the user will be prompted to reenter the rating and explain the parameters (b/c it is an api endpoint.)
2) If a user wants to input a movie that looks similar to another movie title, they will be prompted to select from the following an make sure they are not just duplicating a movie.
3) When a user is verifying their email, if their otp is incorrect, they will be prompted to resend an otp or try again.
4) if a user adds more than 5 movies in the past hour, they will be told to wait an hour till they can add more movies.
5) Exception: User writes fills out the entry incorrectly
If a user attempts to fill in the wrong information in a field, then the entry will give back an error to the user and ask them to try again with the correct field. e.g. filling out the year of release instead of movie genre 
6) Exception: User tries to release a duplicate entry
If a user attempts to upload a duplicate entry, the entry will return back an error signaling them that the entry already exists and they should try another
