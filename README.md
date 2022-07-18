# School_District_Analysis

# Purpose
The initial request of the school was from Maria to review top performing schools, bottom performing schools, along with their reading and math level averages displaying spend per student. After this we were to display the information by school size and type.

After finishing the initial review the school board requested another review to be conducted since Thompson High School had dishonesty about their 9th grade class. We were asked to replace all of the data from this class with Nans to essentially remove the data so it isn't counted. Once this data was removed, we reran the code to show new values with the dishonest information removed.

# Analysis Results

**How is the district summary affected?**
- Original Report:

![image](https://user-images.githubusercontent.com/107363048/179431584-931f30ab-5dbb-4076-ad93-880f6dadb5ea.png)

- New Report:

![image](https://user-images.githubusercontent.com/107363048/179431665-260df1e7-4281-4564-9d10-3220485702fd.png)

After removing the 9th graders the "Average Math Score" dropped .1% and "% passing Math" dropped .2%. The "Average Reading Score" stayed the same while the "% Passing Reading" dropped .1% The overall passing percentage dropped .3%. Overall there were small changes to the overall passing %.

**How is the School Summary Affected?**

- Original Summary Report:

![image](https://user-images.githubusercontent.com/107363048/179431948-5ffda7dc-e73e-4b48-92db-6ac3916e647a.png)

- New Summary Report:

![image](https://user-images.githubusercontent.com/107363048/179432175-10e417ff-1548-4884-9d80-571a0119b894.png)

After combing the data if we left the 9th graders in and went through with the analysis without displaying NaN the high school would suffer greatly on the overall passing %. The reading stays similar, but the overall math scores drop this significantly. 

Here's what Thomas High School looks like without removing the 9th graders:

![image](https://user-images.githubusercontent.com/107363048/179432329-b0673251-783f-484e-8467-e22e224d0c20.png)

Thomas High School dropped 25% on overall passing if we did not remove the dishonest data.

**How does replacing the 9th grader's math and reading scores affect Thomas High School's performance relative to the other schools?**

- Original Report:

![image](https://user-images.githubusercontent.com/107363048/179432564-3bd8f372-8fd4-48bd-8e5a-a3ae71395f43.png)


- New Report:

![Top 5 new summary](https://user-images.githubusercontent.com/107363048/179432579-6e29254b-9eba-4a97-b580-d5acdcb223a9.png)

Replacing the dishonest data does not move Thomas High School from their 2nd place standing amongst other schools. While the overall reading scores wouldn't change Thomas High School in the standings, their math scores would drop their overall passing outside of the top 5 schools.

**How does replacing the 9th grade scores affect the following:**

- Math and reading scores by grade:

![Math Scores by grade](https://user-images.githubusercontent.com/107363048/179432878-8cf75701-4cb0-4b23-90d1-9a5bfd1f5bfa.png) ![image](https://user-images.githubusercontent.com/107363048/179432898-82d8b890-aebf-4637-9b21-938003155614.png)

Both scores by grade don't change after removing the dishonest data.

- Scores by school spending:

![image](https://user-images.githubusercontent.com/107363048/179433068-34f8aecc-0655-4bff-bbc0-ee110bda9f1c.png)

The school spending ranges don't change at the whole integer.

- Scores by school size:

![image](https://user-images.githubusercontent.com/107363048/179433205-e20f4ce8-6689-457c-a4d3-5d6f3f02943d.png)

The school size doesn't change atthe whole integer.

- Scores by school type:

![image](https://user-images.githubusercontent.com/107363048/179433298-e4656d65-2e59-46a2-8e13-c16b40e9a757.png)

The school type doesn't change at the whole integer.

# Summary

The four changes that stuck out to me after reviewing reading and math scores for 9th grade at Thomas High School are replaced with NaNs are as follows:

- The overall passing % when removing the 9th grade class goes down .3% in total. 
- The Average Math Score goes down .16% in total.
- The % passing in math goes down .09% in total.
- The Average reading score goes up by .05% in total.

If we did not remove the 9th grade scores from Thomas High School their overall score would significantly suffer. While the 10th - 12th grade classes are scoring high enough to keep the High School in the top 2 the 9th grade class due to their dishonesty hurt the schools overall standing. Given the change in data it should prmopt an investigation into the 9th grade class to show if there was a substantial difference in their 9th grade class compared to other schools.
