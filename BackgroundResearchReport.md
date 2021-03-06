## Background Research Report

_3. The kind of decisions, interventions, or actions that analysis results could support
(e.g., management actions, advocacy for policy changes, etc.)_

Based on the provided datasets, we divided the projects into two segments. Similarly, we would have two different analysis and their results. The two datasets are ‘Avian Monitoring Dataset’ and ‘Bald Eagle Monitoring’. These two datasets are not related directly and they are collected in different ways at OWC. Data is collected using a Sheet of paper with all attributes. The observer can be a volunteer or citizen science intern.
____
#### Avian Monitoring :
There are almost 60 species in this dataset with their time, weather at the time of encounter.

**Data Entry:** Each observer goes around OWC and stops at designated spots for 15 minutes and collects data on each trail. There are four trails around OWC: Blue, Red, Purple, Green. Observer records the Bird species code and heard or seen on a sheet of paper manually. Then, they make manual entry into a Excel sheet. They collect attributes such as Date, Temperature, wind, Time, # of species, Heard/Seen, etc. 

**Data Cleaning and Analysis:** There are few issues with the way data is stored and collected. There are few missing values and no standard codes used. This is due to manual entry or improper data management. So, this is a challenge to start our research questions. 

**Research questions and Results for Avian Monitoring :**
What are the relationships and possible comparisons between 1990’s vs 2010’s avian data.
The research is to focus on data comparison between 1990s and 2010s and find if each species have increased or decreased in two time periods. Based on the results from two time periods, endangered or sensitive species can be identified and understand the results for better decisions. OWC can focus on the species and investigate more about their habitat loss and take steps to improve the habitat conditions. At this point, research only provides the species counts from two time periods. Are there any new species that are encounters in 1990s or 2010s but not in both time periods. Also, comparing Trail wise count comparison based on two time periods and find out which trail is best suitable or not suitable for overall birds or specific birds species what are endangered. 

eBird data and OWC data in 2010s can be compared to study how OWC has abundance of avians against eBird data. This study can help understand and identify if OWC bird encounters are more or less when compared with eBird data. This study also answers if the eBird reporting is different from OWC data. If the OWC encounters are more than eBird, then OWC has best conditions suitable for birds. Identify and focus on the species are that endangered and make comparisons between eBird data OWC data. Use R package for eBird data access and make comparisons with OWC data. eBird package is called [‘rebird’](https://cran.r-project.org/web//packages/rebird/rebird.pdf) package. 
____

### Bald Eagle Dataset: 

The locations for Bald Eagle are not based on trail, but they are collected based on location of their Nest. The Nest locations in OWC are West, West Nest 1, West Nest 2, East Nest, and Star Island. Observer moves around the OWC and makes their observations in using equipment. They note down information such as Date, Nest location, Net status, and # of birds(of course Bald eagles in this case) found in the nest. This data is mostly related to their Nesting patterns. These are very important attributes about this data. Compare and find the Nest patterns for Bald Eagles data from 1990s and 2010s. Based on the results OWC can focus on Nest Locations such as which location needs more attention if not they can find patterns. These patterns can be found against Nest condition and Nest Status. Nest conditions could be good or poor and there are some blanks too. Nest status includes I - incubation, H - hatched, BR - branching, F - fledged, A - abandoned and B - building. Compare Nest status incubation period from two periods 1990s and 2010s. 

Find the number of birds found in Nest during each Nest status. For example, during incubation how many birds are found in the nest 1A(1 adult). Get the average of the birds found in nest for entire incubation period and compare with old data and latest data.

Year wise comparison for the past three years i.e., 2016, 2017 and 2018. Find which Nest location is good for specific Nest status such as incubation, hatching, etc. Compare number of eggs and adult behavior, identify mostly common behavior. Primary advantage of results from the Nesting helps OWC to take decision related to Nesting locations, such as providing the Nesting conditions needed. Number of Eggs or Number of chicks against the number adults present in the nest. Study present of Juvenile and see if they return to the Nest after flying away from OWC Nests. Here, we are not doing comparison based on the temperatures and precipitation as its more complex and beyond scope of this project. Using R packages for each data analysis and creating visualizations based on Bald eagle data provided. 

OWC can use the visualizations results in their best management decisions and consider restoration and development of Nesting locations. They can improve the data management practices and minimize errors in storing data and avoid Null or blank values. Major decision that help Bald Eagles can be restoration of their Nest locations after analysing the two times period results. 
