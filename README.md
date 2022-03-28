# School_District_Analysis_Challenge

## Overview/Purpose of the Project:
   * The purpose of this project was to assist Maria and the schoolboard in correcting academic dishonesty. This was done by replacing Thomas Highschool's math and reading scores with NaNs and repeating the school district analysis we previously conducted. The following report describes how these changes affected the overall analysis.
   
## The Results:
   *  How is the district summary affected?
      * As seen in the images below, replacing Thomas High School's math and reading scores with NaNs had a **minimal** impact on the district summary. More specifically, if we were to round to the nearest whole number, the summaries would be identical. See below. 
        * Previous District Summary:
        ![Old_District_Summary](Resources/Old_District_Summary.png)
        
        * New District Summary:
        ![New_District_Summary](Resources/New_District_Summary.png)
        
   * How is the school summary affected?
     * After changes were made to Thomas High School, we can see a slight decrease in % Passing Reading, & Passing Math, and % Overall Passing. Each of the aforementioned categories decreased by at least .1%. 
     *  Despite replacing the ninth graders’ math and reading scores, Thomas High School remained a top five performer when compared to the other schools. see image below for detail.
    
        * Previous School Summary:
       ![OLD_SCHOOL_SUMMARY](Resources/OLD_SCHOOL_SUMMARY.png)
        * New School Summary
       ![NEW_SCHOOL_SUMMARY](Resources/NEW_SCHOOL_SUMMARY.png)
      
   * How does replacing the ninth-grade scores affect the following?:
     * Math and reading scores by grade: Math and reading scores remained the same. There was no impact.
     * Scores by school spending: Replacing the ninth-grade scores affected the percent of overall passing, specifically in the $585-630 spending range (increased by 9%)
     * Scores by school size: The scores by school size remained the same with no impact.
     * Scores by school type: The scores by school type remained the same with no impact.
     
## Summary:
   * Overall, the removal of the ninth-grade data for Thomas High School had a very minimal impact on the school district analysis, specifically on the School and District Summaries, Math and reading scores by grade, scores by school size, and scores by school type. Due to this minimal impact and in an attempt to save the school board's time, a limited amount of images was used for this write up. However, additional images can be provided upon request. A link to the copy of the code is provided below for the school board's easy reference. 
   * [PyCitySchools_Challenge](PyCitySchools_Challenge.ipynb)
