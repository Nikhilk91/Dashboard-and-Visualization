# Data Product : Corruption, how it is affecting countries? Is there a solution to it?

##### Date: 2nd Nov 2017                                                                                                                                                    
##### Professor: Michael Schermann
##### Project type: Group
##### Team Members: Embar Ravi Bhargav, Nikhil Kaushik, Neha Goushal, Parvathy, Priyanka Nirpase

##### Tableau Visual: 

Link1: 
https://public.tableau.com/profile/nikhil.kaushik#!/vizhome/Corruption_Perception_and_Reality/PerceptionandReality?publish=yes

##### Youtube Video:
***

### I. Project statement (Motivation, objective, data, project plan)

### The *start* and the *motivation*
*What is a data product?*

Understanding what all a 'Data Product' encompasses is really essential for this project.
To answer this better, this youtube video helped us a lot. Link: https://www.youtube.com/watch?v=OuRINNSDtlM

A data product has several definitions. For this project, a data product is a set of visualizations put together to present a story to the audience which has an argument supported by those visualization.

Once we understood the requirement and expectations from this project, the team discussed the **5 W's**. The 5 W's are important because it helps us in analyzing what needs to be done, who will be the audience and what do they expect from this data product. This also helped us in coming up with a timeline to be followed for the project.

A qucik look at the **5 W's** we used:

* **Why**   - Why is this *Data Product needed*?
* **Who**   - Who will be the *audience*?
* **What**  - What is the *needs and wants* of the audience?
* **Where** - Where can we get the *relevant data* from?
* **When**  - By when this data is needed? 

*Note:* It doesn't matter how awesome a product is, it will be of no value if not delivered when it is needed. Sometimes a normal product works way better than an awesome product, it totally depends on the time of entry.

### Project plan:
1. To decide on a topic on which a 'Data Product' is to be made.
2. Analyze the data and come up with a possible story.
3. To come up with a claim (for the complete data product), with the selected data.
4. Decide on different metrics to be shown in the product.
4. To create a Minimal Viable Product.
5. Combine the data sets collected from different sources to create a single data set.
5. Make intermediate versions.
6. Analyze intermediate versions and find advantages and disadvantages of them.
7. Come up with the final Data Product.
8. Note down possible enhancements in the final version.
9. Create a video to present my visualization.

### Introduction: Corruption
Corruption is a form of dishonest or unethical conduct by a person entrusted with a position of authority, often to acquire personal benefit. Corruption may include many activities including bribery and embezzlement, though it may also involve practices that are legal in many countries. Government, or 'political', corruption occurs when an office-holder or other governmental employee acts in an official capacity for personal gain.

