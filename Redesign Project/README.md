## Data Visualization Redesign Project
##### Date: 2nd Nov 2017                                                                                                                                                    
##### Nikhil Kaushik | W1344280 | Fall 2017
##### Professor: Michael Schermann
##### Tableau Visual: https://public.tableau.com/profile/nikhil.kaushik#!/vizhome/Redesign_Project/Redesign_Project?publish=yes
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

### II. 	“Making-of” documentation (Details of your development process, data wrangling steps, your reasoning, detours, literature, etc.)

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
**Day 3: **
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
**Day 5: **
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

** Day 6: **

* **Activity 1(Fig. 7):** Trying to create better visual by eliminating chart junk and collecting only the relevant data which can support the claim.

*Advantages:* 
1.	This version is simpler than the above versions.
2.	Comparison can be done between two different sports.x

*Disadvantage:*
1.	Cannot support the claim. 
2.	Data does not prompt users to take any actions. 
3.	No need for two different sports on one visual.
![ScreenShot](https://user-images.githubusercontent.com/32223677/32389420-d02f12bc-c087-11e7-931f-bf465b5b2bd8.png)
