Tasker-YouTube
==============

Shell script to process all the relevant information out of the data returned by the YouTube API making it easier to mange with Tasker.

Copy and paste the content of the ShellScript file into a Tasker task under Scripts - Run Script - Command

Save the string you want to search for in a variable named %youtubequery this can be do using AutoVoce or anyother method you like

You may need to make a file called results.txt in the Tasker folder sdcard/Tasker/youtube

Next run the script and you will have some new files call authors.txt, titles.txt, content.txt and links.txt

To get the first result YouTube returned make a Task to read line 1 of each file or for the second result read line 2 and so on.
