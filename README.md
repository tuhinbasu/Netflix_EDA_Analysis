<!DOCTYPE html>
<html lang="en">
<body style="font-family: Arial, sans-serif; line-height: 1.6;">

  <div align="center">
    <h1 style="font-size: 2.5em; text-decoration: underline;">Netflix Top 10: EDA and Analysis</h1>
    <img src="https://github.com/user-attachments/assets/57a9cd7b-29b2-4f5a-b557-784ed55d625c" alt="Netflix Analysis Banner" style="width: 80%; max-width: 600px; margin-top: 20px;">
  </div>

  <hr style="margin: 20px 0;">

  <section>
    <h2 style="color: #2c3e50;">Project Overview</h2>
    <p>
      This project aims to conduct an in-depth Exploratory Data Analysis (EDA) on Netflix's daily Top 10 dataset to uncover trends, insights, and patterns that shape viewership on the platform.
    </p>
  </section>

  <hr style="margin: 20px 0;">

  <section>
    <h2 style="color: #2c3e50;">Dataset Overview and Definitions</h2>
    <p>This dataset contains detailed information about the top 10 Netflix titles, including movies, TV shows, and other content types. Below are the key attributes:</p>
    <ul>
      <li><strong>As Of:</strong> The date when the ranking data was recorded.</li>
      <li><strong>Rank:</strong> The title's current rank in the Netflix Top 10.</li>
      <li><strong>Year to Date Rank:</strong> The rank of the title among all Netflix content for the year.</li>
      <li><strong>Last Week Rank:</strong> The title's rank in the previous week's Top 10.</li>
      <li><strong>Title:</strong> The name of the movie or TV show.</li>
      <li><strong>Type:</strong> Specifies whether the content is a <em>Movie</em> or a <em>TV Show</em>.</li>
      <li><strong>Netflix Exclusive:</strong> Indicates whether the title is exclusive to Netflix (<em>Yes</em> or <em>NaN</em>).</li>
      <li><strong>Netflix Release Date:</strong> The date the title was released on Netflix.</li>
      <li><strong>Days in Top 10:</strong> The total number of days the title has appeared in the Top 10 rankings.</li>
      <li><strong>Viewership Score:</strong> Calculated by dividing the total time spent watching a title in a given week by its running time.</li>
    </ul>
    <p><strong>Dataset Source:</strong> <a href="https://www.kaggle.com/datasets/prasertk/netflix-daily-top-10-in-us/data" target="_blank">Netflix Daily Top 10 in US</a></p>
  </section>

  <hr style="margin: 20px 0;">

  <section>
    <h2 style="color: #2c3e50;">Libraries Used</h2>
    <ul>
      <li><strong>Pandas:</strong> For handling and analyzing data.</li>
      <li><strong>NumPy:</strong> For numerical operations.</li>
      <li><strong>Matplotlib and Seaborn:</strong> For data visualization.</li>
    </ul>
  </section>

  <hr style="margin: 20px 0;">

  <section>
    <h2 style="color: #2c3e50;">Project Objectives</h2>
    <ol>
      <li>Explore and clean the dataset to remove any noise or inconsistencies.</li>
      <li>Analyze the relationships between different variables in the dataset.</li>
      <li>Conduct a viewership analysis to compare the performance of exclusive and non-exclusive content on the platform.</li>
      <li>Identify the top-performing categories on Netflix.</li>
    </ol>
  </section>

  <hr style="margin: 20px 0;">

  <section>
    <h2 style="color: #2c3e50;">Key Analyses Performed</h2>
    <ul>
      <li>
        <strong>Correlation Analysis:</strong> Examined the correlation among variables such as <em>Current Rank</em>, <em>YTD Rank</em>, <em>Last Week Rank</em>, <em>Days in Top 10</em>, and <em>Viewership Score</em>.
        <div align="center">
          <img src="https://github.com/user-attachments/assets/abe26b62-95a6-4b72-a38d-3f0e0722608a" alt="Correlation Analysis" style="width: 80%; max-width: 600px; margin: 10px 0;">
        </div>
      </li>
      <li>
        <strong>Viewership Analysis:</strong> Analyzed average viewership scores:
        <ul>
          <li>Overall scores by title type.</li>
          <li>Exclusive content vs. non-exclusive content.</li>
        </ul>
        <div align="center">
          <img src="https://github.com/user-attachments/assets/580c4475-71e0-410a-848f-cc91189f9b94" alt="Viewership Analysis" style="width: 80%; max-width: 600px; margin: 10px 0;">
        </div>
      </li>
      <li>
        <strong>Exclusive Content Analysis:</strong> Identified the top-performing Netflix-exclusive content across categories:
        <ul>
          <li>Top 10 TV shows</li>
          <li>Top 10 movies</li>
          <li>Top 10 stand-up comedy shows</li>
        </ul>
      </li>
    </ul>
  </section>

  <hr style="margin: 20px 0;">

  <section>
    <h2 style="color: #2c3e50;">Conclusions</h2>
    <ol>
      <li>Higher viewership scores increase the likelihood of content ranking in the Top 10.</li>
      <li>TV shows consistently outperform other types of content on Netflix.</li>
      <li>Both exclusive and non-exclusive TV shows remain highly popular.</li>
      <li>Non-exclusive TV shows tend to perform better than Netflix-produced TV shows.</li>
      <li>Netflix hosts more non-exclusive content compared to exclusive content.</li>
      <li>Among exclusive content, the following titles performed exceptionally well:
        <ul>
          <li><strong>TV Show:</strong> Ozark</li>
          <li><strong>Movie:</strong> The Mitchells vs. The Machines</li>
          <li><strong>Stand-Up Comedy:</strong> Dave Chappelle: The Closer</li>
        </ul>
      </li>
    </ol>
  </section>

</body>
</html>
