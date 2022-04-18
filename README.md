# PyCity Schools with Pandas

## Project Overview

The school board notified Maria that there are signs of academic dishonesty regarding math and reading scores for ninth grade students at Thomas High School. Maria wants the scores removed from the data and the analysis redone that way a comparison can be done to see how the removed scores affects the overall results.

## Resources

- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.11, Jupyter Notebook 6.4.5

## Results

- How is the district summary affected?
  - The average math score fell by 0.1
  - The percentage of students passing math fell by 0.2%
  - The percentage of students passing reading fell by 0.3%
  - The percentage of students passing both math and reading fell by 0.1%
  - Original District Summary:
  ![District_Summary](Resources/District_Summary.png)
  - New District Summary:
  ![New_District_Summary](Resources/New_District_Summary.png)
- How is the school summary affected?
  - The only school affected in the new analysis was Thomas High School
  - The average math score dropped by 0.067412
  - The average reading score increased by 0.047152
  - The percentage of students passing math dropped by 0.086581%
  - The percentage of students passing reading dropped by 0.29013%
  - The percentage of students passing both math and reading dropped by 0.317688%
  - Original School Summary:
  ![School_Summary](Resources/School_Summary.png)
  - New School Summary:
  ![New_School_Summary](Resources/New_School_Summary.png)
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Replacing the ninth graders' math and reading scores ultimately did little to affect Thomas High School's position as the number two school.
  - Original top schools' scores:
  ![Top_Schools](Resources/Top_Schools.png)
  - New top schools' scores:
  ![New_Top_Schools](Resources/New_Top_Schools.png)
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - The only math scores affected are the ninth graders' math scores, which are now denoted with "NaN" instead of the original score of 83.6.
    - Original math scores by grade:
    ![Math_Scores_By_Grade](Resources/Math_Scores_By_Grade.png)
    - New math scores by grade:
    ![New_Math_Scores_By_Grade](Resources/New_Math_Scores_By_Grade.png)
    - The only reading scores affected are the ninth graders' reading scores, which are now denoted with "NaN" instead of the original score of 83.7.
    - Original reading scores by grade:
    ![Reading_Scores_By_Grade](Resources/Reading_Scores_By_Grade.png)
    - New reading scores by grade:
    ![New_Reading_Scores_By_Grade](Resources/New_Reading_Scores_By_Grade.png)
  - Scores by school spending
    - The average math and reading scores by spending were not affected.
    - Original scores by spending:
    ![Scores_By_Spending](Resources/Scores_By_Spending.png)
    - New scores by spending:
    ![New_Scores_By_Spending](Resources/New_Scores_By_Spending.png)
  - Scores by school size
    - The average math and reading scores by school size were not affected.
    - Original scores by size:
    ![Scores_By_Size](Resources/Scores_By_Size.png)
    - New scores by size:
    ![New_Scores_By_Size](Resources/New_Scores_By_Size.png)
  - Scores by school type
    - The average math and reading scores by school type were not affected.
    - Original scores by type:
    ![Reading_Scores_By_Grade](Resources/Reading_Scores_By_Grade.png)
    - New Scores by type:
    
      ![New_Reading_Scores_By_Grade](Resources/New_Reading_Scores_By_Grade.png)

## Summary

In summary, when the ninth grade math and reading scores were taken out, Thomas High School's overall performance compared to rival schools stood strong due to solid grades from the upperclassmen. No scores or percentages for Thomas High School dropped by more than 0.32% and was able to retain the number two spot for top schools. Lastly, replacing the ninth graders' scores with no score ultimately did little to affect the school's overall performance by grade, spending, size, and type.
