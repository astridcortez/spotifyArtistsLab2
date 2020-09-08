# spotifyArtistsLab2

The program titled SpotifyArtistLab2, is meant to take in a csv file that contains a list of records:
song rank, song title, name of artist, streams, and the url, and find out which artists appear on this list and how many times each artist is in the chart.
In order to do that, the program takes in the csv file, splits the information into an array with 5 rows and 200 collumns and prints it out which is one method.
Then it takes this array, and now that the csv file is in "array form," it looks at all the artists and begins to count how many times each artist appears in
top 200 chart. This is another array. As this is going on, it puts this information, the artists and the number of times they show up in the top 200, in another array and returns that array.
Then there is another method that is exactly like this one except it returns the logical length of this array to be used in another method.
Once we have the array with the song artists, the number of times they show up, and the logical length of this array, another method takes this, organizes it alphabetically and puts it into another array. 
For the end result we have an alphabetized array by artist name that shows the number of times each rtist shows up in the top 200 chart of that week.
