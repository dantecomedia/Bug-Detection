# Bug-Detection
Bug Detection

This uses different Machine Learning and Deep Leanring technique to detect bug.

Metric Description

NS



Number of subsystems touched by the current change
ND
Number of directories touched by the current change
NF
Number of files touched by the current change
Entropy
Entropy Distribution across the touched files, i.e. −Σ n
k−1 p k log 2 p k ,
where n is the number of files touched by the change and
pk is the ratio of the touched code in the k-th file to the
total touched code



LA
Lines of code added by the current change
LD
Lines of code deleted by the current change
LT
Lines of code in a file before the current change
FIX
Whether or not the current change is a defect fix
NDEV
The number of developers that changed the files
AGE
The average time interval (in days) between the last and the change over the files that are touched
NUC
The number of unique last changes to the files
EXP
Developers experience, i.e. the number of changes
REXP
Recent developer experience, i.e. the total experience of the developer in terms of changes, weighted by their age
SEXP
Developer experience on a subsystem, i.e. the number of changes the developer made in the past to the subsystems



----------------------------------------------------------------------------------------------------------------------

![Report for the models](https://github.com/dantecomedia/Bug-Detection/blob/master/1.PNG)
![Report for the models](https://github.com/dantecomedia/Bug-Detection/blob/master/2.PNG)




















