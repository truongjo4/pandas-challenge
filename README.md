# pandas-challenge

You are the new Chief Data Scientist for your local government area. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyse the area-wide standardised test results. You'll be given access to every student's maths and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.
------
### File Structure
PyCitySchools - contains the script (main.py) and main CSV file (Resources)

------------------------
# Analysis Write-up
To see various trends in school performance in terms of standardised test results, I have conducted both area-wide and school-wide analyses. Additionally, the relationship between several variables were also investigated.

## Area-wide analyses:
-	This analysis included 15 schools and ~39,000 students.
-	The total budget across all schools sum to 25 million.
-	Marginal difference in the average scores of math and reading, with math scores edging out over reading scores.
-	Similarly, only small percentage differences in students that pass (obtained >50 in their test results) their math and reading exams (~85%)
-	Overall, this suggests that the majority of students pass their tests – a promising trend.

## School-wide analyses
-	For this analysis, there were 8 independent schools (7 government).
-	The budget for each school is very varied, from 248k (Holden High School) to 3.1m (Bailey High School). However, all schools’ budget average out to ~$600 per student – showing how budget is quite correlated to its size.
-	The percentage of students that pass both maths and reading is also quite varied between schools, ranging from 66% (Hernandez High School) to 81% (Griffin High School).
-	Generally, students from independent schools pass both tests at a higher frequency (3/5 of schools in the top five schools based on % overall pass are independent). The majority of the bottom five-performing schools are government schools (4/5)

## Year Level Analysis:
-	There is not much difference between students of different year levels (year 9 – 12) in terms of their average maths or reading scores – even across schools.
Budget spending analysis (per student budget)
-	Interestingly, schools with higher per student budget have a lower % overall passing rate. Schools that have a per student budget range of $585-630 have a higher overall passing rate among students.
o	Perhaps this is due to schools with a small budget and low student count – indicating that these schools may only enrol students that are on average more academically proficient.

## School size analysis
-	Supporting the previous hypothesis, schools with higher student count numbers on average perform worse (lower % overall passing) than schools with a small student population.

## School type analysis
-	As predicted before, independent schools generally perform better than government schools in terms of their average % overall passing metric.



