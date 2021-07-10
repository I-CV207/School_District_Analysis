# School District Analysis

## Overview of the school district analysis

The purpose of this analysis is to transform the given data into a summary indicators are relevant for the school district, such as average math and reading scores, passing percentage, school budgets and so on, such indicators are going to be clasified into diffent categories, by school, by district, by student count, to name some. The final result will give us a general overview of the performance of the district and also give us some insight about what things can change by comparing and relating the different summaries that were created. It is important to take under consideration that the data from 9th graders from Thomas High School has been discarded as it is not trustworthy.

## Results

- How is the district summary affected?

At first sight it seems that the district summary was not affected into significant proportions by the changes applied, the difference can be seen when looking at the significant figures of the measures as seen on the images below.

***District summary before corrections***
![Before_district sumary](https://user-images.githubusercontent.com/83261520/125148055-2bb7b080-e0f5-11eb-8250-04008b8023cc.png)

***District summary after corrections***

![After_district summary](https://user-images.githubusercontent.com/83261520/125148019-f8752180-e0f4-11eb-9516-eb255eb03c1e.png)

- How is the school summary affected?

When it comes to the summary per school thing are now different for Thomas High School, its passing percentages decreased du to the removal of 9th graders, as seen on the images below (school sumary before corrections and school summary after corrections) its **math percentage** went from 93.27% to 66.91%, its **reading percentage** went from 97.30% to 90.94% and its **overral passing percentage** went from 90.94% to 65.07%. 

As it is an isolated event that only ocurred in Thomas High School some adjustements have to be made to disregard the number of 9th graders to adjust the student count that affected the percentages, after applying these adjustments the resultas can be seen on the third image (School summary after data adjustments), now the changes are not as big as they used to be, its **math percentage** went from 93.27% to 93.18%, its **reading percentage** went from 97.30% to 97.01% and its **overral passing percentage** went from 90.94% to 90.63%. 

***School summary before corrections***

![Before_per school summary](https://user-images.githubusercontent.com/83261520/125148469-0aa48f00-e0f8-11eb-9330-ef3b38c36a2b.png)

***School summary after corrections***

![after_per school summary](https://user-images.githubusercontent.com/83261520/125148472-0d06e900-e0f8-11eb-8905-96afdebd5b0d.png)

***School summary after data adjustments***

![after_adjustments_per school summary](https://user-images.githubusercontent.com/83261520/125148822-93242f00-e0fa-11eb-849c-8fc0d1b1937a.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

By replacing the 9th graders and adjusting the measures, Thomas High School kept his spot as the second best school by performance, just below Cabrera High School as seen on the images below.

***Top 5 Schools before corrections***

![top5_before](https://user-images.githubusercontent.com/83261520/125149038-1d20c780-e0fc-11eb-8d5a-d9beea3aa277.png)

***Top 5 Schools after corrections***

![top5_after](https://user-images.githubusercontent.com/83261520/125149039-1eea8b00-e0fc-11eb-86bc-d56d8fb48c51.png)

### How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade

As seen on the images below, math and reading grades were only affected in Thomas High School and only for 9th graders, instead of having an average scores of 83.6 and 83.7 in math and reading respectively they are now shown as NaN.

***Math scores per grade before corrections***

![math scores before](https://user-images.githubusercontent.com/83261520/125149276-b4d2e580-e0fd-11eb-9834-d3d284e846fc.png)

***Math scores per grade after corrections***

![math scores after](https://user-images.githubusercontent.com/83261520/125149279-b7cdd600-e0fd-11eb-91d8-f3a507a3bb28.png)

***Reading scores per grade before corrections***

![reading scores before](https://user-images.githubusercontent.com/83261520/125149281-ba303000-e0fd-11eb-92ed-9fbea0b0402e.png)

***Reading scores per grade after corrections***

![reading scores after](https://user-images.githubusercontent.com/83261520/125149331-31fe5a80-e0fe-11eb-8e31-3ce922c78bc4.png)


- Scores by school spending

There is no significant change in the *scores by school spending*, as 0 and 1 significant figures were used for this summary the difference cannot be appreciate it.

***Scores by school spending***

![spending](https://user-images.githubusercontent.com/83261520/125149551-3f681480-e0ff-11eb-836d-1176a256f49a.png)


- Scores by school size

Just as in *scores by school spending* it is the same case with *scores by school size*, as 0 and 1 significant figures were used for this summary the difference cannot be appreciate it.

***Scores by school size***

![size](https://user-images.githubusercontent.com/83261520/125149712-2449d480-e100-11eb-9a1c-ffb0d973d944.png)


- Scores by school type

Lastly just as in *Scores by school spending* and *Scores by school size* the result is the same in *scores by school type*, as 0 and 1 significant figures were used for this summary the difference cannot be appreciate it.

***Scores by school type***

![type](https://user-images.githubusercontent.com/83261520/125149777-928e9700-e100-11eb-8210-55b451006262.png)

## Summary

Overall the main changes that were seen on the school district analysis by replacing reading and math scores for the ninth grade at Thomas High School with NaNs are:

1. Passing percentages for math, reading and overall in Thomas High School dropped significantly due to the fact that the scores of 9th graders were disregarded but they were still cosidered for the total count of students.

2. After adjusting the measures by substracting the student count of 9th graders in Thomas High School, math, reading and overall scores were different than in the original analysis.

3. When looking at the scores by grade and school, math and reading scores of 9th graders from Thomas High School are nowhere to be seen as such data was disregarded.

4. Practically the rest of the created summaries changed, however such differences cannot be seen due to the significant figures that were used to show the results, meaning that the disregarded scores were close to the overall average and also because the sample that was disregarded was not too big (461 records out of 39170), approximately 1.2% of the total number of records. 


