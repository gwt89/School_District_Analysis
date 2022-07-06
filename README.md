# School_District_Analysis
## Overview of the school district analysis
The data found in students_complete.csv appears to show academic dishonesty; specifically, the reading and math grades for ninth grade at Thomas High School. In order to uphold state testing standards these math and reading scores for Thomas High School have been replaced with NaNs. The impact of the NaNs will be detailed throughout the analysis.
## Resources
Data Source: students_complete.csv, schools_complete.csv

Software: Python 3.10, Jupyter Notebook, Anaconda
## Results
•	How is the district summary affected?

The Average Reading Score dropped .1%. The Passing Math % dropped .1%. The Passing Reading % dropped .1% and the Overall Passing % dropped .2%.

This top image shows the District Summary before the NaNs were introduced.

![District Summary Before NaNs](https://user-images.githubusercontent.com/105949411/177436855-9744c0ab-e09f-4895-98bc-2ddd9f2050c1.png)


This bottom image shows the District Summary after the NaNs were introduced.

![District Summary After NaNs](https://user-images.githubusercontent.com/105949411/177436858-8e154e37-bf2b-4ecd-af2b-37dcd1f22ed3.png)

•	How is the school summary affected?

The Overall Passing % dropped from 90.9% to 90.6%. The Passing Reading % dropped from 97.3% to 97%. The Passing Math % dropped from 93.2% to 93.1%. The Average Reading Score saw little change. The Average Math Score dropped from 83.4% to 83.3%.

This top image shows the School Summary before the NaNs were introduced.

![School Summary Before NaNs](https://user-images.githubusercontent.com/105949411/177440650-b0a932fc-01b7-4c0f-9620-713796dfa421.png)

This bottom image shows the School Summary after the NaNs were introduced.

![School Summary After NaNs](https://user-images.githubusercontent.com/105949411/177440694-369e3043-89df-46c6-8999-7434aead38e0.png)


•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Changing the ninth graders math and reading scores for Thomas High School had little impact on the schools performance. The school did perform slightly worse when comparing their before and after results of introducing the NaNs but not enough to change any scores by even 1 percentage point. The school also did not slip in its rankings compared with other schools. The school was ranked 2nd, both before and after the NaNs were introduced.

This image shows the top schools before the NaNs were introduced.

![High Performing Schools Before](https://user-images.githubusercontent.com/105949411/177441502-1c6a902d-3189-4c44-b426-e9a14aa56cf1.png)

This image shows the top schools after the NaNs were introduced.

![Top Performing Schools After](https://user-images.githubusercontent.com/105949411/177441624-09191166-0838-4262-8be2-953886ea9313.png)


•	How does replacing the ninth-grade scores affect the following:

o	Math and reading scores by grade

All scores for ninth grade in both reading and math have been switched to NaNs.

This image shows the reading scores by grade.

![Reading Scores By Grade](https://user-images.githubusercontent.com/105949411/177441751-e4c6ce8e-90c1-42a9-92f5-a9995302ba0f.png)

This image shows the math scores by grade.

![Math Scores By Grade](https://user-images.githubusercontent.com/105949411/177441841-01c737af-931c-4a1c-a689-db8eb946f5a2.png)

o	Scores by school spending

There is no difference in the Average Math and Reading Scores after the replacement. However the Overall Passing % was slightly higher for all Spending Ranges after the the replacement.

This image shows the scores by spending before the NaNs were introduced.

![Scores By School Spening Before NaNs](https://user-images.githubusercontent.com/105949411/177442127-54cefc8d-8a7c-4dda-a0cb-5fcfb284396a.png)

This image shows the scores by spending after the NaNs were introduced.

![Scores By School Spending After NaNs](https://user-images.githubusercontent.com/105949411/177442496-0d1bfa76-777f-494b-ba16-d3f0437fd093.png)

o	Scores by school size

There is no difference in scores by school size after the replacement.

This image shows the scores by school size before the NaNs were introduced.

![Scores By School Size Before NaNs](https://user-images.githubusercontent.com/105949411/177442826-f7ff6d98-45f7-433c-a5eb-f781b4c07072.png)

This image shows the scores by school size after the NaNs were introduced.

![Scores By School Size After NaNs](https://user-images.githubusercontent.com/105949411/177443232-17d5e734-8fa6-40d3-8863-94e9d6eadeaf.png)

o	Scores by school type

There is no difference in scores by school type after the replacement.

This image shows the scores by school type before the NaNs were introduced.

![Scores By School Type Before NaNs](https://user-images.githubusercontent.com/105949411/177443343-fe4b4061-42e0-411d-bc7b-7d34f5238014.png)

This image shows the scores by school type after the NaNs were introduced.

![Scores By School Type After NaNs](https://user-images.githubusercontent.com/105949411/177443901-6dce709d-3b62-44fe-b641-2608748f18c2.png)

## Summary
4 changes in the School District Analysis

There were some minor changes to the District Summary. The Average Reading Score dropped .1%. The Passing Math % dropped .1%. The Passing Reading % dropped .1% and the Overall Passing % dropped .2%.

The School Summary was effected the new analysis. The Overall Passing % dropped from 90.9% to 90.6%. The Passing Reading % dropped from 97.3% to 97%. The Passing Math % dropped from 93.2% to 93.1%. The Average Reading Score saw little change. The Average Math Score dropped from 83.4% to 83.3%.

Scores by School Spending changed slightly. There is no difference in the Average Math and Reading Scores after the replacement. However, the Overall Passing % was slightly higher for all Spending Ranges after the the replacement.

In the original School Summary generated in the PyCitySchools_Challenge, Thomas High School math and reading scores dropped draumatically. After using the loc method to create a new DataFrame with the passing reading and math scores; the reading and math scores went back up.

![Score Change 1](https://user-images.githubusercontent.com/105949411/177459446-8ac09372-ea79-4764-907a-13ea5694cd87.png)
![Score Change 2](https://user-images.githubusercontent.com/105949411/177459453-4171c204-8971-4d8b-90fb-4ecd776e0eb8.png)


