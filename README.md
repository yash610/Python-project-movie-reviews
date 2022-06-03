# Python-project-movie-reviews
Python Project to fetch movie infromation for the top 500 most popular movies from website "metacritics.com"
Wrote a python script that collect the movie information for the top 500 movies from the website. Next, from the movie information collected, I extracted 2 pieces of information: The list of the main cast (actors/actresses), and the genre information of the movie (drama, action, thriller, etc). Built a dictionary of the movies that contain this information. 

Created three choices for the users:
1. The 1st option was ‘movie’, when the user chooses this one, then the program asks for the name of a movie and then displays the cast information and genre information accordingly.
2. The 2nd option was ‘people’, when the user chooses this one, then the program asks for the name of an actor/actress, and displays: (a) all the movies that this person has acted in, (b) a summary of the genres of these movies.
3. The 3rd option was ‘comparison’, when the user chooses this one, the program asks for the names of 2 actors/actresses, then calculate their cosine similarity based on the genre of movies they have acted in.
