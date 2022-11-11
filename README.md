
# Game recommender
The goal of this project is to create a model that can recommend video games to the user. if a user gives a game name as an input. the model will recommend some other similar type of games to the user. because it is a classification problem, I have used k-nearest neighbors (KNN) algorithm. KNN will group/cluster similar types of data point close to each other based on their features. for data preparation I have used NumPy, pandas, matplotlib and seaborn. for standardizing the data and modeling I have used sklearn library.



# About the data

the dataset used in this project is from <a href = "https://www.imdb.com/?ref_=nv_home">IMDB </a>. you can download the updated dataset from <a href = "https://www.imdb.com/interfaces/">here </a>


for this project I have downloaded two datasets from IMDb and merged them together. the datasets contain.

<ul><li>tconst (string) - alphanumeric unique identifier of the title</li><li>titleType (string) – the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)</li><li>primaryTitle (string) – the more popular title / the title used by the filmmakers on promotional materials at the point of release</li><li>originalTitle (string) - original title, in the original language</li><li>isAdult (boolean) - 0: non-adult title; 1: adult title</li><li>startYear (YYYY) – represents the release year of a title. In the case of TV Series, it is the series start year </li><li>endYear (YYYY) – TV Series end year. ‘\N’ for all other title types</li><li>runtimeMinutes – primary runtime of the title, in minutes</li><li>genres (string array) – includes up to three genres associated with the title</li>
<li>averageRating – weighted average of all the individual user ratings</li><li>numVotes - number of votes the title has received</li></ul>

<br>
