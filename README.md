There are unix commands like awk and sed that make text processing such an interesting exercise.
In the beginning of my career I work with unix tool lex and yacc
In recent years I had to use unix on and off
Refreshing for my job search this time, I fell in love with awk and sed which I hadn't had the opportunity to use at work so far.

Another fascination for me in the pase few years has been to analyse patterns in wordle answers.
One such exercise using python:
https://github.com/lalitha2019/wordle-analysis

Putting together my 2 new found interests, I started working on a project using unix now.
Objective:
https://wordfinder.yourdictionary.com/wordle/answers/ - This website maintains an archive of wordle solutions and updates daily.
. Get the content from there in html format and extract the solutions to a text file.
. Process the text file and organize the data in suitable form for analysis
. Perform Analysis


Files:
unix code
- get-wordle-answers-from-web 

script used by awk command in the above unix code
- script2.txt

intermediate / output files
- t.html - html file from the url
- finally.html - intermediate output - the answers part of html file
- cleanAnswers.txt - intermediate output - the answers part above, formatted into neat key, value pairs (and a few additional lines which are easy to clean up, if needed)
  This file can be used as input for data anlalysis using python or any other preferred language / tool
  Details in this text file can be read as data structures like arrays or tables and used for analysis and visualization
- wordleData.txt - data from the above key, value pairs (has a few additional lines that may or may not be helpful in further processing / analysis)
  The above file is good enough for using as input for data analysis, but this was just an extension to my exercise in text processing