The unethical and often illegal nature of corruption makes measurement particularly complicated. Corruption data usually comes from either direct observation (e.g. law enforcement records and audit reports), or perception surveys (e.g. public opinion surveys, or expert assessments). In this project the data taken is from both sources.
![Screenshot](https://user-images.githubusercontent.com/32223677/33506132-47355eda-d6a3-11e7-80e5-20f7f7e3aa69.jpg)
*Source: Huffington Post*

**Corruption Perception Index and its importance in our analysis**

Transparency International (TI) has published the Corruption Perceptions Index (CPI) since 1996, annually ranking countries "by their perceived levels of corruption, as determined by expert assessments and opinion surveys." The CPI generally defines corruption as "the misuse of public power for private benefit" 

**Economic implications**
"Research papers published in 2007 and 2008 examined the economic consequences of corruption perception, as defined by the CPI. The researchers found a correlation between a higher CPI and higher long-term economic growth, as well as an increase in GDP growth of 1.7% for every unit increase in a country's CPI score. Also shown was a power-law dependence linking higher CPI score to higher rates of foreign investment in a country."   *Source: Wikipedia*

In this project, we first validated how CPI relates with the reality. We compared CPI with the percentage of people who have actually bribed. This helped in proving that the CPI matches the reality. For further analysis on affects of corruption we used CPI as a metric.

We analyzed how corruption can hinder the Human Development by creating a visualization between HDI and CPI. This helped us in understanding that Human Development is lower in countries where corruption is more. 

Further analyzed how deep rooted are the effects of corruption on a country's **GDP** and how it affects the **Foreign Direct Investment**.

In this project we also added a possible solution to the problem of Corruption and that is **Education**. The message to all the countries is - 'educate your people to eradicate corruption'.

**Data Source:**

### II. 	“Making-of” documentation (Details of your development process, data wrangling steps, your reasoning, detours, literature, etc.)
![Screenshot](https://user-images.githubusercontent.com/32223677/33506542-22adedbe-d6a5-11e7-9cd1-01e4c6598da8.png)

### III.	Several intermediate visualization prototypes (This section encompasses detailed “Making-of” and Intermediate Visuals)

**Advantages:**
* This visualization is part of a Minimal Viable product and is a quick way to check with the user if this is what he/she is looking for.
* This has a very small set of countries, but provides us with some sort of trend that the countries with higher corruption has higher number of share of people who have bribed.

**Disadvantages:**
* It is hard to make any solid conclusion with the subset of data used.

![Screenshot](https://user-images.githubusercontent.com/32223677/33509171-23f37aea-d6b4-11e7-928d-76713da275db.png)

**Advantages:**
* This visualization helps to see the trend and relationship between Corruption Perception Index and Reality.
* This helped in proving that CPI matches Reality.

**Disadvantages:**
* The segregation or the grouping in this visual is done on the basis of CPI, which is redundant as it can be easily seen from the x-axis. The color coding is not needed for this repetitive categories. 

![Screenshot](https://user-images.githubusercontent.com/32223677/33367446-7abd9b0c-d4a3-11e7-98c9-c8024f7cfac3.png)

### IV.	Final Data Product:
#### Visualization 1: Perception matches Reality

This visualization is to validate how CPI relates with the reality. The comparison of CPI with the percentage of people who have actually bribed is matching. For further analysis on affects of corruption we used CPI as a metric as this can be considered a good parameter to be used as it matches with the reality. The CPI correctly shows the level of corruption in different countries.

**Advantages:** This visual enables the audience to easily see how Corruption Perception Index is realted to the reality. The visual shows a relationship between the CPI and the share of people who have bribed (in percentage)  for the year 2013. 

We have kept the visualization in the same format. All the visualizations are of type **scatter plot** as we had a large set of countries and it make sense to analyze data using a scatter plot. It is easy to see the trend corruption is following if the data is grouped on the basis of **continents**. The x-axis has been kept consistent throughout so that the user doesn't have to put in a lot of time and effort to understand each visual.

This visual presents a great insight regarding the problem of corruption. It can be easily observed that the problem of corruption is greater in the region of Asia, Africa and South America. It can be concluded from this visualization that corruption is a problem of a region. It could be possible that corruption gets spreaded to the neighbouring countries and is perceived as a normal practice in the particular region as most of the countries in the region faces this problem. It would take further analysis and is out of scope of this project, to check wether the problem of corruption has spread from one country to another over the period of time.

![Screenshot](https://user-images.githubusercontent.com/32223677/33506929-d324ca72-d6a6-11e7-915a-147e0ef239a0.png)

A further analysis has been done by the team to study the reasons behind this pattern of Corruption based on the regions.
 
*From South Korea’s presidential scandal to Malaysia’s 1MDB fund, not many Asian countries have been able to avoid the smear of corruption. While our statistic looks at the entire region, the numbers for some individual countries are staggering—and suggest corruption is deeply-rooted in everyday life.
One of the major reason for high corruption is the financial instability. “If everyone around you is poor or desperate and scrambling for the next dollar, you might think that what matters is money, not adhering to high-minded rules,” says David Hugh-Jones, an experimental economist at the University of East Anglia in Norwich, U.K. Political system like that of India is inherently corrupt and it is destroying the society’s moral fiber. Corruption is innate in such system of government because it fails to balance powers. People in high office are not innately corrupt; they become so because the system gives them 1) an elevated sense of their worth and 2) opportunity.*

*Source:  http://www.sciencemag.org/news/2016/03/corrupt-societies-encourage-lying
          http://www.jonstquah.com/documents/Corruption%20in%20Singapore%20AJPA.pdf
          https://www.forbes.com/sites/tanvigupta/2017/03/13/asias-five-most-corrupt-countries/1#ac7b0246a985*
          
*Bribery is essential for opening up economic opportunities to those who are normally cut off by the political elite’s stranglehold on the more profitable industries. The majority of Africans (58%) say that corruption has increased over the past year. Out of 28 governments, 18 are seen as completely failing to address corruption. people do not report bribery because they are scared of suffering retribution and think reporting mechanisms are ineffective. Many countries in the region have seen threats and violence against civil society, making it dangerous to operate and difficult to hold governments to account.*

*Source: https://www.transparency.org/news/feature/corruption_in_africa_75_million_people_pay_bribes*

*Corruption continues to make headlines in Latin America. Due to its geographical location, Central America, home to some of the CPI’s worst performers in the region, is a hub of drug trafficking and beset by criminal groups. It would be naïve to ignore the role of history in the region’s corruption landscape. Built on political systems skewed towards the needs of powerful oligarchies, which in many places continue to wield significant economic and political power today, corruption has permeated the region far longer than the drugs trade and would likely persist even in the face of organized crime’s demise.*

*Source: https://www.insightcrime.org/news/analysis/why-is-latin-america-so-corrupt/
         https://blogs.imf.org/2017/09/21/corruption-in-latin-america-taking-stock/*
         
#### Visualization 2: Corruption has adverse effect on human development

Human Development Index(HDI)
The World Health Organization (WHO) defines health as a state of complete physical, mental and social well-being. Along with crime and violence, corruption is seen as the most serious challenge affecting health of most of the countries. Corruption exists when people abuse the power that is entrusted to them     in order to benefit them personally. Lack of transparency, secret dealings, bribery continue to ravage our social, economic and human development. It is causing a serious loss in the economy, governance efficiency, quality of life, trust in public institutions. Leading areas in corruption are education and health care, corruption in these areas directly impairs the quality of human capital.

Corruption increases the costs of providing education and health services. It also affects the average life expectancy. Corruption has a greater influence on the income of the poorest segment of society, in other words it is reflected in the first place on the poor. The tax burden is being shifted on the poor, social programs funds aimed at reducing the income differentiation are being stolen as well.
Nowadays human capital has become, both in theory and in practice, an intense leading factor in the development, the foundation of the GDP growth, combined with innovations and new technologies.
It reduces the rate of economic growth, reduce the public expenditure on education and health care, social stratification of the population, informal employment development.

Hence, we need to see the impact of corruption on overall quality of human capital. The best approach to do this is the index method. The index method is used to bring the various elements of human capital to a single coordinate system. The most famous index that is used in the practice of evaluation of human capital is the Human Development Index (HDI).

Advantages: In this visualization, we have plotted corruption perception index against human development index. We have divided the countries into continents in order to get a better understanding and to analyze the reasons behind corruption. Blue color represents Asia, Africa and South America whereas red represents North America and Europe. We can clearly see the trend here, the Asian, African and South American countries have very low corruption perception index which indicates a very high corruption. Clearly, they have a very low human development index. For North America, Europe and Oceania, as the corruption perception index is increasing, i.e. as the corruption is decreasing, we get to see a growing trend in human development. The visualization provides the platform to study the reasons and come up with an action plan to eradicate corruption.  

### V. About the final Data Product
This Data product is a set of several visualization and covers the topic of **Corruption**, its affects and its causes.
In this project the team has created several visuals to represent how different countries are perceived on the parameter of corruption and where they actually lies in reality using the parameter 'percentage of people who actually bribed' in the country. 

Then the second visualization shows how the corruption has been affecting the Human development. This a graph showing Human Development Index and Corruption Perception Index.

### V.	Road map with future features/enhancements
* Add analysis to check why and how corruption became prevelant in certain areas of the world. Also, add predictive modelling to understand the possible future trend to see how the corruption can affect a region (will it increase or decrease).
* Analyze the possible effect of erradicating corruption from a country. Although corruption is assumed to be a problem and a factor hindering growth, but it could potentially be needed in certain countries for the purpose of business and a smooth functioning of government bodies. In these countries corruption might be playing a vital role in growth of GDP.
* Further analysis could be done to add more solution to this problem.

***
### Additional Information
***

### VII.	All the links:

Links related to visualization 1, explaining the **,'Reason behind corruption in different regions'**:

Link: http://www.sciencemag.org/news/2016/03/corrupt-societies-encourage-lying

Link: http://www.jonstquah.com/documents/Corruption%20in%20Singapore%20AJPA.pdf

Link: https://www.forbes.com/sites/tanvigupta/2017/03/13/asias-five-most-corrupt-countries/1#ac7b0246a985

Link: https://blogs.imf.org/2017/09/21/corruption-in-latin-america-taking-stock/

Link: https://www.insightcrime.org/news/analysis/why-is-latin-america-so-corrupt/
