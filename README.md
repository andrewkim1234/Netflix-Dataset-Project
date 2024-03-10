# Netflix Dataset Project 

**The Dataset I used**

[Netflix Movies and TV Shows](https://www.kaggle.com/datasets/arnavvvvv/netflix-movies-and-tv-shows?resource=download)

The reason behind this project was for me to familiarize myself with data science topics and to apply all of the knowledge that I have gained.

### Importing Libraries
First I imported all the libraries that I would be using in this project which were pandas, NumPy and matplotlib and SciPy
<br>
<br>
### Loading, Inspecting and Cleaning the dataset
Next I loaded, inspected and cleaned the dataset using multiple functions.
I used function such as .info() and .value_counts() to load and inspect the dataset

I then checked for NaN values and got rid of all entries that included NaN values as they were not going to be useful for this project.
I also changed some of the types of the columns using the .astype() function to get the appropriate types

I also changed the names of some columns such as rating to age_rating to make them make more sense and to avoid confusion when performing tests
<br>
<br>
### Data Analysis and Visualizations
*Here is the main part of the project*

I answered multiple questions that I had on the dataset originally and made changes along the way to more clearly display my results.

The first question I had was "Which year had the most movies?"
I carried out this process by plotting my results in a bar graph because for this question I believe a bar graph was the best visual way of displaying my results. I continued by finding statistical values 
for this question such as finding the mean, median, quartiles, etc... 
I then displayed vertical lines to show where on the bar graph these values lie

I went on to answer more questions about the dataset I had such as "Which country produces the most movies/shows" and sub-questions such as "For the country with the most movies/shows, how many did they produce over the years?"
Something interesting that I found in my research was that the bar graph of the most produced country is very similar to the total years and movies graph. This was because there is a direct correlation between the two questions and the 
most produced country has a direct affect on the years and movies graph.

I started to challenge myself by finding trends within the dataset. I tried to see if there was a trend in movie duration as the yearas go by. What I found was that in the early years (1940 to 1960), movies were shorter in length but as 
we started to come closer to the current age, the results varied in a frame between 8 and 253 minutes.

Another trend I tried finding was how long on average it took for a movie to be added to Netflix once released. A problem that I found was that there were a lot of movies in the early 1900s and Netflix was not even existant at this time. 
To solve this issue, I found the earliest log that the dataset had of adding a show/movie and got all the movies and shows released after that date and compared the results. Doing this changed to average years it took a movie to be on netflix from 
6.08 years to 2.58 years.

I then carried out tests such as categorizing the data based on what entries they had in the genre column and further categorized those values by the age_rating column.

I also categorized movies based on which descriptions matched my interests, which is medieval culture, and returned a list of titles that included medieval aspects in their description.
<br>
<br>
### Hypothesis Tests
I carried out a 2 sample T-Test to see if there was a correlation between data results.
The value I got was very close to 0 which indicated that the observed result is extremely unlikely to have occured by chance alone, rejecting the null hypothesis.
