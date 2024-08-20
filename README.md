# Welcome to regeX-Games 
## What is the game?
Debuted at .conf23
The regeX-Games are an exciting game where players get to put their regular expressions skills to the test! 
The alias for this game is BORE (Boss of Regular Expressions).
How is it hosted?
It is hosted on a single Splunk Cloud Platform Search Head that everybody can access. 
Players are assigned the user role while hosts are assigned the admin role.

## What you need to play:
A computer with internet access
A good attitude

## What are the rules?
Answer questions in any order
Do not cheat! (no looking behind the curtain, no using ChatGPT, etc., no using work by others without their consent, etc. - this is not an exhaustive list - plus we have ways of checking for cheats) Use YOUR answers.
Have fun!
How do I play?
Login to Splunk! 
Update your name
Click on the username in the upper navigation bar > Account Settings
Update Full Name and Save

Navigate to the BORE: Play dashboard
Choose which level (Beginner, Intermediate, Advanced) and question to work on. 
A link is provided to the dataset in regex101 to test out solutions.
Use the “Regular Expression” input to match sections of strings from the given dataset. The “match” capturing group is a default input and the capturing group should be used in all questions. 

If using regex101, add the number of steps provided in the upper-right hand corner into the “# of steps” input. This is on the honor system, but is verifiable through submitted answers! Steps will default to 1000000.

There is an opportunity to score more points. If successful in matching the known results as well as hidden strings, bonus points will be awarded.
Having trouble? Ask for a hint with the “Hint?” input. Asking for a hint will deduct 5 points from your score!
Correct submissions will populate a “CORRECT” output in the dashboard. If the hidden bonus criteria is met along with the known criteria, “CORRECT + BONUS” will be displayed. Incorrect submissions will result in “INCORRECT”. 

## Tips
Use regex101
Look for leading or following spaces that might lead to incorrect matches
Escape double quotes (e.g. \”), backslashes (e.g. \/), and brackets (e.g. \] or \[)
In regex101, substitutions use $1 while Splunk uses \1
How is it scored?
Questions will be scored with the following points:
Beginner questions have a base score of 50
Intermediate questions have a base score of 100
Advanced questions have a base score of 150
Each question will have a bonus multiplier of 50% if the regular expression matches hidden criteria
Beginner questions will have a bonus of 25
Intermediate questions will have a bonus of 50
Advanced questions have a base score of 75
Incorrect answers will not be penalized
Using the hint option will deduct 5 points
Entering the steps found in the upper-righthand corner in regex101 will impact score
The lower the amount of steps, the higher the point value
The number of characters in your regular expression will impact score
The less characters used, the higher the point value
The first users to answer questions will get bonus points:
First: 10 points
Second: 9 points
…
Tenth: 1 point

