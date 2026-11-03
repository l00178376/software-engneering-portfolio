# Task 1 
Decision points identified
No.	Condition	Decision point
1	dest.equals("LOCAL")	if
2	wt < 1	if
3	wt < 5	else if
4	dest.equals("NATIONAL")	else if
5	wt < 1	if
6	wt < 5	else if
7	wt < 1	if
8	wt < 5	else if
9	p	if
10	q > 10	if
Total decision points: 10

3. Cyclomatic Complexity Calculation
Cyclomatic complexity measures the number of independent paths through a method.

The formula is:
Cyclomatic Complexity = Decision Points + 1

Calculation:
M = 10 + 1
Cyclomatic Complexity = 11

McCabe's Threshold
McCabe's recommended threshold is 10.

Since the calculated complexity is 11, the method exceeds this threshold.

This suggests that the method is relatively complex and may require additional testing and maintenance effort.

4. Maintainability Issues Identified
The following issues were identified by reading through the code.

4.1 Duplicated Logic
The three destination branches (LOCAL, NATIONAL and other destinations) repeat the same weight-based calculation structure.
Although the shipping prices differ, the conditions are almost identical.
Impact: This duplication makes the code harder to maintain because changes may need to be made in several places.

4.2 Unclear Variable Names
Several variable names are shortened and do not clearly explain their purpose.

Examples:
wt — should be something like weight.
dest — should be destination.
p — should be isPremium or another descriptive name.
q — should be quantity.
c — should be shippingCost.
Impact: Unclear naming makes the code harder to read and understand, especially for developers who have not worked with it before.

4.3 Missing Input Validation
The method does not check whether the input values are valid.

For example:
Negative package weights are not handled.
Invalid destination values are automatically treated as international destinations.
There is no visible validation for other unexpected inputs.
Impact: Invalid inputs could result in incorrect shipping charges.

4.4 Hard-coded Values
Shipping prices and discount percentages are written directly into the method.
Examples:
2.50
5.00
0.5
0.9
Impact: Updating prices or discounts requires changing the method itself. Using named constants would improve maintainability.

4.5 High Cyclomatic Complexity
The method contains 10 decision points, giving it a cyclomatic complexity of 11.

Impact: A higher number of independent paths makes the method more difficult to test and maintain.

4.6 Multiple Responsibilities
The method calculates shipping costs and applies discounts within the same function.
Impact: Separating these responsibilities could make the code easier to understand, test and modify.

5. Internal Attributes vs Human Judgement
Some code quality concerns can be measured using software metrics or automated tools, while others require human judgement.

Maintainability concern	Measurable internal attribute	Human judgement
Cyclomatic complexity	Yes	Yes
Duplicated logic	Yes	Yes
Variable naming	Partially	Yes
Missing input validation	Partially	Yes
Hard-coded values	Yes	Yes
Multiple responsibilities	Not directly	Yes
Unclear destination handling	Partially	Yes

Explanation
Measurable internal attributes:

Cyclomatic complexity can be calculated by counting decision points.
Code duplication can be detected using code analysis tools.
Hard-coded values can be identified through static analysis.
Naming conventions can be checked automatically to some extent.
Human judgement:

Determining whether variable names are meaningful.
Deciding whether duplicated code should be refactored.
Evaluating whether a method has too many responsibilities.
Deciding whether the input validation is sufficient.
Automated tools can help identify potential problems, but human judgement is still important when evaluating overall code quality.

# Task 2
 Defect Density Calculations
The formula used is: Defect Density = Number of Known Defects / Product Size (KLOC)
System A
Known defects = 45
Product size = 30 KLOC
Calculation: Defect Density = 45 / 30
System A = 1.5 defects per KLOC

System B
Known defects = 15
Product size = 6 KLOC
Calculation: Defect Density = 15 / 6
System B = 2.5 defects per KLOC

System	Known defects	Product size	Defect density
System A	45	30 KLOC	1.5
System B	15	6 KLOC	2.5

Why the Comparison May Be Unfair
Defect density does not always provide a completely accurate comparison of software quality.

There are several reasons why comparing these two systems may be misleading.

 Different Testing Effort
One system may have undergone more extensive testing than the other.
A system with more testing may have more defects discovered and recorded, while a system with less testing may appear to have fewer defects simply because fewer problems have been found.

Different Defect Severity
Not all defects have the same impact.
For example, one system might contain several minor cosmetic issues, while another might have fewer defects but include a serious security or functionality problem.
Defect density does not distinguish between minor and critical defects.

Different Development Methods and Code Quality
The systems may have been developed using different programming languages, tools, coding standards or development processes.
These differences can affect the number of defects and make a direct comparison less reliable.
Other factors include differences in system complexity and how defects are identified and recorded.

Comparison with Reported Evidence
The calculated defect densities are:
System A: 1.5 defects per KLOC.
System B: 2.5 defects per KLOC.
These figures should be compared with the USA/Europe average and the level considered good, as reported in the lecture.
Interpretation
System A has a defect density of 1.5, while System B has a defect density of 2.5.
The lower the defect density, the better the apparent result, assuming the systems are measured consistently.
