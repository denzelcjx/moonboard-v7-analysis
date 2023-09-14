# moonboard-v7-analysis
## Analysis of V7 benchmarks by average user gradings

The MoonBoard is a standardised training board for rock climbing which allows users 
to create problems and climb problems set by other climbers using the Moonboard app. 
The MoonBoard sits at a 40 degree angle, and has 3 different configurations of 
holds: 2016, 2017, and 2019. Each problem is assigned a grade by the setter, and 
once users complete the problem, they can log the entry into their logbook and 
choose the grade they feel the problem should be assigned. Problems can be chosen 
to be Benchmarks by moderators, which can contribute to a users ranking on their 
local leaderboard. 

In this (rudimentary) Excel spreadsheet, I analyse the average user grading and 
standard deviation of the user gradings across (setter-graded) V7 Benchmarks. Due 
to the constraints of being only able to fetch the problem configuration, number of 
repeats, and setter information from the spookykat/MoonBoard API wrapper, I manually 
collected the problem information and the user gradings from the app. Thereafter, 
I calculated the **user grading averages** of each V7 Benchmark problem and the 
**standard deviation** of the user gradings (excluding the highest user gradings 
as they are most likely trolls lol).  

I also plotted a graph with the **user grading averges**, the **standard deviation** 
of the user gradings, and also the **number of repeats** to glean potential insights 
on the correlation between these variables. In the "SETTERS" sheet, the user grading
averages of each setter can be sorted. Variables can also be sorted to view the number 
of repeats, user grading averages and standard deviation of problems across the 
V7 Benchmark catalogue.

### Some constraints:
1. Data is not dynamic and has to be manually keyed in/ updated.
2. some V gradings (i.e. V5 and V8) encompass 2 gradings on the Font Scale (6c/6c+, 7b/7b+).
3. Comments (hence user sentiments) are not considered.
4. Different users has different strengths and body morphology, which is not factored in.
