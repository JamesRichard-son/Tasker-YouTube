Tasker-YouTube
==============

DISCLAIMER: THIS HAS NOT BEEN FULLY TESTED

Shell script to process all the relevant information out of the data returned by the YouTube API making it easier to mange with Tasker.

place the script in a Tasker task under Scripts - Run Script - Command

Save the string you want to search for in a variable named %youtubequery

You may need to make a file called results.txt in the Tasker folder sdcard/Tasker/youtube

Next run the script and you will have some new files call authors.txt, titles.txt, content.txt and links.txt

To get the first result YouTube returned make a Tasker task read line on the first line of each file or for the second result line 2 and so on.
