Anime Data Analysis Project

⸻

Project Overview

  This project explores and analyzes a combined anime ratings dataset, focusing on user behavior, genre preferences, and the popularity of various anime types and titles. The analysis is broken down into 5 clear steps, each saved as a separate Python file, to demonstrate core data analysis skills using pandas, matplotlib, and seaborn.

⸻

Dataset

  We use dataset "Anime Recommendations Database" by CooperUnion
  
  	rating.csv
   	anime.csv

⸻

File Descriptions


	animerec1.py

User Ratings Distribution

• Loads the merged dataset
	 
• Visualizes the distribution of scores (rating_x) using countplot
	 
• Shows how often users rate anime from 1 to 10

Goal:
Understand overall user rating behavior (most users give 8–10 stars).

	animerec2.py

Average Rating by Genre
  
• Cleans rows with missing genre or rating_y
 
• Splits multi-genre strings into individual genre entries using explode()
   
• Calculates average rating_y per genre
   
• Visualizes top genres by average rating

Goal:
Find out which genres have the highest average ratings individually.

	animerec3.py

User Behavior: Optimistic Users

• Groups dataset by user_id
 
• Filters users who only give high ratings (9 or 10)
 
• Outputs list of such users

Goal:
Detect users who consistently rate anime very highly — useful for understanding rating bias or designing personalized systems.

	animerec4.py

Top Anime Types

• Analyzes the most common anime type (e.g., TV, Movie, OVA)

Goal:
Identify which anime types dominate the platform.

	animerec5.py

Popular Titles

• Finds and visualizes the top 10 anime titles by number of members

Goal:
Identify which titles are the most widely watched.
