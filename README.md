<div align = "center"><h2><u>Netflix Top 10: EDA and Analysis</u></h2></div>

<h3><u>Project Overview</u></h3>
<p>
  This project aims to perform in-depth Exploratory Data analysis on the Netflix dataset.
</p>
<h3><u>Dataset Overview and Definition</u></h3>
<p>
  <li>
  As Of: The date the ranking data was recorded.
  </li>
  <li>
  Rank: The current rank of the title in the Netflix top 10
  </li>
  <li>
  Year to Date Rank: The title's rank across all content for the year.
  </li>
  <li>
  Last Week Rank: The title's rank in the previous week's top 10.
  </li>
  <li>
  Title: The name of the movie or TV show.
  </li>
  <li>
  Type: Indicates whether the content is a *Movie* or a *TV Show*.
  </li>
  <li>
  Netflix Exclusive: Specifies whether the title is exclusive to Netflix (*Yes* or *Nan*).
  </li>
  <li>
  Netflix Release Date: The date the title was released on Netflix.
  </li>
  <li>
  Days In Top 10: The total number of days the title has appeared in the top 10 rankings.
  </li>
  <li>
  Viewership Score: It is calculated by dividing the total time spent watching a series or movie in a given week by the running time of the title.
  </li>
Dataset: https://www.kaggle.com/datasets/prasertk/netflix-daily-top-10-in-us/data
</p>
<h2>Libraries Used</h2>
<p>
  1. Pandas: For handling and analyzing data.<br>
  2. Numpy: For numerical operations.<br>
  3. Matplotlib and Seaborn: For data visualization.
</p>

<h3>Project Objectives</h3>
<p>
1. Explore and clean the dataset to remove any noise or inconsistencies.
2. Analyze the relationships between different variables in the dataset.
3. Conduct a viewership analysis to compare the performance of exclusive and non-exclusive content on the platform.
4. Identify the top-performing categories on Netflix.
</p>

<h3>Conclusions</h3>
<p>
1. An increase in viewership scores ensures that content ranks in the top 10. Overall, TV shows on Netflix are much more popular compared to other types of content.<br>
2. The trend is similar for exclusive and non-exclusive TV shows, which remain popular. Netflix does not host non-exclusive Concert/Performance or Stand-Up Comedy content on its platform (or this data is missing).<br>
3. Non-exclusive TV shows perform better than TV shows produced by Netflix.<br>
4. Netflix hosts more non-exclusive content than exclusive content on its platform.<br>
5. Among the exclusive content:<br>
  * TV Show: Ozark <br>
  * Movie: The Mitchells vs. The Machines<br>
  * Stand-Up Comedy: Dave Chappelle: The Closer<br>
  have performed exceptionally well and remained top-seeded for a long time, respectively.
</p>






