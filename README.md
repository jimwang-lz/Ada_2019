# Title: Ada_2019_project


 
# Abstract
*What's the motivation behind your project? A 150 word description of the project idea, goals, dataset used. What story you would like to tell and why?*

If you ask some elderlies, they may say a little dirt never killed anybody. However, with the degradation of the environment recently, food safety, especially when eating outside, has become a more and more serious issue all around the world. Therefore, inspections are performed by the staff from the Chicago Department of Public Health’s Food Protection Program using a standardized procedure.  According to the data displayed on the Kaggle, we get the result with different performances of establishments. Our objects are to review the overall sanitary conditions using the inspection results and analyze the effectiveness of the inspection methods in order to evaluate the reliability of the overall results. Possibly, we could understand the food hygiene condition all over the world through this small state. 
 
# Research Questions

*A list of research questions you would like to address during the project.*

1. The sanitary conditions of food establishments:
- How is the overall sanitary condition of Chicago’s dining establishments? How is it distributed in this city?
- What are the most common violations? What do the violation comments imply?
- How does food hygiene condition correlate to facility type: Does a certain type of restaurant have a more serious problem on food security?
- How does food hygiene condition correlate to time (i.e. months, seasons, and years): Does hot weather mean bad food sanitation? Does food safety get improved over time?
- How does food hygiene condition correlate to districts: Do some districts always face a bigger food safety problem? Where is the safest or worst place to eat?
- Do restaurants have Clustering affection: Do geographically closed restaurants have a similar violation?
- If the hygiene condition and violation type are highly correlated to the districts, try to use some other additional geo-related dataset to find out why.(bonus)
 
2. The effectiveness of the inspection methods:
- Is different inspections’ frequency consistent: Do different kinds of inspections have similar distribution both in the time domain and geographic domain?
- How does inspection’s result correlate to the inspection’s type and frequency: for example, do advanced noticed inspection have a better result?
- Does the inspection frequency satisfy the state’s requirements?
- How do different inspection methods influence the inspection results?
- Try to develop a way to measure the establishments’ hygiene performance. (bonus)
3. Case study:
Analyze the situation of some most popular food establishments and give some suggestions to nowadays young people in restaurant selection.
 
# Dataset
*List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.*
We will use the dataset from the City of Chicago Open Data which is derived from inspections of restaurants and other food establishments in Chicago from January 1st, 2010 to the present. This dataset includes abundant information on the inspections’ results. However, to achieve our goal, we may extend our data with the population demographics and the district’s division from the official website of Chicago.


 
# A list of internal milestones up until project milestone 2
*Add here a sketch of your planning for the next project milestone.*
- Acquire, clean and merge the data
- Preliminary descriptive analysis and plot individual establishment based on location and time
- Group different establishments based on the locations and analyze the relationships of results
- Group different establishments based on time and analyze the overall results
- Group different establishments based on inspection methods and analyze the effectiveness of inspection
- If we could, we want to find out some other factors which will affect the establishments’ sanitary conditions 
- Start thinking about the data story

 
# Questions for TAs
*Add here some questions you have for us, in general or project-specific.*
- Is it okay for us to use some other dataset as an additional dataset to mine more stories from the existed dataset? For example, to use other geo-related data that can be found from the city of Chicago open data to analyze the potential relationship between food violation type and the main population of the particular area?
- What’re the differences between milestone 2 and the report submission? Do we need to finish all the analysis working before milestone 2?
- When are we getting the feedback for the milestone 1?
- How much memory RAM would this require? Would it be feasible to conduct the analysis without resorting to cloud computing?
 

