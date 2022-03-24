# Investigate_a_Dataset
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.

● A number of characteristics about the patient are included in each row.

● ‘ScheduledDay’ tells us on what day the patient set up their appointment.

● ‘Neighborhood’ indicates the location of the hospital.

● ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

● Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

Question(s) for Analysis :-
What are the factors that affect the attendaance of patients ?

Data Wrangling
In this section of the report, I will load in the data, check for cleanliness, and then trim and clean my dataset for analysis. Make sure that I document my data cleaning steps in mark-down cells precisely and justify my cleaning decisions.

General Properties
I won't perform too many operations in each cell.

I wil Create cells freely to explore my data.

One option that I can take with this project is to do a lot of explorations in an initial notebook.

I will make sure to use enough comments to understand the purpose of each code cell.

I will create a duplicate notebook where I will trim the excess and organize my steps for final report.

Data Cleaning
After discussing the structure of the data and any problems.

I will clean and perform those cleaning steps.

General Properties :-
I will be sure to keep my reader informed on the steps that i will take in my investigation.

I will Follow every code cell, or every set of related code cells, with a markdown cell to describe to the reader what was found in the preceding cell(s).

So that the reader can then understand what they will be seeing in the following cell(s).

Data wrangling summary:
First I loaded my data and print out a few lines, Perform operations to inspect data types and looked for instances of missing data.

Then I checked the shape, duplicate rows, unique values, duplicated patients IDs, missing values or other issues and described my data

Finally I cleaned my data by remove mistake values, correct the columns name, Clean duplicated and clean unnecessary data.

Exploratory Data Analysis
Now that Ihave trimmed and cleaned my data, I'm ready to move on to exploration. Compute statistics and create visualizations with the goal of addressing the research questions that I posed in the Introduction section. I will compute the relevant statistics throughout the analysis when an inference is made about the data. At least two or more kinds of plots I will created as part of the exploration, and I will compare and show trends in the varied visualizations.

I will investigate the stated question from multiple angles. I will be systematic with your approach. I will Look at one variable at a time, and then follow it up by looking at relationships between variables. I will explore at least three variables in relation to the primary question. This can be an exploratory relationship between three variables of interest, or looking at how two independent variables relate to a single dependent variable of interest. Lastly, I will perform both single-variable (1d) and multiple-variable (2d) explorations.

Conclusions
The number of attended patients who received SMS less than the number of absent patients who received SMS. So we must revise our SMS campaign.

The most showing of ages are from 0 to 8 after that the ages from 45 to 55 and the least attendance above 65 .

There is a correlation between age and chronic diseases . There isn't a correlation between chronic diseases and attendance .

Gender hasn't Clear effect on the attendance.

There is no clear affected of gender with age & chronic diseases at the attendance by mean or median.

Our SMS campaign need to be evaluated since there are more showing patients without SMS than showing patients with SMS .

I see the neighbourhood affected on the attendance.

The effect of Neighbourhood SMS_received at the attendance in only five neighbourhood

IL HAS OCEANICAS DE TRINADE is the most responsive to SMS.

There are different attended from Neighbourhood to other.

There are Neighbourhood where the average age is large but no one came from them.

AEROPORTO then ILHADOBOI are with high ages attendance .

Limitations
No clear correlation exists between showing and gender, chronic diseases, or welfare program enrollment.
