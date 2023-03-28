- Text & Code:

```

Although it was named after comma-separated values, the CSV module can manage parsed files regardless of the field delimiter - be it tabs, vertical bars, or just about anything else.

```


```

import csv

with open('nba_games_november2018_visitor_wins.txt', newline = '') as games:
    	game_reader = csv.reader(games, delimiter='\t')
    	for game in game_reader:
    		print(game)


```

primary reference for reading data from txt file [Importing Data from Tab Delimited Files with Python](https://www.pluralsight.com/guides/importing-data-from-tab-delimited-files-with-python)