### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE:01-03-2024
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
### EMPLOYEE DATASET
![image](https://github.com/Ashwinkumar26/WDM_EXP2/assets/145831269/decbaaa8-20b3-4aec-98bf-f124405689c0)

### BANKING DATASET
![image](https://github.com/Ashwinkumar26/WDM_EXP2/assets/145831269/9675cd2c-abb0-4df3-984d-7d921cf9b0bd)
### BUYING DATASET
![image](https://github.com/Ashwinkumar26/WDM_EXP2/assets/145831269/28a39101-041a-4840-bc1d-a88ac8412c39)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
### EMPLOYEE DATASET
![image](https://github.com/Ashwinkumar26/WDM_EXP2/assets/145831269/327b4885-53af-443e-bbdf-304bbe0fa690)
### BANKING DATASET
![image](https://github.com/Ashwinkumar26/WDM_EXP2/assets/145831269/3f64498b-df36-467d-9559-e57447aed030)
### BUYING DATASET
![image](https://github.com/Ashwinkumar26/WDM_EXP2/assets/145831269/9379cba5-ab4a-4248-8bd5-a6e8eee5d233)

### RESULT: 
Thus the program has been successfully executed.
