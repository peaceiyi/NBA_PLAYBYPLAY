# NBA Play by Play 

Here's my python script to parse through play by play NBA data and turn it into a csv file!

##### Necessary Modules
- Requests

##### Access JSON Link
- load play by play page for the game you want
- right click and hit inspect element (or press option+command+i)
- go to the network tab (there should be another tab under network called XHR -- make sure its highlighted)
- look for a link that says "playbyplayv2?..." (if there's nothing there reload the page)
- save the request URL that pops up to the right once you click the "playbyplayv2" link
- example - https://stats.nba.com/stats/playbyplayv2?EndPeriod=10&EndRange=55800&GameID=0041700104&RangeType=2&Season=2017-18&SeasonType=Playoffs&StartPeriod=1&StartRange=0

##### Running the Script
- open terminal
- use cd to find the directory the script in is
- type "python3 playbyplay.py" to run
- paste link you saved
- type file name
- have fun

##### THINGS TO FIX
- let the user input the URL of the play by play page! (idk if this is possible)

