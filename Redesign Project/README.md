## Data Visualization Redesign Project
##### Date: 2nd Nov 2017                                                                                                                                                    
##### Nikhil Kaushik | W1344280 | Fall 2017
##### Professor: Michael Schermann
##### Tableau Visual: https://public.tableau.com/profile/nikhil.kaushik#!/vizhome/Redesign_Project/Redesign_Project?publish=yes
##### Youtube Video: https://www.youtube.com/watch?v=nVczlzKEF7g&feature=youtu.be
***

### I.	Project statement (Motivation, objective, data, project plan)
I am redesigning the visualization which is present on the site: http://www.informationisbeautiful.net .
The visualization I would be redesigning is http://www.informationisbeautiful.net/visualizations/caffeine-and-calories/

**The motivation behind this redesign is:**

1. To reduce the chart junk that is data pixels over visualization pixels.
2. To remove any element of a chart that does not contribute towards the claim.
3. Try to redesign this visual with a cognitive approach.

**Project plan:**

1.	To identify the claim, to be made by the visual. 
2.	To come up with the MVP.
3.	Data Identification and extraction.
4.	Make intermediate versions.
5.	Analyze intermediate versions and find advantages and disadvantages of them.
6.	Come up with the final visual.
7.	Note down possible enhancements in the final version.
8.	Create a video to present my visualization.

**This is the screenshot of the visualization I shall be re-designing:**
![ScreenShot](https://user-images.githubusercontent.com/32223677/32389433-d208ff30-c087-11e7-815f-432a1bc6afc0.png)

### II. 	“Making-of” documentation (Details of your development process, data wrangling steps, your reasoning, detours, literature, etc.)
![ScreenShot](https://user-images.githubusercontent.com/32223677/32399166-1fd400ba-c0b1-11e7-8706-3c04da497fee.png)

### III.	Several intermediate visualization prototypes (This section encompasses detailed “Making-of” and Intermediate Visuals)

**Day 1:**

* **Activity 1:** Went through different visualizations available on the site http://www.informationisbeautiful.net . After analysis selected the visualization I would like to redesign. I selected the specific visual because I could see the way it can be improved or modified to make it more presentable with lesser chart junk.
***
**Day 2:**

* **Activity 1:** Had a discussion with the professor regarding the visualization I selected. 
Meeting output: Some insights from the professor. Ideas on how the visualization can be improved or better represented (Ideas which I cannot use now).

* **Activity 2:** Drafted project statement and created a project plan. Started working on “Making-of” document.

* **Activity 3:** Deciding on the purpose of the visual, the claim and the audience.
***

**Day 3:**
* **Activity 1:** Searching the data which could give me a relationship between the number of calories burned by playing a sport for different hours.
Relevant data found on: http://www.nutristrategy.com/caloriesburned.htm
    1.	Copying the data into an excel for MVP.
    2.	Later, I will try to do the same using beautiful soup.
    
* **Activity 2:** Joining the dataset (Fig 1.) to play with data in Tableau.
![ScreenShot](https://user-images.githubusercontent.com/32223677/32389342-a2199960-c087-11e7-82e9-c8b90afb47fb.png)
<font color=green>Fig. 1</font>
***

**Day 4:**
* **Activity 1:** Creating a test visual with the available data (Fig. 2).
![ScreenShot](https://user-images.githubusercontent.com/32223677/32389345-a2582752-c087-11e7-9702-84e29a499b6c.png)
<font color=green>Fig. 2</font>
* **Activity 2:** Changing the sports data to come up with more accurate data points. Fig. 3 below shows data created from information available for 1 hour. This was changed to a range of 15 mins to 2 hours. Fig. 4 shows how the data rows and columns were changed and data is reduced to three columns only.
![ScreenShot](https://user-images.githubusercontent.com/32223677/32389347-a272b978-c087-11e7-964d-6c50be76de48.png)
<font color=green>Fig. 3</font>
![ScreenShot](https://user-images.githubusercontent.com/32223677/32389417-cfd79776-c087-11e7-9e62-300d3d1f73bf.png)
<font color=green>Fig.4</font>
***

**Day 5:**
* **Activity 1:** Read one article on how to write a claim for your visualization.
Link: http://blog.ventivtech.com/blog/iliinskys-4-pillars-of-effective-data-visualizationfor-risk-claims-and-safety-managers

* **Activity 2:** Testing and playing with data in Tableau

*Advantage of Fig. 5:* 
1. Shows that we somewhat have a linear graph between Calories vs Time
2. Helpful for visual developer to make further progress.

*Disadvantage:* Doesn’t show useful information to the user.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389418-cff6fb34-c087-11e7-9c3f-03cff44b475f.png)

<font color=green>Fig. 5</font>	

*Advantages (Fig. 6):* This graph shows how much calorie the same sport can burn for people with different weights.

*Disadvantage:* Very basic level of visual, just information.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389419-d0131a08-c087-11e7-83f4-c62913f978d9.png)

<font color=green>Fig. 6</font>	
***

**Day 6:**

* **Activity 1(Fig. 7):** Trying to create better visual by eliminating chart junk and collecting only the relevant data which can support the claim.

*Advantages:* 
1.	This version is simpler than the above versions.
2.	Comparison can be done between two different sports.x

*Disadvantage:*
1.	Cannot support the claim. 
2.	Data does not prompt users to take any actions. 
3.	No need for two different sports on one visual.
![ScreenShot](https://user-images.githubusercontent.com/32223677/32389420-d02f12bc-c087-11e7-931f-bf465b5b2bd8.png)

***
**Day 7:**
* **Activity 1:**
Watched this very informative video: https://www.youtube.com/watch?v=boJcT-lerFQ
This video tells about 50 simple tricks to be used in Tableau. I liked the video as it is very well paced and one gets to learn easy hacks of tableau to improve.

* **Activity 2 (Fig. 8-12):**
Tried to apply what I learnt in the video mentioned in activity-1 above.
End-Product of this activity is the visual in Fig. 8.

*Advantages:*
1.	Can easily see for a coffee its caffeine content, its calorific value and the duration for which badminton needs to be played to burn the equivalent calories. 

*Disadvantage:*
1.	Too much data on one chart. 
2.	Hard to make a strong claim.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389421-d04a0928-c087-11e7-92d4-797a25fe5f77.png)

<font color=green>Fig. 8</font>	

Steps to reach the end-product shown in Fig. 8 (Fig 9-13):

Trying to add caffeine content in the visualization:
The fig. 9 shows the Time vs Calories and the Caffeine content in different Coffees.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389422-d07ecc08-c087-11e7-8f68-d4199c760d5f.png)

<font color=green>Fig. 9</font>	

Combining Caffeine and Time vs Calorie graph in one.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389423-d0b38c72-c087-11e7-92d1-4299f6c93413.png)

<font color=green>Fig. 10</font>	

This graph is an intermediate graph; this displays all the drinks and their calorific value.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389424-d122de6a-c087-11e7-8075-1a346ae19153.png)

<font color=green>Fig. 11</font>	


The Fig. 11 was modified to add Time in it.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389425-d1414616-c087-11e7-9d8f-4f7667325b84.png)

