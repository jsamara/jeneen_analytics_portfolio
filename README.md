# Jeneen's Analytics Portfolio
Portfolio containing projects that I have created using data visualization and analytics.

## Twitch Top 100 Streamers of November 2022
As a person who loves engaging with others on Twitch, both as a streamer and a viewer, I was very interested in the data of top streamers on Twitch. When learning how to extract and analyze data, there was no doubt in my mind that that was what I wanted to practice on.

### Collecting the Data
To start this project, I had to look for data to use. There are quite a few Twitch trackers online but not all of them were quite accurate and not all of them let you export the data. I happened to come across a tracker called SullyGnome where I was able to compare my own stream statistics to the statistics that I can find in my Twitch creator dashboard and they were quite accurate to what I was seeing on my creator dashboard so I exported the data for the top 100 streamers based on watchtime for the month of November of 2022.

### Breaking Down the Data
When I took a look into the data, there was a lot to look at, it was quite overwhelming. In order to break it down, I came up with a couple of questions to answer, how much watchtime did each of the top 100 streamers have? What were the top languages spoken within the top 100? How many of these channels label themselves as "mature"? Lastly, were there any streamers in this list that were not partnered?

In order to answer these questions I tried to come up with the most digestable ways to view the data to answer each of these questions. I felt that adding a heatmap to the list of streamers organized by watchtime was very intuitive and allows you to see all the names of the streamers in the list as well as their watchtime. This was the perfect place to also incorporate my solution to the question of whether there were any non-partnered streamers in this list. There ended up being 4 total so I just highlighted the 4 of them and included a legend that tells you that those 4 are not partnered streamers. The language question felt like it would be easy to visualized by size but in practice did not actually come across as obvious as I had hoped so I included the heat map there as well for extra emphasis. Then last but not least, to answer which streamers labeled themselves as "mature", a pie chart easily showcases this and since it is out of 100, the amount of streamers represented in either category also represents the percentage of streamers as well.

### What I Would Change:
If I had more time when creating this visualization, I would have loved to represent the top games that were played. This seems like crucial information that I could learn from as a streamer and be able to apply to my own content. Taking that even a step further, I would like to see how each game affects a streamers viewership. At the time of making this visualization I had labeled any "non-mature" streamer as "family friendly". If I ever do get the opportunity to recreate this visualization again I would like to instead label it as "non-mature" because not all streamers that do not identify as mature would call themselves family-friendly. The last change I would like to implement if I ever could is to instead broaden this project to the top 100 streamers of the past year instead of just the past month.


![Top 100 streamers in November of 2022](https://github.com/user-attachments/assets/3cd34b20-1443-4b4b-b44c-8d39a73f554a)
