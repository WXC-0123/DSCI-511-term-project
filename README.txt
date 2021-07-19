A TV SHOW DATASET (The Office, US)

Release Date: March 14, 2021

----------------------------------------------------------------------

README CONTENTS
0.1 Group Information
0.2 Use
0.3 Folder Contents

1.0 Data Information
1.1 Transcripts
1.2 IMDB

2.0 Data Tables
2.1 MASTER table

3.0 Challenges
3.1 Missing episodes
3.2 Looking Ahead
----------------------------------------------------------------------
0.1 Group Information

This dataset was compiled by Emily Wang, Rohit Lakshminarayana and 
Manoj Venkatachalaiah for DSCS 511, Winter 2021. 


----------------------------------------------------------------------
0.2 Use

Because this data was made from data taken from publicly available websites,
it has all of the same free use protections as that data. In other 
words, this data can be used for research but cannot be used for 
things such as profit or identifying individuals.

Anyone can use the code without specifically citing the authors. 


----------------------------------------------------------------------
0.3 Folder Contents

final_notebook.ipynb	        Code to create the final dataset (final_dataset.csv)

final_dataset.csv		Final dataset in CSV format

raw_data			Folder containing the Raw text data, i.e., 
				transcript of each episode in json format, refer
				Section 1, Web scraping in final_notebook.ipynb

preprocessed_data		Folder containing the preprocessed text data, i.e., 
				transcript of each episode in json format, refer
				Section 2, Pre-processing in final_notebook.ipynb

----------------------------------------------------------------------

1.0  Data Information

----------------------------------------------------------------------

1.1 The Office transcripts	https://www.officequotes.net/


1.2  IMDB data			https://www.imdb.com/title/tt0386676

----------------------------------------------------------------------



2.0  Data Tables

----------------------------------------------------------------------
2.1  MASTER table

Columns:

Episodes		Episode number across all seasons, ranges from 
			0 to 184

Title			Title of the episode

Writers			Writers of the episode

Director		Director of the episode

Rating			The imdb rating of the episode 

Num_Votes		The number of votes casted

Dwight_positive_score   The positive score for the character 'Dwight
			in the episode

Dwight_neutral_score	The neutral score for the character 'Dwight
			in the episode

Dwight_negative_score	The negative score for the character 'Dwight
			in the episode

Dwight_compound_score	The compound score for the character 'Dwight
			in the episode

The above 4 sentiment scores are present for all the characters in the list:
 'Jim',
 'Pam',
 'Kevin',
 'Angela',
 'Stanley',
 'Phyllis',
 'Oscar',
 'Andy',
 'Ryan',
 'Kelly',
 'Meredith',
 'Michael',
 'Creed',
 'Toby',
 'Darryl',
 'Erin'

The next 4 columns would be 'Jim_positive_score','Jim_neutral_score', 
'Jim_negative_score', 'Jim_compound_score' and so on.
----------------------------------------------------------------------

3.0  Challenges

----------------------------------------------------------------------
3.1  Missing Episodes

The data for two episodes i.e., Season 4 Episode 8 and Season 5 
Episode 18 weren't available on the website https://www.officequotes.net/. 
We decided to omit said episodes from our research. Other resources on
the internet could be inspected and the data for said episodes could be
retrieved.



----------------------------------------------------------------------
3.2  Looking Ahead

Researchers could use our data for a machine learniing problem but trying to
predict the imdb rating of an episode using the sentiment scores of characters

They could also use our data just as an analysis research problem. 