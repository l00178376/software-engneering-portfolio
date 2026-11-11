## Task 1 – Compare the Measures
1. Calculate LOC per month
Assembly language

Lines of code: 5,000
Effort: 28 person-weeks
Assuming 4 weeks per month: 28 / 4 = 7 person-months
Calculation:

5,000 / 7 = 714.29 LOC/month

High-level language

Lines of code: 1,500
Effort: 20 person-weeks
Assuming 4 weeks per month: 20 / 4 = 5 person-months
Calculation:

1,500 / 5 = 300 LOC/month

2. Compare productivity, delivery time and effort
Based on LOC/month, assembly language appears more productive because
it produces approximately 714 LOC/month compared with 300 LOC/month for the high-level language.

However, the high-level language actually delivered the system faster and with less effort:

Assembly language: 28 person-weeks.
High-level language: 20 person-weeks.
Therefore, the high-level language was faster and cheaper in terms of labour effort, despite having a lower LOC/month figure.

3. Calculate Function-Point productivity, duration and cost
Given:

Function points: 197
Productivity: 18 function points per person-month
Cost: €5,200 per person-month
Estimated duration:

197 / 18 = 10.94 person-months

Estimated labour cost:

10.94 × €5,200 = €56,911.11

Therefore, the estimated labour cost is approximately €56,911.11.

4. Why can LOC and Function Points give different conclusions?
LOC measures the amount of code written, while Function Points measure the functionality delivered to users. A high-level language can achieve the same functionality with fewer lines of code,
meaning that LOC may make it appear less productive even when it requires less effort.
Function Points focus more on what the software does rather than how much code is written.

Explanation of the disagreement between LOC and Function Points:
LOC suggests that assembly language is more productive because it produces more lines of code per month. 
However, the high-level language delivered the same system faster and with less effort, using fewer lines of code. 
This shows that LOC does not necessarily measure actual productivity, whereas Function Points focus on the functionality delivered rather than the amount of code written.

## Task 2 – Where Would This Mislead a Manager?
Memo to Management

Subject: Appropriate Use of Software Productivity Measurements

Software productivity measurements can be useful for project planning and monitoring, but raw Lines of Code (LOC) per month should not be used to compare individual developers in performance reviews.

LOC figures can be misleading because developers may use different programming languages, work on projects with different levels of complexity,
or have different levels of experience and working conditions. They can also encourage unnecessary code production rather than better-quality solutions.

For example, our assembly-versus-high-level language comparison showed that assembly produced 714 LOC/month, 
compared with 300 LOC/month for the high-level language. However, the high-level language delivered the same system faster, using only 20 person-weeks instead of 28. This demonstrates that more lines of code do not necessarily mean better productivity.

Productivity data is safer to use for team-level project estimation and tracking trends over time, 
provided that projects and working conditions are reasonably comparable and process quality is considered. 
However, it should not be used alone to reward or punish individual developers.
Managers should consider code quality, functionality, complexity and teamwork alongside productivity figures.
