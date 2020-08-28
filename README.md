# NBA-2pt-vs-3pt
NBA Three Points Evolution Trend analysis based on multiple factors (independent variables) with linear-regression model using Python (Pandas and Matplotlib).

We wanted to look at the evolutionary trend within the NBA, specifically how the use of the 3pt. has changed through the years since it's been implemented. Players used to attempt to score closer to the basketball rim In order to ensure higher accuracy, but it’s been confirmed by sports analysts that players are attempting and making more 3pt. through the years and the league has been in talks of creating a 4pt perimeter on the basketball court. 

Our Questions

1.	How have team attempts and percentages changed throughout the decades?
2.	What is the relationship between the 3pt. and a championship caliber team?
3.	How have player roles changed through the years due to the 3pt?

Three Point Change in Decades.

We used the NBA final data from 1980 to 2018, showcasing 4 decades. Using both the NBA final winner and the runner up we can see with the graphs below that there as significant increases in 3pt attempts and percentages.

![3 pts Attempts Through Decades](https://user-images.githubusercontent.com/59676112/91520474-6b9dec80-e8c3-11ea-8c77-b1352a470445.png)

![3 pts Percentage Through Decades](https://user-images.githubusercontent.com/59676112/91520502-75bfeb00-e8c3-11ea-8d56-a37e0a65c268.png)

The below linear regression model displays the year by year 3pt attempt. Here we can see that there is a steady increase in usage during the Finals. We can conclude here that the 3pt. has become more popular, but is there any relationship between the 3pt and a championship? 

![attemptforeachyear](https://user-images.githubusercontent.com/59676112/91517188-3b525000-e8bb-11ea-83f3-d5763000bece.png)

The Graph below displays 3pt made throughout the years for the Finals along with their Percentages. Blue bars representing championship team and orange the runner up team. What we see here is that championship teams have both higher percentages and made shots. We were able to conclude here that the 3pt is one important factor that determines the championship however, there are a few years such as 1997, 2011 and 2016 where the runner up team had high stats for both, so we can’t say that it’s the sole factor.

![3pt Made Through Years For Finals](https://user-images.githubusercontent.com/59676112/91520779-1e6e4a80-e8c4-11ea-98aa-d3e58ee89ba7.png)

![3pt Percentage Through Years For Finals](https://user-images.githubusercontent.com/59676112/91520816-38a82880-e8c4-11ea-9696-fad84d90af4e.png)

How has the skill evolved as seasoned veterans’ game VS. a young player?

Here we decided to investigate veteran players who came into the league from 2005 – 2019 and younger players who came into the league in 2012. What we see is that the veterans are peaking at over 40% and the younger at 30%. Also, there looks to be a decline within the use of the 2pt, given the rise in 3pt. 

![Veterans   Younger 3 vs 2](https://user-images.githubusercontent.com/59676112/91521309-5cb83980-e8c5-11ea-801c-307b3a16674b.PNG)

Further, the veterans are averaging and attempting more than the younger group. Both graphs display a dip, but looking closer at the data, after 2018 we see that there is a significant decline in the amount of minutes played in the latter part of the veterans year. Veterans losing more than 6 mins on the court by 2019. The younger players only lost about a minute. We concluded that veterans are focusing more attention than the younger players are, and this could be closely related to the longevity of their careers.

![Veterans   Younger attempt ratio](https://user-images.githubusercontent.com/59676112/91521160-0d720900-e8c5-11ea-8d82-c52c1cc5acbe.PNG)

![Veterans   Younger made ratio](https://user-images.githubusercontent.com/59676112/91521174-1236bd00-e8c5-11ea-85bc-db1a6d752f90.PNG)

Centers and Power Forwards – How have these roles changed?

We also wanted to look at the roles of certain players – specifically players who in the 80s and 90s would always stay in the paint and never step foot around the perimeter. Below we can see that after 2015 there is a sharp incline with Centers and PF attempts and made shots (over 4000 attempts and a little over half of those are made) – 35% from the 3 which is a good average for an effective shooter.

![3pt Made   Attempt for PF](https://user-images.githubusercontent.com/59676112/91520862-5c6b6e80-e8c4-11ea-8845-e9aa54a675ff.png)

![3pt Made   Attempt For C](https://user-images.githubusercontent.com/59676112/91520888-74db8900-e8c4-11ea-9532-43daa59f7dbd.png)

This is important because the role for the Center and PF has changed and it allows them to be an offense threat elsewhere which helps give coaches a more versatile playbook. 

