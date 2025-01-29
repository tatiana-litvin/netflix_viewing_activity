# Netflix Viewing Activity

# Project Background

Netflix is an American video streaming company with a SaaS model, active since 2007. With over 30 million users, it is the most subscribed video-on-demand platform. This project analyzes a specific user's viewing activity using data collected by the platform and provides an overview of their activity since subscribing to the service.

Insights and recommendations are provided on the following key areas:

- **Content Watched:** Shows which movies and TV shows were most frequently watched during the previous year and over time.
- **Viewing Activity Over Time:** Illustrates variations in watching activity across different years, months, or days of the week.



The python script used to report and explore trends as well as create the visualizations can be found here [link](https://github.com/tatiana-litvin/netflix_viewing_activity/blob/main/netflix-analysis.ipynb).



# Data Structure & Initial Checks

The table used for the analysis contains information on viewing activity for all users since the account was created. The most important columns include: Start Time, Duration, Title, and Bookmark.

The grain of the table is each interactive viewing event from the user on the platform, meaning it includes moments when a movie was paused and later resumed, trailers watched, and other clips viewed via autoplay.



# Executive Summary

### Overview of Findings

The content analysis revealed that the most-watched TV shows of 2024 were: "Gossip Girl," "Queer Eye," and "BoJack Horseman." As for movies, a complete analysis was conducted across all years of active subscription to identify the most-watched films. The top movies were: "The Holiday," "Pride and Prejudice," and "Love Actually."

The viewing activity over time analysis showed significant fluctuations across months and years. The year with the highest total watch time across all months was 2020, likely due to the pandemic.

![hours_watched](https://github.com/user-attachments/assets/5dd19d66-04dc-40dd-b9d6-8c9b0dc00ccc)


# Insights Deep Dive

### Trends over time:

* **The month in 2024 with highest number of watch hours was December, while the one with the least was April.** This pattern reflects personal behavior, as December is a holiday month, offering more free time for watching movies and TV shows. Conversely, April saw a decrease in activity, likely due to a heavy workload related to Master’s thesis writing, which left less time for recreational streaming.
  
* **The number of TV Shows watched was more than 4 times the number of movies watched.** Understanding the user’s content preference can help the platform deliver more tailored recommendations that align with their interests.
  
* **The day of the week with the most watch time during 2024 was Tuesday.** Identifying the most active days allows the platform to recommend longer content on popular days and suggest shorter titles for busier days.
  
* **The use of the platform, as measured by total hours of watch time, has been decreasing over time, with a slight increase frmo 2023 to 2024.** The most significant jumps in watch time occurred between 2019 and 2020, with an increase of 48%, likely due to the pandemic, and from 2021 to 2022, which saw the largest decrease of -59%, possibly tied to the start of a Master's program. Since 2020, watch time has steadily declined, with a small uptick in 2024 (a 1.75% increase), likely influenced by the December holiday boost.




# Recommendations:

Based on the insights and findings above, here are some recommendations: 

* December showed the highest watch time in 2024, likely due to the holiday season. **Consider promoting holiday-themed content or exclusive releases during the last quarter to leverage this increased watch time.**
* TV shows were watched significantly more than movies. **Highlight more movies that fit into a shorter style, and continue promoting tv shows in highlight ares of the platform.**

  
