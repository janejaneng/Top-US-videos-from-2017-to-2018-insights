<h1>What America watched from 2017 to 2018 on Youtube?</h1>

<h2>Overview</h2>
This report presents an end-to-end analytical workflow on the top 1,000 trending YouTube videos in the United States. The goal is to derive actionable insights into content engagement patterns, category dynamics, and temporal trends. The process involves Python-based preprocessing, data cleaning, and feature engineering, followed by visualization and interaction via Tableau. The analysis is designed to inform content strategy and audience understanding.
<br />

- <b>#1 Success Factor: The Entertainment category completely dominates the top rankings, far surpassing Music and News.</b>

- <b>Key Strategy: Timing Matters. Publishing a video on a Thursday is the strongest predictor for landing a high position, likely to capitalize on weekend viewership.</b>

- <b>Engagement Drives Views: High view counts are strongly correlated with high engagement (likes and comments), showing that audience interaction is crucial for reach.</b>

- <b>Channel Consistency: Certain channels have multiple videos in the top 1000, indicating that established creators have a repeatable formula for success.</b>
<br/>
<img width="100%" height="100%" alt="image" src="https://github.com/user-attachments/assets/dd90183e-5b98-4449-b9e3-d5e87d75e356" />

<h2>Data source</h2>
https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset

<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Excel</b>
- <b>Tableau</b>

<h2>Preprocessing Steps:</h2>

<b>Raw data</b> 
<br />
<br />
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/505c7141-67df-492f-86de-1d4069140e35" />
<br />
<br />
<b>Category mapping </b>
<br />
Added a new column category_name by matching category_id with the YouTube API category JSON
<br />
<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/3e91550e-cadb-46f3-af86-c406c4a193ab" />
<br />
<br />
<b>Added</b>
-	first_trending_date: earliest trending date
-	last_trending_date: latest trending date
-	trending_date_count: total number of distinct trending days
<img width="60%" height="60%" alt="image" src="https://github.com/user-attachments/assets/db86cab8-f65d-4de2-a7e4-547bc9e17d6c" />
<br/> 
<b>Excel usage </b>
<br/>




  



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
