# Project One: Exploratory Data Analysis

# Team Name: 007

# Project Overview:
A Swedish music streaming start-up launched in 2008, Spotify began as an ethical answer to controversial file sharing sites like Napster and LimeWire by offering users a free service with advertisements or an optional monthly ad-free subscription for a nominal fee, using some of the revenue generated to compensate artists for their music.  

Today, over 50% of all music is accessed via streaming services, and Spotify is the most used streaming platform. With 456 million monthly users in 183 regions, it accounts for roughly one third of all music streaming listeners worldwide.  European users account for the largest percentage of active monthly users at 32%, but while North American listeners account for 22%, this market also has Spotify’s highest amount of active daily usage.  

Now, more than ever before, stakeholders in the music industry have immediate and detailed information on how individual artists are being received by music lovers around the globe.  Previously only trackable through direct purchases such as concert tickets and album sales, now stakeholders can see not only the popularity of these artists, but where in the world they are most popular, even down to which songs of theirs have the highest number of streams.  

Thanks to playlists and individual track selection being prioritized over comprehensive albums, single songs hold far more weight than in the past.  Record labels, in particular, have become increasingly dependent on these datasets, often reviewing Spotify statistics to make informed decisions on whom to promote, and where. In fact, labels as large as Sony use Spotify as the main indicator for chart successes.  Not only is Sony a major rightsholder on the Spotify platform, it is also a significant shareholder. 

Using Spotify API and a kaggle dataset called Spotify Charts, a resource of all daily hit charts from 2017 – 2022, we looked at the difference between global listener trends and compared them with that of the US, Spotify’s largest active daily user base.  

# Project Structure:
After reviewing many potential Spotify datasets, we chose one that holds the entire “Top 200” songs published globally between 2017 and 2021, a resource with 164,807 values.  We first reviewed and cleaned this dataset to eliminate irrelevant categories, consolidated the findings by year, and cleaned the text to increase legibility and reduce potential errors.  

The project collaborators worked as a team to ask relevant questions that could be answered by this dataset and build data visualizations that would help us communicate the most important aspects to our audience, including tables, graphs, and a Google Slides presentation to highlight key elements from our findings. 

Our project code can be found here: https://github.com/a-barbera/Project-One-Group-7

# Project Contributors:
1. Anna Barbera
2. Tanner Horton
3. Jonathan Michel
4. Victor Pang
5. Bronwyn Milne

# Objective:
Analyze music data trends and find out which markets hold the most influence over global music trends and determine if song and artist popularity in the largest market is reflective of global preferences as well.  
# Hypothesis:
<b>Hypothesis:</b> The top streaming market will have a substantial influence over global charts.

<b>Null:</b> The top streaming market will not have a substantial influence over global charts.

<b>Alternative:</b> The top streaming market will have a substantial negative influence over global charts.


