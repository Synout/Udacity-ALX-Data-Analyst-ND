# PISA Student Survey Dataset Investigation
## by Mohamed E. Rahmani

## Dataset

The PISA student survey is a questionaire aimed to collect information from students nearing the end of their compulsory education. The study collected over 500 points of interest from different economies, measuring financial literacy and problem solving skills, as well as scores in reading, maths and science.

For this exploration, the  any, and see if certain conditions (wealth, computer use, etc) affect the students scores differently.

The dataset was provided in udacity recommended datasets, and can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1581581520574000),
with feature dictionary available [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000).


## Summary of Findings

In this exploratory analysis, I investigated the score features and compared them to other features of interest including gender, country, student aged started learning, student wealth and student activities out of school. The scores were normally distributed and no significant skews were observed. I found interesting trend with females scoring significantly higher than males on average reading score, while score slightly less in maths score, and no significant difference between the two genders on science scores.

I found an inversely proportional relationship between scores and students age started learning feature. This was true for all three subjects and later also proved to be true for both males and females. Females showed significantly higher mean reading scores than males across all age categories. Also, students who have lower wealth tendency (< 0) were found to start learning at a later age than those with higher wealth tendency (~ 0).

When it came to out of school (OOS) activities, the students showed better results when they played less videogames. This relationship was more significant with students who played single player games everyday or almost everyday (<=500), showing even lower scores. Students who never or hardly ever read news scored lower on all mean scores, while students who read once or twice a week scored slightly higher on all subjects. Similarly, when it came to students using social media, those who used social media once or twice a week scored higher on all three subjects.

Lastly, comparing the gender scores across the countries, China and Singapore were found to have the highest scores on all subjects for both males and females. Interestingly, Latvia and Slovakia had higher female scores than males on all three subjects on contrary to what has been observed previously in males vs females scores. On the wealth vs countries visualization, females always scored lower than males on wealth tendency across all countries.

## Key Insights for Presentation

For the presentation, my focus was on previewing scores as main features against features that showed prominent trends such as age started learning, gender and country. I used box plots to convey a quick summary of the features distribution, mainly focusing on the mean and spread. First, I preview the scores distribution to showcase that the distributions are normalized. Next, I preview the gender against the scores in three subjects to outline the performance of females in reading supercedes that of the males, while both male and females scoring closely in maths and science. Then, I preview the significance of age started learning on scores which was a very interesting finding. Finally, I show my findings that wealth tendency had a similar relation to age of student when they start learning: the higher the wealth tendency of the student the more probably they begin learning earlier.