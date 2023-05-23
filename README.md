# Olympics (1980-2020) dashboard
![image](https://github.com/mohammedwasim1/Olympics-1980-2020-dashboard/assets/121304144/0ba1bce6-0cfe-4708-9777-d997fe04bf66)

### **Dataset source**

Link to dataset: https://www.kaggle.com/datasets/nitishsharma01/olympics-124-years-datasettill-2020?select=Athletes_summer_games.csv

## **Objective**
To determine the top achieving countries, in the Winter and Summer Olympics, over a forty year period between 1980 - 2020. 

Please note: Countries in my dataset/visuals are referred to as "Areas", due to the inclusion of combined regions e.g. USSR. The term "Areas" also serves an inclusive term for participating islands and teams such as: IOC Refugee Olympic Team.

## **Justification**
By tracking the performance of the top countries in the Olympics, other nations can use the data as a benchmark for their own performance. It helps countries set realistic goals and targets for their athletes and national sports programs. By studying the successes and failures of leading nations, aspiring countries can identify areas for improvement and develop strategies to enhance their own sporting achievements.

## **Steps taken**
**Data integration**
  
  Combined the Summer and Winter dataset (CSV files) into one dataset, through Power Query.

**Data cleaning**
  
  Removed unnecessary columns which would not aid analysis.
  
  Eliminated null values from the dataset. Null values existed for some athletes ages.
  
  Excluded athletes who did not achieve any medals.
  
  Combined sports types into the main discipline e.g. Rhythmic Gymnastics would be changed to Gymnastics.
  
  Removed duplicates.
  
**Dashboard preparation**
  
  Created measures, using DAX, to perform calculations on my data to derive new insights. For instance, a Measure was created to obtain the total     amount of medals from all competitions. 
  
**Visualisations**
  
  Employed the use of appropriate chart types to represent my data accurately and intuitively. These included: Line Chart, Stacked Bar Chart and others.
  
  Enabled filters on most charts to only include top performing countries, as it made the visuals relevant to my objective.
  
## **Key insights**

  The top five achieving countries across the forty year recorded period (1980 - 2020), in descending order, are: United States, Germany, Russia,   China and Australia.

  Across all five aforementioned countries, the age which athletes obtained the most medals was at 24 years old.

  When analysing countries medal achievements by the Winter Season, countries with colder climates enter the top five positions. These include:   Canada, Finland and Sweden.

  Countries attain a greater number of medals, when the Olympic Games are hosted in their own city.
