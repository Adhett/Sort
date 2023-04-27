"In class, the professor introduced the use of BaseX to query different things in an XML file of books, 
such as finding authors with the name X, filtering books by date, etc. 
He asked us to perform a search that would order the authors alphabetically.
We tried various methods, but most of them involved creating variables and sorting them by X.
While researching, I discovered that there was a function called 'sort'.
I looked at many forums and threads to figure out how to use 'sort' in a search.
Some of the methods were overly complicated for such a simple problem, so I decided to use 'sort' in a different way.
I used 'sort' by concatenating 'distinct-values(libros/libro/autor) = sort()', but for some reason, it didn't work. 
So, I added a comparator 'distinct-values(libros/libro/autor) = >sort()', and voila! It worked."