# Methodology:
We chose Kaggle’s Spotify Charts “Top 200” dataset, [found here](https://www.kaggle.com/datasets/dhruvildave/spotify-charts?resource=download).  Using Pandas, we cleaned it by eliminating categories not relevant to our study, checked it for duplicates, consolidated the findings by year, and cleaned the text to increase legibility and reduce potential problems. 

We then used Pandas, Matplotlib, and statistical tests such as a chi-squared test and p-values to build different ways of looking at the information and to run tests on our hypothesis.  Using tables to sort, evaluate, and categorize our findings, we then created graphs and diagrams to help visualize these findings.  

Lastly, we developed a team presentation and a robust Google Slides folder of graphs and key elements to support our findings and facilitate audience engagement. 

# Research Questions
 <b>Question One:  Which Countries were the Most Influential on the Global Spotify Market from 2017-2021?</b>

Our analysis shows that the United States has the highest amount of total streams and accounts for 21% of total global streams between the years of 2017 - 2021, significantly higher than any other individual region represented in our dataset.  

![total streams per region](graphs2/Countries_By_Streaming.png)
![global vs US top songs comparison](graphs2/Global_vs_US_top_songs_overall.png)
![bar chart, top ten countries total streams](/graphs2/Top_Ten_Countries_by_Streaming.png)
![pie chart, Us vs. International streaming totals](/graphs2/US_Streaming_Percentage.png)

<b>Question Two: How do Rankings of Top Artists in the Top Streaming Country Compare to the Global Rankings?
? </b>

The top ten most popular artists during this time frame:

1. Post Malone
2. Ed Sheeran
3. Drake
4. Bad Bunny
5. Billie Eilish
6. J Balvin
7. Ariana Grande
8. The Weeknd
9. Juice World
10. Dua Lipa

<h3>Here, we can see what percentage US streams made of the total amount of streams for these globally most popular artists:</h3>

![Post Malone pie chart](https://github.com/VictorPang04/Spotify/blob/main/Post_Malone_Pie_Chart.png)
![Ed Sheeran pie chart](https://github.com/VictorPang04/Spotify/blob/main/Ed_Sheeran_Pie_Chart.png)
![Drake pie chart](https://github.com/VictorPang04/Spotify/blob/main/Drake_Pie_Chart.png)
![Bad Bunny pie chart](https://github.com/VictorPang04/Spotify/blob/main/Bad_Bunny_Pie_Chart.png)
![Billie Eilish pie chart](https://github.com/VictorPang04/Spotify/blob/main/Billie_Eilish_Pie_Chart.png)
![J Balvin pie chart](https://github.com/VictorPang04/Spotify/blob/main/J_Balvin_Pie_Chart.png)
![Ariana Grande pie chart](https://github.com/VictorPang04/Spotify/blob/main/Ariana_Grande_Pie_Chart.png)
![The Weeknd pie chart](https://github.com/VictorPang04/Spotify/blob/main/The_Weeknd_Pie_Chart.png)
![Juice World pie chart](https://github.com/VictorPang04/Spotify/blob/main/Juice_World_Pie_Chart.png)
![Dua Lipa pie chart](https://github.com/VictorPang04/Spotify/blob/main/Dua_Lipa_Pie_Chart.png)

<h3>Between the years of 2017 and 2021, the United States (the region with the highest amount of total streams) shared 50% of the same top ten artists as the global rankings.</h3>

GLOBAL RANKINGS:

![Global Top 10 2017](https://github.com/VictorPang04/Spotify/blob/main/Global_Top10_2017.png)
![Global Top 10 2018](https://github.com/VictorPang04/Spotify/blob/main/Global_Top10_2018.png)
![Global Top 10 2019](https://github.com/VictorPang04/Spotify/blob/main/Global_Top10_2019.png)
![Global Top 10 2020](https://github.com/VictorPang04/Spotify/blob/main/Global_Top10_2020.png)
![Global Top 10 2021](https://github.com/VictorPang04/Spotify/blob/main/Global_Top10_2021.png)

US RANKINGS:

![US Top artist rankings 2017](https://github.com/VictorPang04/Spotify/blob/main/US_Top10_2017.png)
![US Top artist rankings 2018](https://github.com/VictorPang04/Spotify/blob/main/US_Top10_2018.png)
![US Top artist rankings 2019](https://github.com/VictorPang04/Spotify/blob/main/US_Top10_2019.png)
![US Top artist rankings 2020](https://github.com/VictorPang04/Spotify/blob/main/US_Top10_2020.png)
![US Top artist rankings 2021](https://github.com/VictorPang04/Spotify/blob/main/US_Top10_2021.png)

<b>Question Three: How do Rankings of Top Songs in the Top Streaming Country Compare to the Global Rankings?</b>

<h3>From 2017-2021, the US had at least 56% of the same top songs as the global charts in the top 100. </h3>

In 2017, the US charts had 60% of the same top 100 songs as the global charts.

![venn diagram, 2017 top songs comparing US to global](graphs2/_top_songs_2017_venn.png)

In 2017, the US charts had 50% of the same top 10 songs as the global charts.

![double bar graph, 2017 top songs comparing US to global](graphs2/Global_vs_US_top_songs_2017.png)

In 2018, the US charts had 63% of the same top 100 songs as the global charts in 2018.

![venn diagram, 2018 top songs comparing US to global](graphs2/_top_songs_2018_venn.png)

In 2018, the US charts had 70% of the same top 10 songs as the global charts.

![double bar graph, 2018 top songs comparing US to global](graphs2/Global_vs_US_top_songs_2018.png)

In 2019, the US charts had 63% of the same top 100 songs as the global charts.

![venn diagram, 2019 top songs comparing US to global](graphs2/top_songs_2019_venn.png)

In 2019, the US charts had 40% of the same top 10 songs as the global charts.

![double bar graph, 2019 top songs comparing US to global](graphs2/Global_vs_US_top_songs_2019.png)

In 2020, The US charts had 57% of the same top 100 songs as the global charts.

![venn diagram, 2020 top songs comparing US to global](graphs2/top_songs_2020_venn.png)

In 2020, the US charts had 40% of the same top 10 songs as the global charts.

![double bar graph, 2020 top songs comparing US to global](graphs2/Global_vs_US_top_songs_2020.png)

In 2021, The US charts had 66% of the same top 100 songs as the global charts.

![venn diagram, 2021 top songs comparing US to global](graphs2/top_songs_2021_venn.png)

In 2021, the US charts had 70% of the same top 10 songs as the global charts.

![double bar graph, 2021 top songs comparing US to global](graphs2/Global_vs_US_top_songs_2021.png)

The US charts had 56% of the same top 100 songs as the global charts from 2017 to 2021.

![venn diagram, total top songs comparing US to global](graphs2/top_songs_overall_venn.png)

We used a chi squared test to determine if the data matched our expectations of how influential the US song charts would be, considering the market makes up 21% of Spotify streams in our timeframe. Since the chi square value of 73.84 exceeds the critical value of 3.84, we conclude that the results are statistically significant and can reject the null hypothesis. 

<b>Question Four: How does the Top Song of Each Year (2017-2021) Perform in the Top 10 Streaming Countries?</b>

In breaking down the regional contribution for each of these five songs, we are able to compare the rankings to the previously mentioned overall top ten countries list.

Ed Sheeran was not only the most streamed artist for 2017, he also charted the most streamed song for this year. As expected, the United States was the primary contributor for each of these songs. Although Sweden, home to Spotify headquarters, was not a top ten country in terms of overall streams, it ranked sixth for this song and charted in the top ten for two others.

![bar graph, Shape of You: Top Regions (2017)](graphs2/Shape_Top_Ten_Countries.png)

![venn diagram, Shape of You (2017)](graphs2/.png)

God’s Plan, a song by the Canadian artist Drake, was the most streamed release for 2018. You may notice that despite ranking seventh in terms of overall streams, Italy will not be listed as a top contributor for any of these primarily English-language songs.

![bar graph, God's Plan: Top Regions (2018)](graphs2/gods_plan_top ten_countries.png)

![venn diagram, God's Plan (2018)](graphs2/.png)

The top song for 2019 was Señorita, a duet by Sean Mendes and Camila Cabello. Even though Indonesia and the Philippines were not in the overall top ten, they were found to be a leading contributor to this song and the most popular song 2021.

![bar graph, Señorita: Top Regions (2019)](graphs2/señorita_top_countries.png)

![venn diagram, Señorita (2019)](graphs2/.png)

Perhaps more noteworthy, the Netherlands was in the top ten for each of these songs despite not making it onto the overall list. Seventy percent of the overall top ten countries were also leading contributors to the most-streamed song from 2020, Blinding Lights by The Weeknd.

![bar graph, Blinding Lights: Top Regions (2020)](graphs2/blinding_lights_2020_top_countries.png)

![venn diagram, Blinding Lights (2020)](graphs2/.png)

That total was sixty percent for the top song of 2021, drivers license by Olivia Rodrigo, and 66% when considering all five songs.

![bar graph, drivers license: Top Regions (2021)](graphs2/drivers_license_top_countries.png)

![venn diagram, drivers license (2021)](graphs2/.png)

# Conclusion:

The U.S. market makes up 21% of the total global Spotify streams from 2017 - 2021 represented by our dataset.

From 2017 - 2021, the U.S. top ten artists had a 50% overlap with global top ten artists.

From 2017 - 2021, the U.S. had at least 56% of the same songs as the global charts. 

The top song of each year had the highest number of streams from the U.S. market. 

We reject the null hypothesis, as our studies support the idea that the largest market will have the greatest influence on Spotify global trends.

# Study Limitations:

This study is limited to only songs that achieved a "Top 200" status between the years of 2017 and 2021.  
This study is also limited to the 68 unique regions available using Spotify API, when Spotify is available in a total of 183 regions worldwide.  Additionally this is still limited as Spotify is not universally accessible.
This study is only limited to data gleaned from Spotify.  Other popular music streaming services include Apple Music, Amazon Music, and YouTube Music. 

# Future Exploratory Analysis:
Future analysis could include:

1. Researching datasets from other music streaming services and combining those results with that of Spotify.

2. Further use of Spotify API to analyze what categorical features the most popular songs and artists have in common.

3. Further research into the connection between record labels and streaming services.

4. Further consideration of population sizes and the parts they play in determining popularity.

# References: 
https://www.kaggle.com/datasets/dhruvildave/spotify-charts?resource=download

https://www.kaggle.com/code/pavansanagapati/spotify-music-api-data-extraction-part1

https://www.kaggle.com/code/tanersekmen/spotify-50-song-analysis

https://seekingalpha.com/article/4516217-spotify-labels-interdependent

https://www.demandsage.com/spotify-stats/#:~:text=256%20million%20of%20Spotify's%20monthly,precise%2C%20as%20of%20September%202022.

https://www.rug.nl/news/2020/06/how-spotify-is-influencing-the-music-industry?lang=en

https://www.bbc.com/news/newsbeat-43240886

https://www.businessofapps.com/data/spotify-statistics/

https://newsroom.spotify.com/company-info/

https://www.bbc.com/news/business-60881567

https://thetowerinfo.com/listen-spotify-china/

https://worldpopulationreview.com/countries
