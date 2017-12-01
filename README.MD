This is just a removal of the azapi script from the GNSongAnalysis project.

The script goes to Lyrics.az and extracts the lyrics from the html page. 

It saves the lyrics as a .txt document in the director it is under. Probably would be super easy to modify the script to take a param
on where to put the file. Oh well this is a work in progress use it as is.

Lyrics pages in general from Lyrics.az work as follows:
https://lyrics.az/{ARTIST}/{ALBUM}/{SONGNAME}.html

Pretty easy sometimes the album can be '-' so even if you specify the album it can find it.

The GNSongAnalysis project has a way to lookup the artist and album a song is onif you don't have the information.
This is purely if you just want a way to lookup lyrics based on your own provided information. 

Could be modified to go through the artist page and just get all the lyrics:


Planned:
https://lyrics.az/{ARTIST}/allsongs.html <- page that lists all the songs they have lyrics for. Guess you could just grab all those links
and then just parse for the lyrics that away
https://lyrics.az/{ARTIST}/allalbums.html <- lists all of the albums and songs on those albums

uhhhhh may add more features I dunno
