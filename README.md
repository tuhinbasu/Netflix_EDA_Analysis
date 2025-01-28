<div align = "center"><h2><u>Netflix Top 10: EDA and Analysis</u></h2>
 
  ![image](https://github.com/user-attachments/assets/57a9cd7b-29b2-4f5a-b557-784ed55d625c)

</div>
<h3>Project Overview</h3>
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
  3. Matplotlib and Seaborn: For data visualization.<br>
</p>

<h3>Project Objectives</h3>
<p>
1. Explore and clean the dataset to remove any noise or inconsistencies.
2. Analyze the relationships between different variables in the dataset.
3. Conduct a viewership analysis to compare the performance of exclusive and non-exclusive content on the platform.
4. Identify the top-performing categories on Netflix.
</p>

<h3>Key Analysis Performed</h3>
<p>
  1. Correlation Analysis<br>
  - Analyzed the correlation among the specified columns: [Current_Rank, YTD, Last_Week_Rank, Days_Seeded, and Viewership_Score].<br>
 
 ![image](https://github.com/user-attachments/assets/abe26b62-95a6-4b72-a38d-3f0e0722608a)

  2. Average Viewership Analysis<br>
  - Analyzed the overall average viewership score compared to title types.<br>
  
  ![image](https://github.com/user-attachments/assets/580c4475-71e0-410a-848f-cc91189f9b94)

  - Analyzed the average viewership score for exclusive content produced by Netflix.<br>
 
  ![image](https://github.com/user-attachments/assets/16345d73-961c-4b95-905e-7f923755a997)

  - Analyze the average viewership score for non-exclusive content on Netflix.<br>
 
  ![image](https://github.com/user-attachments/assets/8cc59802-03fb-4a49-a7e8-c6ab1f8101cd)

  3. Analyzed the exclusive and non-exclusive content<br>
  
  ![image](https://github.com/user-attachments/assets/fd678dcd-3611-452c-843c-48037ece7284)

  ![image](https://github.com/user-attachments/assets/3c672151-3678-4a3f-8e88-918e55787380)

  4. Performed analysis on exclusive content<br>
  - Count all the exclusive content in each type.<br>
  - Identify the top 10 TV shows produced by Netflix.<br>
  - Identify the top 10 movies produced by Netflix.<br>
  - Identify the top 10 stand-up comedy shows produced by Netflix.<br>
</p>

<h3>Conclusions</h3>
<p>
1. An increase in viewership scores ensures that content ranks in the top 10.<br>
2. Overall, TV shows on Netflix are much more popular compared to other types of content.<br>
3. The trend is similar for exclusive and non-exclusive TV shows, which remain popular. Netflix does not host non-exclusive Concerts/Performance or Stand-Up Comedy content on its platform (or this data is missing).<br>
4. Non-exclusive TV shows perform better than TV shows produced by Netflix.<br>
5. Netflix hosts more non-exclusive content than exclusive content on its platform.<br>
6. Among the exclusive content:<br>
  * TV Show: Ozark <br>
  * Movie: The Mitchells vs. The Machines<br>
  * Stand-Up Comedy: Dave Chappelle: The Closer<br>
  have performed exceptionally well and remained top-seeded for a long time, respectively.
</p>






