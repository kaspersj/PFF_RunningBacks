# PFF_RunningBacks
Analyzing running back data from the NCAA and NFL, with the goal to glean insights from the statistical trends.

** Note: As per Pro Football Focus Term's and Conditions, we are not permitted to share a private data set. **

## NCAA to NFL Running Back Analysis: Does College Elusiveness Predict Pro Success?
On and off since February 2025, @couragekwonye and I have been deep-diving into NCAA and NFL running back data. Our goal? To unearth statistical trends and gain insights, specifically focusing on whether a college running back's elusive rating impacts their drafting value and NFL performance. In simpler terms, we wanted to see if being elusive in college translates to higher NFL run grades.
 
## The Data Journey: A Marathon, Not a Sprint
As with many data science projects, our analysis took several interesting turns, with the bulk of our effort dedicated to creating a usable dataset. This involved:
•	Combining NCAA and NFL data: We meticulously merged and joined datasets year by year, going all the way back to 2014. This was a tedious process, especially since many talented college players didn't meet draft eligibility requirements.
•	Data Cleaning and Filtering: We removed duplicate values and refined the data to ensure each player's information reflected their best performance year (based on their highest 'grades_run' value), dropping other seasons.

## Unpacking the Insights: K-Means Clustering 
In today's AI-driven world, descriptive understandings of insights are crucial to make sense of the "noise." Our analysis employed several techniques to extract meaningful patterns:  \n
•	K-Means Clustering: The scatter plots in the accompanying PDF visualize the results of K-means clustering on running back performance metrics. Each point represents a player-season, colored by its assigned cluster. You'll notice most charts show 3 clusters. This number was determined using the Elbow Method line charts, which illustrate "inertia" (within-cluster sum of squares) for different cluster counts. We looked for the "elbow" point where adding more clusters didn't significantly reduce inertia.

## Continuous Learning and Future Endeavors
While the insights from this analysis might not revolutionize the field, the true value lies in the process of continuous learning and personal development. This project perfectly blended my interests in data science, research, and sports. As I continue my job search, I'm committed to further developing my skills as a researcher.

## I'd love to hear your thoughts! Do you have any other interesting research project ideas, know of any job opportunities, or would you be interested in collaborating on future projects? Feel free to reach out!