<font color=green>Fig. 12</font>	

This have Coffee, Caffeine, Calories vs Time. This version was refined to get the end-product (i.e fig. 8)

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389426-d165cf68-c087-11e7-980d-2ffd014c7724.png)

<font color=green>Fig. 13</font>
***

**Day 8:**
* **Activity 1:** Had an email conversation with the professor.

*Outcome of the meeting:*
1. The end-product (Fig. 8) is too complex, in the sense has too much information on one chart.
2. The version 1, i.e. Fig. 7 was a better and simpler version compared to Fig. 8.

*Following question raised by professor, to self-critique my work:*
1.	What is the worst thing in my visualization?
2.	What is still better in the visual I am re-designing?
3.	Does the type of sport matters much in this visual?
4.	What could be said by the relationship between Calories and Time? Like is a linear relationship? <br>

 **Activity 2:** Reverting changes to make it look like version 1.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389427-d1845a1e-c087-11e7-894a-5d19fe9e99be.png)

<font color=green>Fig. 14</font>
***

**Day 9:**
* **Activity 1:** Meeting with the professor during Lab session.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389428-d1a5f142-c087-11e7-9460-e53652450805.png)

<font color=green>Fig. 15</font>	

Shows how to make it a cognitive visual, user can put in the time he/she ran and check which drink he can pick.

* **Activity 2:** Watched: https://www.youtube.com/watch?v=opfVV1maNVw&t=311s

