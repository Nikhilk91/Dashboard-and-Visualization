## Lab Session - 7
#### Objectives: Redesign result of lab session 3.
#### Date: 04-Nov-2017
#### Tableau Link: https://public.tableau.com/profile/nikhil.kaushik#!/vizhome/Book_12_0/Dashboard_1?publish=yes

#### Steps
* Critique your visualization
* Develop a roadmap for improvement
* Improve your visualization
* Explain how you have improved your visualization


#### Purpose of Lab-3:
Develop persuasive visualization for data breaches and its impact using stock prices as a parameter. This required data wrangling to read JSON symbols from Yahoo Query Tool to extract and clean stock price data of various companies from Yahoo Finance. 

**Technology Used:** Python in Jupyter notebook to extract stock data from Yahoo Finance. This extraction is done from JSON file and then based on Ticker values the stock prices for 40+ companies were picked.
In this Lab, we made use of Fuzzy Wuzzy giving more insights of how we can do string matchin using it.

***
#### Road map with future features/enhancements/features (For Lab-3):
***
**1.**  The visual created in Lab-3 shows data for one particular company. This particular company could be an outlier, in turn can prove this visual a 'deceptive' one.

**Improvement:** Add more details in the caption regarding why the particular company is chosen.

**2.** The references are missing in the visual. Refrences add more value to the product.

**Improvement:** Add references in the caption.


**3.** The analysis is based just on the basis of stock prices and this could again be not a sufficient parameter to make the claim.

**Improvement:** More parameters could be addded to this visualization. For instance, security breach could affect the market valuation of the company. So, market valuation could be used as one of the parameters too.

**4.** The visual doesn't provide any data about how the overall market reacted in that particular year.

**Improvement:** Adding information about how the overall market was reacting in that particular year also gives some sense of support to the claim. There could be a case when the drop in the stock price is due to the overall market crash and not because of the security breach. If the market reaction is mentioned in the visual, the user doesn't have to seacrch for this information in case of doubt.

**5** The reaction of security breach could affect different companies differently. The companies which are more data centric such as banks would react highly to breaches.

**Improvement:** The analysis could be based on different segments of companies. Segmenting data based on the category could help in resolving the issue. Financial firms may react to breaches completely differently when compared to IT companies.
