
# STUDENTS RESULT ANALYSIS

Student result analysis involves evaluating academic performance data to identify trends, strengths, and areas for improvement among students. This process typically includes examining grades, test scores, and other assessments to understand how students are performing individually and collectively. By analyzing this data, educators can make informed decisions about curriculum adjustments, targeted interventions, and support strategies, ultimately aiming to enhance student learning outcomes and foster academic success..




## DATASET

`STUDENTSCORES.csv`


## RUNNING THE ANALYSIS LOCALLY 
Get the repository cloned or forked 
```bash 
git clone https://github.com/SUVAJIT-KARMAKAR/STUDENT-RESULT-ANALYSIS.git
```
Navigating to the project directory 
```bash
cd STUDENTS-RESULT-ANALYSIS
```
Installing the required packages for the analysis 
```bash
pip install numpy 
pip install pandas
pip install matplotlib
pip install seaborn 
```
Run the .ipynb file
```bash
RESULTSANALYSIS.ipynb
```
## STEPS TAKEN FOR THE ANALYSIS
- Importing the required modules in the workspace.
- Reading the csv file in the workspace.
- Head values in the dataset.
- Describing the dataset.
- Retriving basic information about the dataset.
- Calculating total null values present in the dataset.
- Dropping the unnamed column from the dataset.
- Replacing the `WklyStudyHours` into proper format.
- Getting a box plot for outlier detection in the `MathScore`.
- Getting the box plot for outlier detection in the `ReadingScore`.
- Getting the box plot for outlier detection in the `WritingScore`.
- Getting gender distribution chart.
- Getting a heat map on the influence of parent education on students marks.
- Getting a heat map on the influence of parents marital status on students marks.
- Ethnic group distribution using pie chart.





