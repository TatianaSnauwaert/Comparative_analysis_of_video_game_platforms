# Comparative_analysis_of_video_game_platforms
## Integrated project after the 1st module from Practicum by Yandex

### Goal
Prepare a report for the online store Ice to identify patterns that determine whether a game will succeed or not. This will allow us to spot potential big winners and plan advertising campaigns.

### This project's repo includes the following files:

- The project's final jupyter notebook (Integrated project 1_final.ipynb);
- A pdf format of the notebook (Integrated project 1_final.pdf)
- Input data (games.csv)
- Project description from Practicum (IG1_description.pdf)

### This project includes the following steps:

1. Descriptive statistics;
2. Data Preprocessing: missing values replacement, data type change, duplicates check, total sales calculation;
3. EDA: distribution analysis of top platforms, user profile creation per region;
4. Statistical hypotheses testing.

### Based on the analysis we have come to the following conclusions:

1. **Top platforms study gave the following results**:
- There are 5 platforms that stand out in terms of total sales in all regions: 'PS4', 'PS3', 'X360', '3DS', 'XOne';
- We decided to take data for the past 5 years to build a prognosis for 2017 in order to make sure the chosen platforms are still popular in 2017;
- There are no significant differences in sales for the top 5 platforms. All 5 distributions have long tails of large positive numbers;
- There is almost no linear connection between sales and user reviews and quite a weak linear connection between game sales and professional reviews for the 'PS4' platform;
- We didn't find any significant differences between the amounts of total sales each platform made for the same games.
- Action games are the most profitable as well as popular. It looks like, generally, more active games (action, shooter, sports) have high sales, while more calm and intellectual games (puzzle, strategy) have low sales.

2. We analyzed **top 5 platforms and genres in 3 regions (NA, EU, JP)** and found that in each region different platforms prevail - most games are sold on 'X360' platform in the NA region, on 'PS4' platform in the EU region and on '3DS' in the JP region.

Action games are the most popular in both the NA and EU regions, while role-playing games prevail in Japan (with action games on the second place).

The NA and EU regions are similar: shooter games come second in both regions, the difference in percentage is not very big - around 7-8%. Third are sport games. 'PS3' released the most sports games in the last 5 years and it explains why it occupies the third and second places in the NA and EU regions, respectively.

The JP region differs: more than 30% of games are role-playing. 'PS3' and '3DS' platforms release the most role-playing games, that's why they are the biggest in Japan in terms of sales.

The rest of genres that we summarized under "others" takes up a little less than a quarter of all sales, so we can conclude that different players prefer different kinds of games, so the variety of genres is appreciated by users.

We also checked whether the ESRB ratings affect sales in individual regions and concluded that the tendencies in the NA and EU regions are the same, while Japan shows again a different picture. In the NA and EU regions most games are sold with rating "M" (Mature 18+), while in Japan - with rating "E" (Everyone).
This gives us an idea of the age distribution of the target audience in the gaming industry per region.

Summarizing this section, **a typical user in each region has the following characteristics**:

- NA region: a Mature person (18+) playing mostly action games on the "X360" platform;
- EU region: a Mature person (18+) playing mostly action games on the "PS4" platform;
- JP region: a person of any age playing mostly role-playing games on the "3DS" platform.

3. Next step was **statistical hypotheses testing**. We tested two hypotheses:

- Average user ratings of the 'Xbox One' and 'PC' platforms are the same.
- Average user ratings for the Action and Sports genres are the same.

In the first case we have retained the null - the average user ratings of the 'Xbox One' and 'PC' platforms are indeed the same. In the second case we have rejected the null - the average user ratings of the Action and Sports games are not the same.

### The logbook of this project can be found [here](https://docs.google.com/spreadsheets/d/1SrGdReexaSEomJGS6yR6cRwJtHA_XqpprnLaE7B6Ayg/edit#gid=1704507796) (IP1 tab).
Total time spent on the project: 15.6 hours with a daily average of 3.53 hours working for 4 days.
