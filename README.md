# NCAA-Quaterback-Analysis
## Background
For many colleges is place for students to gain and education, experience, and expand their worldview. It provides a place for individuals to grow. However, the other side of that is the world of sports. Many looks at college sports programs as the defining characteristics. It is a place to showcase skill and power and establish a name for yourself and school in front of the nation. Such competitions put pressures on university to be the best, and those that succeed are rewarding with millions of dollars. The biggest influence on a college besides their academics is their football program. It can make or break a school. Top performing football programs have been seen to bring of upwards of 31$ million dollars in revenue, and for some it can account for 70% of the school’s profits. To help put this in perspective, the subsequent 35 sports schools may offer is equal to what a single football program will bring in. This places a burden to recruit and improve players to be the best in the nation to improve programs. The more successful a team is, the more money they can bring in. One of the single most important roles in a team is the quarterback. They are the playmakers on the field and can decide how to team success will go. With this, we can investigate what makes a successful quarterback and how schools and player can prioritize skills to improve the overall team.

![Imgur](https://i.imgur.com/nbgPMXS.png)

## Objective 
The goal of this project is to analyze what various quarterback statistics affect their ratings. Various machine learning models will be sampled to find an optimized model that best fits the data to a regression model. The findings can the be used to infer what are the best and east areas a quarterback and or college can focus on to improve the players skill. Ideally with improved skill the overall team performance will go up leading to a chain reaction to aid in the improvement of a football program and revenue

## DATA
The data used was gathered from four different ESPN sources
1. College Football Total Quarterback Rating(QBR) – (2004-2019) Season Leaders
    * Rates the quarterback on playmaking skill and gives an overall score 0-100
2. College Football Power Index (2005-2019)
    * Ranks and rates teams offensive defensive and special teams’ efficiency 
3. College Football Player Passing Stats (2004-2019)
    * An overview of top performing players and their seasons passing stats
4. College Football Player Rushing Stats  (2004-2019)
    * An overview of top performing players and their seasons passing stats
    
![Imgur](https://i.imgur.com/C2yAze4.png)

## Models
To analyze a quarterback's skill 9 different regression models were analyzed and compared against each other to find which had the best fit of the data. R-sq, root mean squared error (RMSE) and mean absolute error (MAE) were used to measure each model’s performance. Due to the nature of the data the models were naturally correlated with each other, so all models had relatively high performance. 
* _Neural Network was abbreviated “NN” followed by optimization algorithm used._

![Imgur](https://i.imgur.com/lslgxtM.png)

The finalized model used was a multivariate linear regression algorithm. Creating the final model outliers’ non-significant figures were dropped. There was a small reduction of the fit of the model with at while giving a reduction in error. With low variance between out train and test RMSE it can be assumed that the data is well fitted.

![Imgur](https://i.imgur.com/i6S8iMw.png)

## Data Analysis
### Influence of age in conference 

* Top Tier = BIG12, ACC, PAC-12, BIG10, SEC
* Bottom Tier = MAC, Mountain-West, Independent, C-USA, American, Sun-Belt

The difference in age ranges if most notably seen with lower tier conferences. They show a change in QBR rating of 30 from 18-year-olds to 24 year-olds while top tier conference only have change of 15. This puts and emphasis for smaller conferences to have their quarterbacks redshirt and sit out a year to give them more time to age and grow in skill. The top tier conference can benefit from the same but will see smaller affects. This is likely due to recruiting. More established and successful football programs have a stronger influence on recruiting new high performing athletes. Their new athletes typically will have a higher starting QBR rating than smaller schools’ new recruits. It puts more emphasis on smaller schools to develop their quarterback’s skill to reach a similar QBR rating of top tier conferences.

![Imgur](https://i.imgur.com/c2KYqaR.png)
