# song-browser
A static SPA front-end for laulu.wiki's song dump

## Why does this exist?
Laulu.wiki was a song listing website, probably maintained by Aalto University's Guild of Automation and Systems Technology. It was a resource for song lyrics to student drinking songs, and got taken down in late 2020 / early 2021 for containing some extremely extremely questionable material. I got my hands on a dump of the site's song archive from before its closure, and built this as a new frontend for them. A live version can be found at ttpk.fi/songs/

As said, many of the songs on the site are **extremely** questionable. Grepping the dump for racial slurs gives several examples. I condemn this this kind of content, and chose to archive the site only because I dislike how all of it was sweeped under the rug. Therefore, the site serves as an archive of some of the more questionable parts of finnish student culture, as well as a resource for finding lyrics that only existed on laulu.wiki previously.

I will not share the song dump here, as none of it is my property. 

## What is this, in a technical sense?
song-browser is an app for navigating and displaying json files containing lyrics and metadata to songs. It is an SPA built in a single on pure JS, with the only external dependency being the font that's used. The webapp has features for searching songs and displaying their metadata. It can be very easily deployed by using your preferred web server software to serve it as a static page

## What's next?
CSS Updates and a song search by lyrics feature, and possibly a category view. I want to do more with the data than just show it, so we'll see what I come up with