* **Activity 3:** A step further towards a final Visual:

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389429-d1c1bbfc-c087-11e7-9642-a467d95b7a2d.png)

<font color=green>Fig. 16</font>

Added Parameters to the above graph which can check take the user input and can tell about the action user can take.

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389431-d1e606f6-c087-11e7-8532-f979ad0c189b.png)

<font color=green>Fig. 17</font>

### IV.	Final data visualization:
From this:

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389433-d208ff30-c087-11e7-815f-432a1bc6afc0.png)

<font color=green>Fig. 18</font>

To this: 

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389434-d23e71e2-c087-11e7-98e9-7448ea49acd7.png)

<font color=green>Fig. 19</font>

![ScreenShot](https://user-images.githubusercontent.com/32223677/32389435-d2813cde-c087-11e7-86dc-087cc6c5fb04.png)
<font color=green>Fig. 20</font>

Final version:

![ScreenShot](https://user-images.githubusercontent.com/32223677/32400943-38d6033e-c0c4-11e7-90d1-34f7378dc877.png)

### V. About the final visual (Fig. 21)

**Description:** 
This graph shows a relationship between the calorie content of a drink versus the time (mins) a person needs to run (5mph) to burn the equivalent calorific value.
It is a cognitive visual in which a users can input the time they ran and then check which all drinks they can consume. This also provides them the feature of filtering based on the different coffee brands/chains. 
In this a user can also input the specific coffee name to check if it is in the consumable list or not. This will be highlighting the coffee of user's choice on the visual.

**Claim:**
To burn more calories you need to run more

**Warrant:**
Studies have shown that physical excercises helps in burning calories.

**Backing:**
https://www.health.harvard.edu/diet-and-weight-loss/calories-burned-in-30-minutes-of-leisure-and-routine-activities
The study done by Harvard Medical School shows the how much calories is burned by different excercise & sports. This also includes running at 5MPH.

**Qualifier:** 
The calories burned by running at 5MPH is calculated for a person with a weight of 180 lbs. This value is taken according to the average weight of the US population.


### V.	Road map with future features/enhancements/features
Future improvement could be to make the visual more cognitive, the following could be the steps to achieve that:
1.	Providing users to select from different weight categories to give them more accurate results.
2.	Giving users the option to choose from different sports they play rather than fixing it to just running.

***
### Additional Information
***

### VI.	Assumption(s)

1.	I have calculated the calories burnt by running for ‘x’ mins using the information provided on http://www.nutristrategy.com/caloriesburned.htm the values are taken for a person of 180 lbs. This assumption is taken based on average weight of American Men and Women. To get the average weight for men and women, I have used the information provided by the below abc news article. The calculated average is around 181 Lbs.
Article: http://abcnews.go.com/Health/average-weight-american-men-15-pounds-20-years/story?id=41100782

### VII.	All the links:
#### Links for Data:

**1. Data:** https://drive.google.com/open?id=0Bz8aQat8L1dhUG10OG9WbG9kdDQ
|| **Comments:** Sheet *“Running”* is used from this excel file, this sheet is created using the calories run after an hour of running at the speed of 5mph.

*Source:* http://www.nutristrategy.com/caloriesburned.htm


**2. Data:** https://docs.google.com/spreadsheets/d/1KYMUjrCulPtpUHwep9bVvsBvmVsDEbucdyRZ5uHCDxw/edit?hl=en_GB&hl=en_GB#gid=0
|| **Comments:** This is the data picked from http://www.informationisbeautiful.net

#### Links of YouTube videos for learning Tableau:

**1. Video:** https://www.youtube.com/watch?v=boJcT-lerFQ
|| **Comment:** Learning more about tableau, tells about 50 tips in 50 mins.

**2. Video:** https://www.youtube.com/watch?v=opfVV1maNVw&t=311s
|| **Comment:** Learning tableau, tells about how to use parameters

#### Links for articles read to improve Visualization:

**1. Article:** https://blog.hubspot.com/marketing/data-visualization-mistakes
|| **Comment:** How to improve your visuals.


**2. Article:** http://blog.ventivtech.com/blog/iliinskys-4-pillars-of-effective-data-visualizationfor-risk-claims-and-safety-managers
|| **Comment:** Noah Iliinsky’s four pillars of visualization
