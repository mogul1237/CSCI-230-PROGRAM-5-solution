# CSCI-230-PROGRAM-5-solution

Download Here: [CSCI 230 PROGRAM 5 solution](https://jarviscodinghub.com/assignment/csci-230-program-5-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

OBJECTIVES
• To use a Deque data structure. (user implemented)
• To implement the Iterator OOD pattern for use in the Deque.
• To use the iterator pattern to access the elements of the Deque.
• To read from a text file.
• To obtain input from a URL.
• To use JSON formatted data.
PROGRAM REQUIREMENTS
IMDB keeps information about movies, but IMDB does not have a public API. However the Open Movie Database (OMDB)
does have a public API. Using that API, you can get movie data programmatically in Java then store and manipulate that movie
data. Write a program to look up movie data (genre, plot, year, rating, runtime, plot, etc.) from the Web by specifying the just
the movie title. Do this for a list of titles, then print the movie data for all of those titles to the console. Then the program will
end.
PROGRAM SPECIFICATION
Implement the DequeAL ADT using an ArrayList. Implement the Iterator interface (java.util.Iterator) in the Deque, using
generics. Test this class well before using it next. The iterator object that a Deque object can create using it’s iterator method,
will iterate through the elements in the Deque object from the front of the Deque to the rear of the Deque.
Read the movie names from the MovieTitles.txt file. For each movie name, fetch the OMDb (Open Movie Database) data for
that movie using a REST call to https://www.omdbapi.com . The REST call returns a JSON object. Store each JSON object
returned by that REST call into the Deque object.
After the program looks up all of the movies, then iterate through the Deque object and print out each JSON object as a string
onto the console.
The JSON jar file is provided.
The MovieTitles.txt file is provided.
Abstract Data Type:
Deque implemented in an ArrayList
Deque implements Iterator
REFERENCES
None
GUI:
No GUI. Use the console for I/O.
PROGRAM DOCUMENTATION
Provide internal documentation only as required in the program documentation standard in OAKS.
Updates and clarifications to this assignment, if needed, will be done on Discussions.
PROGRAM SUBMISSION
Use the corresponding dropbox in OAKS using the same naming conventions as given in Program 1.
