# School_District_Analysis
Python and Pandas
# School District Analysis Challenge

**General overview

I removed Thomas High School 9th graders' math and english scores, replacing them with NaN, and NOT zero.  Because the grades were very similar to other grade levels at Thomas High School as well as other high schools, the average grades did not change markedly.  Because the students still stayed in the analysis, ie the denominator, leaving them in to include them in spending per student made sense, but leaving the students in the denominator while calculating passing rates negatively affected Thomas High School as well as the groups that Thomas High School was grouped in (Charter Schools, Medium sized schools, spending per student in the $630-$644 bucket schools).  

The negative impact was greater when the overall number of schools in the bucket was smaller, as would be expected.  Because there are only 15 schools, it is a difficult decision as removing those students from the analysis would change the results of spending per student, charter vs public, etc, and yet leaving them in while removing their scores also leads to different analyses.

**Specific Questions:

**(1) How is the district summary affected?

The district summary is affected the least because the data is spread over the most number of students.  For this reason, I analyze this data down to the hundredths, in order to better illuminate the change.  Seeing as the average scores for Thomas High School were in line with the removed scores, the grades did not change, but rather the passing percentages changed because the number of students in the denominator remained the same as before.

Average math score declined from 78.99% to 78.93, so minimally.
Average reading score declined from 81.88% to 81.86%, also minimally.
Percentage of students passing math declined from 74.98% to 73.88%
Percentage of students passing reading declined from 85.81% to 84.65%
Percentage of students passing both reading and math declined from 65.17% to 64.09%.

**(2) How is the School Summary affected?

Although passing rates come down slightly as we mentioned in the district summary above, the passing rates of other schools are not impacted, so it is the relative performance of Thomas High School that is affected the most.  The school summary is affected principally by the reduced ranking of Thomas High School.  Thomas High School was the #2 ranked school in terms of overall passing rates, with a district-leasing reading pass rate and a more middling math pass rate.  

**Removing the Thomas High School 9th graders' math and reading scores moves Thomas High School from 2nd place to 8th place, the exact middle of the pack of 15 schools, which coincidentally more in line with how their math passing rate would have ranked them.  

This does bring up the potential validity of the worry that there was cheating, because where Thomas shines is that the SAME people who passed math, passed reading, ie the high overlap between those who pass math and those who pass reading is what raised their place in the rankings.  This might warrant looking into school officials and whether they were motivated to change these grades.

**(3) What is the impact to Thomas High School performance?

Average math and reading score declined minimally, as the scores removed were in line with the scores that remain.
For example, the average math score declined from 83.47% to 83.35%, and the average reading score actually slightly increased from 83.85% to 83.89%.  

Since Thomas High School is the smallest microcosm of the impact on changing these grades, any larger pool or grouping will see infinitessimal changes in average grades.  This is not the same for passing rates which move more because the denominator of the number of students stays the same and then all those 9th graders are not included in the numbers of students who pass at Thomas High School.  I mention below under the section "more data needed" what additional comparisons might be helpful to draw more concrete conclusions from the Thomas High School data.

Percentage of students passing math declined from 93.3% to 66.9%
Percentage of students passing reading declined from 97.3% to 69.7%
Percentage of students passing both reading and math declined from 90.9% to 65.1%

**(4) How is the per grade results for math and reading affected?

For Thomas High School, 9th grade math and reading scores are removed.  This does not affect the math and reading scores of any other school, and in general, many schools have eerily similar scores.  It improves the relative performance of other schools, but more in pass rates which are affected by the denominator effect.  Scores were so in line with the rest of the grades and the rest of the schools that the removal of grades did not affect average scores.

**(5) How are the results for scores by school spenging affected?

As Thomas High School is within the bucket of schools who spend $630-$644 on their students, the performance of the students in that bucket and their performance relative to students in other buckets was affected.

Average math and reading score declined minimally.
Percentage of students passing math declined from 73% to 67%
Percentage of students passing reading declined from 84% to 77%
Percentage of students passing both reading and math declined from 63% to 56%

**(6) How are the results for scores by school size affected?

Thomas High School is in the bucket of medium sized schools, and thus only the average passing rates of medium sized schools were impacted, however, this also lowered the relative performance of medium sized schools, especially because the number of schools in the district is only 15 total schools.  In fact, the comparative analysis of school size conclusion changes, with the highest overall passing score no longer being for medium sized schools.  Now the smaller the school the better the passing percentage, with small schools having better passing percentages than medium which are still better than large.  Prior to this change, medium sized schools had the best passing percentages.  This is not a conclusive result though because keeping the same denominator of the number of students greatly negativley impacts the performance of passing percentages, whereas you can see the average grades stay the same.  However, if you remove all those students, you lose information around spending per student, size of schools, etc. that is both valid and relevant for the district to make their analyses.

Average math and reading scores declined very minimally.
Percentage of students passing math declined from 94% to 88%
Percentage of students passing reading declined from 97% to 91% 
Percentage of students passing both reading and math declined from 91% to 85%

**(7) How are the results for scores by school tyupe (Charter vs District) affected?

Since Thomas High School is a Charter School, the removing of 9th graders scores only changed the percentage passing results for charter schools, however, it resulted in a lower pass rate and therefore less outperfornance vs district schools.
Average math and reading scores declined very minimally.
Percentage of students passing math declined from 94% to 90%
Percentage of students passing reading declined from 97% to 93%
Percentage of students passing both reading and math declined from 90% to 87%
This change in results therefore made charter schools seem less superior, although still markedly superior, in performance.

**More data needed, and more analysis

While it is necessary to include all students to determine spending per student and size of school in the district's plans, it would be instructive to look at math, reading, and overall passing rates of Thomas High School Students with the 9th graders grades completely removed, so see how the rest of the school stacks up perfornamce wise with the other schools in the district.  Additionally, a chart showing before taking out the grades, then with the grades as NaN with the students included in the statistics, and thirdly, the data with the 9th graders removed.  This chart could better show us what the right path is with the data, and whether to use it or how to change it on a broader basis once you analyze it for Thomas High School.

Perhaps this is because this is just an exercise, but I did find it odd that so many schools had very close average math scores and average reading scores.  I would have expected more of a range between grades and between schools.  This makes it harder to determine whether there was cheating, because one cannot quickly presume that the grades put in were "fitted too well" because many of the grades across the school system seem too close together.

