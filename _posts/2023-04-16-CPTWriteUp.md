---
toc: true
layout: post
description: "Write up for College Board."
categories: [markdown, week-29]
title: "CPT Write Up"
---

3. a. 

- i. The program is meant to allow users to write about their opinions on their favorite movies by letting users post movies and their thoughts on them

- ii. The video shows a message is displayed informing the user they have not added any movies. Afterwards, a user is shown inputting various movie titles along with commentary. After clicking the text to "Show Movies", the movies are displayed below in the order they were added.

- iii. The inputs of adding a movie title and commentary create the content that is displayed as the output in the posts once the "Show Movies" text is clicked.

3. b. 

- i. 
![]({{ site.baseurl }}/images/codebi-1.PNG)
![]({{ site.baseurl }}/images/codebi.PNG)

- ii. 
![]({{ site.baseurl }}/images/codebii.PNG)

- iii. The name of the list being used to store each movie object is movies.

- iv. Inside of the list 'movies' objects called 'movie' are stored. Each one contains an id as well as the title of the movie and the user's commentary.

- v. The list helps manage complexity in the program by creating a database from which each movie and its commentary can be accessed and displayed. This program could also be written as a dictionary with the movie title being the key and the commentary being the value, however by writing it as a list with multiple objects stored inside it allows for multiple comments to be added for the same movie, as this way we don't have to worry about having multiple keys with the same value in one dictionary.

3. c. 

- i. 
![]({{ site.baseurl }}/images/codeci.PNG)

- ii. 
![]({{ site.baseurl }}/images/codecii.PNG)

- iii. The procedure contributes to the functionality of the program by generating a message to tell the user if they have added any movies and displaying each movie along with commentary if they have.

- iv. The procedure first uses selection to check to see if the user has added a movie to the 'movies' list. If they have not, a message is displayed notifying them of this. If they have, the program then displays a message telling them their movies are displayed below. Along with this message, the program first sequentially defines a variable, i, to count the number of movies in the 'movies' list. then it uses a for loop to iterate through each movie in the list and accesses the text of its movie title and commentary to be displayed in a newly created div element. This process is repeated until a div element has been created for each movie in the 'movies' list.

3. d. 

- i. 

1. First Call: The first call is the 'Show Movies' text being clicked when there are no movies in the 'movies' list.

2. Second Call: The second call is the 'Show Movies' text being clicked when there are movies in the 'movies' list.

- ii. 

1. Conditions Tested by the First Call: The first call checks if there are any movies in the 'movies' list.

2. Conditions Tested by the Second Call: The second call checks if there are any movies in the 'movies' list. If there are one or more movies the text for the movie title and commentary of each movie are also checked.

- iii.

1. Results of the First Call: the first call results in no movies being found in the movies list, thefore a message is displayed telling the user there are no movies to display.

2. Results of the Second Call: the first call results in the list of movies being iterated through to display each movie along with the commentary for it.




